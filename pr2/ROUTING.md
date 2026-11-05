---
id: PR2-ROUTING
version: 0.1.0
status: teacher-review
---

# PR2: outcome-file conversation entry and routing

Use this file with `../GENERAL-TUTOR.md`, `AREA-INSTRUCTIONS.md`, the student's exact teacher-issued outcome URL, and the selected activity. It selects the current task; it cannot waive activity prerequisites, approval requirements, authorship checks, or the `.phx` completion gate.

## 1. Student entry

The intended student starter is:

> I am taking PR2 and you will help me by following my progress located in: [my teacher-issued GitHub outcome-file URL]

The outcome file contains the controlling-file links and teacher-maintained route. A GitHub URL is an entry locator, not evidence that its contents or linked files were read. Retrieve the actual files before proceeding. Prefer the exact teacher-issued raw text URL. Do not guess another student's URL, search by name, or request an identity mapping.

Follow the outcome filename/YAML/student-code binding. Parse activity Level 1 sections outside fenced code; entry instructions before them are not an activity outcome. The teacher-maintained route fields at the document level select one section. Read comments only from the selected activity; earlier outcomes may supply prerequisites explicitly requested by that activity, not unrelated instructions.

## 2. Exact activity map

| route_activity | Activity file |
|---|---|
| pr2_act_01 | https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/pr2_act_01.md |
| pr2_act_02 | https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/pr2_act_02.md |

No other activity is defined by this router. Missing, unknown, or inaccessible activity files require teacher clarification. The URLs are intended deployment locations, not proof that a draft has been published or approved for release.

## 3. Route fields and actions

The teacher edits these YAML fields in the student's outcome record:

- `route_activity`: one exact activity code from the map.
- `route_action`: INITIAL, RESUME, REVISION, WAIT, or COMPLETE.
- `route_directive_id`: exact teacher directive ID for REVISION; otherwise Not applicable unless relevant.
- `route_baseline_revision`: identified baseline for REVISION/RESUME where applicable.
- `route_resume_checkpoint`: exact C0–C8 or H1–H8 checkpoint when resuming; otherwise Not applicable.

| Action | Required behavior |
|---|---|
| INITIAL | Load the selected activity, check its prerequisites, and start only its missing initial work. Do not restart an already submitted activity; a conflicting existing outcome requires clarification. |
| RESUME | Reuse the available in-progress work/checkpoint, verify the resume point, and ask the next unresolved question. Elicit only essential missing evidence, not a full restart. |
| REVISION | Load the identified baseline and the matching directive from the selected activity's Revision Routing or another teacher-designated source. Reopen named checkpoints and affected dependencies only. Missing baseline, required scope, or directive means teacher clarification, not INITIAL. |
| WAIT | Briefly explain the recorded pending teacher decision. Do not launch another activity, manufacture approval, or generate a submission. |
| COMPLETE | Acknowledge the recorded completion and any teacher handoff. Do not start another activity or generate duplicate files merely because the student opened a chat. |

RESUME and REVISION remain modes of the selected activity, not additional activities. Pass INITIAL or REVISION to the activity's entry-mode contract; RESUME retains the original entry mode recorded in the available work and uses its checkpoint. WAIT/COMPLETE do not begin learning stages. Source verification and current teacher requirements still apply.

## 4. Written feedback and route conflicts

The route selects the activity/action; teacher feedback specifies the issue, authorized repair, restriction, or next decision. Use actual feedback naturally at the relevant stage, not a separate checklist for the learner. Optional blank comments are not an error. Nonbinding suggestions do not become required tasks.

For REVISION, the selected section's Revision Routing must identify the directive, baseline source/revision, checkpoints, required repairs, and authorized scope using `REVISION-DIRECTIVE-TEMPLATE.md` conventions. Prose feedback can explain those fields but cannot silently replace a missing baseline or conflicting approval. Do not invent a structured directive from ambiguous comments.

If the route says INITIAL but the teacher says to revise submitted work, or it selects Activity 2 without its own explicit drafting authorization and accepted concept revision, identify the conflict and contact the teacher. Do not choose a convenient instruction or ask the student to decide what the teacher meant. No approval is inferred from “good,” completion, `.phx` existence, or feedback alone.

When no route is present, only an unequivocally initialized record with no work or approval may default to Activity 1 INITIAL. Existing work with absent routing needs teacher clarification; do not guess which activity or portion to repeat. A student request cannot change the teacher-maintained route or locked decisions.

## 5. First response and session boundary

After required retrieval and prerequisite checks, briefly identify the selected activity/action. Ask language preference if not known; after a language answer, ask the actual next task question in the same response. If language is already known, ask that question immediately. Do not end with “I will follow your progress” or ask permission to proceed.

For example, a verified C4 revision should begin with the specific unresolved question issue, not new topic selection. Do not compose the student's answer while acknowledging the route.

One selected activity per conversation. A teacher route change to a different activity requires its own starter in a new chat. Do not silently switch tasks mid-session. Generating a draft progress update does not update the route or GitHub; only an actual teacher-saved record does that. Preserve revision history and keep personal identities and detailed private feedback out of public records.
