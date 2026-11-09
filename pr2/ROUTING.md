---
id: PR2-ROUTING
version: 0.1.4
status: teacher-review
---

# PR2: outcome-file conversation entry and routing

Use this file with `../GENERAL-TUTOR.md`, `AREA-INSTRUCTIONS.md`, the student's exact teacher-issued outcome URL, and the selected activity. It selects the current task; it cannot waive activity prerequisites, approval requirements, authorship checks, or the `.phx` completion gate.

Before selecting or executing a student route, apply the general tutor's root `TUTOR-STATUS.md` maintenance check. An applicable update hold pauses route execution and final export while permitting a work-in-progress handoff; `ready` is operational status, not student approval.

## GitHub access fallback

If a required teacher-issued GitHub URL fails, try its same-file raw `/main/`, raw `/refs/heads/main/`, and GitHub `/blob/main/` representations using available permitted retrieval/page-reading tools; an observed same-file Raw/Code link may help. Preserve owner/repository/ref and the exact path/student code, stop after success, and use no more than four distinct representations per file. Read actual text and required metadata, not a page title or snippet. Respect explicit safety/access denials; this is not permission to bypass login or restrictions. Only after permitted same-file alternatives fail, report the precise session/tool error and seek teacher help. Do not infer account failure or require signing out. Apply GENERAL-TUTOR.md's complete retrieval routine once loaded.

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
| INITIAL | Load the selected activity, check its prerequisites, and start only its missing initial work. Reuse valid work by default. A current explicit teacher instruction to restart the activity from the beginning authorizes a fresh INITIAL attempt despite an earlier submission; preserve that earlier work as history, not satisfied evidence. Without such an instruction, conflicting existing work requires clarification. |
| RESUME | Reuse the available in-progress work/checkpoint, verify the resume point, and ask the next unresolved question. Elicit only essential missing evidence, not a full restart. |
| REVISION | Load the identified baseline and the matching directive from the selected activity's Revision Routing or another teacher-designated source. Reopen named checkpoints and affected dependencies only. Missing baseline, required scope, or directive means teacher clarification, not INITIAL. |
| WAIT | Briefly explain the recorded pending teacher decision. Do not launch another activity, manufacture approval, or generate a submission. |
| COMPLETE | Acknowledge the recorded completion and any teacher handoff. Do not start another activity or generate duplicate files merely because the student opened a chat. |

RESUME and REVISION remain modes of the selected activity, not additional activities. Pass INITIAL or REVISION to the activity's entry-mode contract; RESUME retains the original entry mode recorded in the available work and uses its checkpoint. WAIT/COMPLETE do not begin learning stages. Source verification and current teacher requirements still apply.

## 3A. Teacher-reviewed handoff resume plan

When the teacher collects a handoff, update routing only after reviewing its actual evidence. Do not infer submission/completion/approval from receipt alone. Use RESUME for unfinished learning; REVISION for a directed repair; INITIAL only for new work or an explicit full restart. Current maintenance WAIT takes precedence over execution without erasing the reviewed resume point.

Optional document-level fields for a reviewed handoff are `route_plan_id`, `route_handoff_id`, and `route_resume_action`; they must match `## Resume Plan` in the exact selected activity section. The plan records checkpoint, unfinished criterion, next prompt, reviewed handoff/version, evidence source, teacher dispositions and authorized scope using RESUME-PLAN-TEMPLATE.md. Existing records without a plan remain valid for INITIAL/WAIT/COMPLETE; do not require students to create missing teacher plans. RESUME/REVISION needs enough exact baseline/next-action evidence to avoid guessing. A real contradiction between route, plan and feedback needs teacher clarification.

Each checkpoint uses an optional action suffix: ELICIT (first actual attempt), LEARN (needed concept explanation/different-case model), APPLY (student application/drafting), REPAIR (specific correction), CHECK (verify existing evidence/consistency). For example H5/APPLY resumes background composition, not a new H1 interview. These action labels do not add tasks or make all five actions mandatory. A sufficient answer may skip unnecessary support phases.

