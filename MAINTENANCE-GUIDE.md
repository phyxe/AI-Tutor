# Teacher guide: pause for instruction updates

Edit the root `TUTOR-STATUS.md`, then commit and push it before changing the affected teaching files. Local edits are not visible to student chats. This is an operational notice, not a student outcome record.

## Activate a hold

Set these fields in that file (example only; the date/time below is not an actual scheduled hold):

```yaml
notice_id: teacher-chosen-unique-update-id
status: updating
scope: selected
learning_areas: [pr2]
activities: [pr2_act_02]
timezone: Asia/Manila
expected_resume_at: "YYYY-MM-DDTHH:MM:00+08:00"
updated_at: "YYYY-MM-DDTHH:MM:00+08:00"
recheck_interval_student_turns: 5
```

Replace the timestamp placeholders with actual Philippine local date/times before publishing. Use `scope: all` for every area/activity. With `scope: selected`, a matching learning-area folder OR exact activity code activates the hold; use `learning_areas: []` when pausing only one activity. Folder identifiers currently include `pr2` and `effcom`. Do not include student identities in notices.

Write a short student-facing explanation in the body, such as “Your teacher is improving the activity instructions. Please keep your handoff and return after the expected completion time.” The tutor supplies the actual timestamp from metadata. Do not put alternate teaching instructions or answer content here.

## Student behavior

At its next scheduled successful notice check, an affected tutor stops new learning/final export, creates a cumulative work-in-progress Markdown handoff if file tools are available, then explains the update and expected return time. Students can download that file for resumption or interim teacher collection. A tool failure is disclosed: retain the existing chat and latest actual save; do not require manual assembly, promise an uncreated file, or instruct them to leave without a save.

No prompt can push an update into an inactive chat or guarantee immediate detection. Checks occur at entry/resume, stage boundaries, before final export, after the configured student-turn interval, and when the student reports a teacher update. Five turns is an operational polling interval, not an estimate of account quota. More frequent checks add retrieval overhead. Avoid duplicate checks in the same response.

If students are already using old instructions, send them this message through your normal teaching channel yourself:

> My tutor instructions are being updated. Ask the tutor to reread the current GENERAL-TUTOR.md and TUTOR-STATUS.md in phyxe/AI-Tutor before continuing, and follow the maintenance handoff instructions.

This guide does not send a message to students automatically.

## Clear the hold

Finish and verify the affected files, publish them, then set `status: ready` and update the notice ID/time before publishing the ready notice. Keep the teacher announcement accurate. The tutor must recheck the live notice and changed instructions before resuming; it does not automatically restart in the background.

The expected time is an estimate, not an automatic release. If `status` remains `updating` after that time, the hold remains active. Extend the timestamp if delayed. If no trustworthy clock is available, the tutor quotes the exact teacher-provided date/time and timezone without inventing a countdown.

Never mark `ready` until the intended update is actually published. A read error is not evidence that maintenance is active or cleared; the tutor reports that status could not be verified and preserves progress.
