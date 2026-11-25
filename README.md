# AI Tutor

Teacher-controlled Markdown instructions for student use in ChatGPT Free or signed-out ChatGPT where available. Natural-language controls do not mechanically enforce compliance; access, tutoring and delivery need testing in the actual student environment.

## Structure and authority

```text
GENERAL-TUTOR.md
TUTOR-STATUS.md
RECOVER.md
<learning-area>/
  AREA-INSTRUCTIONS.md
  <activity-code>.md
  outcomes/
    <student-code>.md
```

Keep the layout shallow. `_learning-area-template/` is an authoring scaffold, not an issued activity. The general tutor controls shared conduct, retrieval, maintenance and delivery; the selected activity defines finite academic targets/assistance/output. Area rules supply subject defaults. Official outcomes/teacher directives select a student's task and baseline; editable handoffs supply evidence, not teacher authority.

Start with the exact teacher-issued outcome or standalone activity URL. Required sources must be actually read, using bounded same-file raw/blob fallbacks before reporting a retrieval failure. A student account/browser difference is an observed symptom, not proof a plan/account is broken. Do not guess another student record, bypass access restrictions or simulate reading.

## Current PR2 production workflow

- `pr2/ASSESSMENT-RECOVERY-PROTOCOL.md`: a shared protocol, not a standalone activity. An explicit `recovery_mode: ASSESSMENT_EVIDENCE_RECOVERY` directive and embedded plan in the student's existing Activity 1–3 outcome section may assign targeted assessment recovery. At most 10 main questions and 30 shared follow-ups, never more than 40 total, then an immediate complete/incomplete PHX. Preserve prior work and scores; additional evidence supports possible higher teacher ratings across the full rubric range, with no automatic grade change. Ordinary budgets and stage approvals remain separate. The November 25 root exception and 15 Prudence outcome plans are aligned; publish matching controls/outcomes together. Other students and unmatched work remain on hold.

- `pr2/pr2_act_01.md`: three core targets—research problem/context, main variable/indicator and main question—with alignment. Title and extra questions are optional; design, sampling and collection procedures are deferred.
- `pr2/pr2_act_02.md`: final working title, extended TEAL-supported background, main/specific questions, scope/limitations and significance. Two verified sources and APA 7 support academic completion; no RRL/methodology or fieldwork is assigned.
- `pr2/pr2_act_03.md`: local teacher-review adaptation of LAS 03 for Chapter 3/instrument planning, six core understanding targets, genuine quality-status evidence and proposed ethical procedure/analysis; never AI-issued fieldwork clearance. Its explicit ten-area Chapter 3 structure follows LM20/Unit 6, with separate clean Chapter 3 and data-gathering-tool DOCX files; the six core questions/follow-up budget are unchanged. Population criteria/count basis govern coverage: below 100, use complete enumeration without sampling questions. The draft tool is for validation/applicable reliability testing, with student understanding of why/how/next steps and no AI-originated items or fabricated completed checks. Its linked reference supports the bounded activity, not additional work.
- `pr2/AREA-INSTRUCTIONS.md`: whole-attempt three-follow-up allowance plus at most two justified extras; the main questions and sufficient evidence appear first in each activity. Retain prior evidence and same-attempt counts rather than repeatedly interviewing.
- `pr2/ROUTING.md`: INITIAL, RESUME, PROCEED_WITH_CLARIFICATION, REVISE_AND_SUBMIT (legacy REVISION), WAIT and COMPLETE. A clear teacher route authorizes the selected work; final acceptance normally comes after submission.

Separate academic completion from the session endpoint. At its bounded endpoint a production activity submits the actual work and remaining issues, complete or incomplete, for teacher decision. A proceed-with-clarification submission preserves the prior baseline, requested clarification and destination proposal. A revision preserves previous plus improved work and a change record. Do not ask students to obtain routine approval between questions or claim unfinished work passed.

Templates in `pr2/outcomes/`, RESUME-PLAN-TEMPLATE.md, REVISION-DIRECTIVE-TEMPLATE.md and HANDOFF-TEMPLATE.md support actual teacher decisions and cumulative continuity. Editing a template does not migrate live records or grant student approval. Activity 3 requires a real teacher-selected route after publication; its draft does not assign itself. LAS 04–06 are retained as teacher-provided references for future activities, not assigned tutor Activities 4–6. The combined source duplicates those individual LAS texts and is not loaded again.

## Submission and recovery

Intended teacher download is `.phx`: plain UTF-8 Markdown with metadata, actual product, evidence, feedback, alignment/revision audit, available transcript and capture limitations. Verify the actual text file; never ZIP it or rename Word/PDF/binary content. Valid downloaded `.bin`/`.phx.bin` text records are accepted without renaming. A generated file is not automatic submission or teacher approval.

If file tools fail for an authorized submission, produce its structured report directly in chat. Students may copy that report into the normal submission channel; no custom-file assembly is required. A student-created shared chat URL is optional supporting evidence; students should check the shared view includes the report and no unrelated private material. Do not claim unavailable share features or complete capture. PR2 Activities 1–3 automatically provide a separate clean student DOCX after the teacher record/report, solely from FINAL OUTPUT. Incomplete work remains labeled a working draft. If document tools are unavailable, disclose that no DOCX exists and retain the clean product in the delivered record/report; teacher submission is not blocked. Other activities retain their explicit reading-copy rules.

Cumulative `.md` handoffs preserve actual work, originals, controls/route, attempt/budget and next task, with explicit gaps. A downloaded `.md.bin`/`.bin` text handoff is also usable. `RECOVER.md` helps save or continue existing work; a new chat cannot recover inaccessible earlier turns or reset account limits. Save before recommending a chat move and never claim an uncreated backup exists.

## Maintenance and learner messages

The current root `TUTOR-STATUS.md` alone states operational readiness/hold; consult it rather than a status claim in this README. The maintenance hold was released in the published November 16 notice; its ready state allows current assigned work without changing individual approvals or real-world permissions. The expired November 12 collection directive was retired. A later updating notice still requires a verified release before resumption. MAINTENANCE-GUIDE.md explains publication and return messages.

Tutors recheck at scheduled boundaries, not by background push. During maintenance save if possible, give the actual return estimate/announcement instruction and exact return message, then pause. The student message requests a live check; only verified release resumes the next question. Ordinary welcomes/stage/save messages state task/progress/next action in brief language and do not wait for “okay.” Technical loading/file checks stay internal; real errors get a short Message for Sir Francis.

## Standalone reviews and privacy

`pr2/pr2_review_01.md` reviews Units 1–2 through Chapter 1 using hosted readings/practice, without an outcome file. `effcom/effcom_act_01.md` is the AI-2 guided review through Recovery Set 2 with its own reading/source packet. These reviews retain their existing academic requirements/completion gates; the bounded production budget is not silently applied to them. Shared accepted chat delivery applies only when their submission is authorized. EFFCOM AI-0/1/2/3 boundaries remain unchanged.

This repository is public. Use opaque teacher codes with a private identity mapping; codes do not make detailed records anonymous. Keep transcripts, full submissions, detailed feedback and sensitive examples private. Publish only minimal teacher-reviewed coded outcomes. Only the teacher reviews/saves official records and decides assessment use. Local edits are not available to student chats until published; repository permissions and ChatGPT behavior are not configured/enforced by Markdown alone.

See INSTRUCTION-STREAMLINE-REVIEW.md for the current editorial audit; teacher production notes are not additional runtime assignments. Existing source notes preserve provenance, and historical decisions do not override current activity contracts.