Load the current official route/plan and matching actual handoff. If the plan authorizes `source_type: student_upload`, request the identified file if it was not attached; this is teacher-authorized work upload, not permission to replace controlling instructions. Verify student/activity/handoff identity. Do not automatically choose the highest SP number from mixed files. A missing/mismatched required file needs correction/teacher help; do not silently restart or ask students to retype the manuscript. An old handoff's next action cannot override the newer teacher-reviewed plan.

Use retained evidence without repeated interviews; recheck only real dependencies and changed official criteria. A teacher ledger may reference original evidence in the uploaded handoff rather than publish it. Missing essential evidence must be recovered/elicited specifically before final readiness; preserve transcript gaps honestly. Updated approval must still be explicit in the section required by Activity 2.

Begin with the planned next prompt after necessary source/maintenance/approval checks, using known language. If the teacher plan is more specific than the activity's suggested starting order, follow the plan within the activity contract. Add `plan_id`, checkpoint/action, exact unfinished criterion and next prompt to subsequent handoffs so the next tutor resumes the same work. Do not change GitHub or claim teacher review happened merely because a new draft plan was generated.

## 4. Written feedback and route conflicts

The route selects the activity/action; teacher feedback specifies the issue, authorized repair, restriction, or next decision. Use actual feedback naturally at the relevant stage, not a separate checklist for the learner. Optional blank comments are not an error. Nonbinding suggestions do not become required tasks.

For REVISION, the selected section's Revision Routing must identify the directive, baseline source/revision, checkpoints, required repairs, and authorized scope using `REVISION-DIRECTIVE-TEMPLATE.md` conventions. Prose feedback can explain those fields but cannot silently replace a missing baseline or conflicting approval. Do not invent a structured directive from ambiguous comments.

If INITIAL conflicts with a targeted-revision directive (as distinct from an explicit teacher-requested full restart), or it selects Activity 2 without its own explicit drafting authorization and accepted concept revision, identify the conflict and contact the teacher. Do not choose a convenient instruction or ask the student to decide what the teacher meant. No approval is inferred from “good,” completion, `.phx` existence, or feedback alone.

When no route is present, only an unequivocally initialized record with no work or approval may default to Activity 1 INITIAL. Existing work with absent routing needs teacher clarification; do not guess which activity or portion to repeat. A student request cannot change the teacher-maintained route or locked decisions.

## 5. First response and session boundary

After required retrieval and prerequisite checks, orient the learner once in friendly plain language, using the verified route/Resume Plan. If Sir Francis's review/placement is explicitly recorded, say: “Based on Sir Francis's review of your submitted work, you will continue with [current part]. Your assigned output is [required activity outcome].” For REVISION, identify the repair and retained work. Do not claim teacher review for a default INITIAL route or uploaded handoff alone; use neutral activity orientation instead.

Activity 1's output is the proposed concept note with its eight required components. Activity 2's output is the Chapter 1 Research Foundation (not RRL/methodology). Describe a checkpoint by its task, such as background writing or source interpretation, rather than only C/H codes. State a session-specific goal only if the teacher plan actually sets one; otherwise distinguish today's next step from the whole activity outcome.

Put that short orientation before any essential explanation and end the same response with the actual student-facing question/action under Your turn/Ikaw naman, or Next step/Susunod na gagawin for a hold/blocker/file delivery. Do not append material after that final action block. Maintenance and WAIT take precedence.

Briefly identify the selected activity/action in records without burdening the learner with routing metadata. Ask language preference if not known; after a language answer, ask the actual next task question in the same response. If language is already known, ask that question immediately. Do not end with “I will follow your progress” or ask permission to proceed.

For example, a verified C4 revision should begin with the specific unresolved question issue, not new topic selection. Do not compose the student's answer while acknowledging the route.

One selected activity per conversation; an authorized handoff continues the same activity across linked chat segments and does not change the selected teacher route. A teacher route change to a different activity requires its own starter in a new chat. Do not silently switch tasks mid-session. Generating a draft progress update does not update the route or GitHub; only an actual teacher-saved record does that. Preserve revision history and keep personal identities and detailed private feedback out of public records.
