# AI Tutor

Teacher-controlled Markdown instructions for student tutoring through ChatGPT Free or signed-out ChatGPT where available. Access and file-loading behavior still require testing before classroom use.

## Structure

```text
GENERAL-TUTOR.md
<learning-area>/
  AREA-INSTRUCTIONS.md
  ACTIVITY-001.md
  outcomes/
    <student-code>.md
```

Each learning area has its own folder directly at the repository root. Area instructions and activity files sit directly inside it; only student outcomes use a subfolder. Add activities as `ACTIVITY-002.md`, `ACTIVITY-003.md`, and so on.

`_learning-area-template/` is a reusable scaffold, not an active learning area. Copy it to a short descriptive folder name when adding an area. Its outcome template is not a student record.

## Session inputs

For an unreachable public GitHub file, tutor entry points now instruct bounded same-file raw/blob/page-reading alternatives before escalation. The exact repository, ref, and path must be preserved; snippets, guessed contents, adjacent student records, and access-control bypasses are prohibited. See `GENERAL-TUTOR.md` for the shared routine. A logged-in/logged-out difference is an unresolved session symptom, not proof that an account is faulty or that signing out fixes limits.

Students may start with their exact teacher-issued outcome URL. Each PR2 outcome links to the controlling files; `pr2/ROUTING.md` interprets the teacher-maintained route and selects one activity. The route and scoped written feedback support initial work, resumption, or targeted revision. Linked-file access still requires testing, and local files must be published before their raw GitHub URLs are usable.

A session needs the root general tutor file, the chosen area instructions, the chosen activity, and any outcome record explicitly required by the activity. Confirm the actual contents are available; a repository link alone is not proof that ChatGPT read the files. A teacher-provided starter may explicitly authorize pasted/offline copies. Otherwise, a required-source failure means contacting the teacher rather than improvising replacement instructions.

General tutor instructions establish shared behavior. Area instructions specialize it; activity instructions define the task. Outcome files are evidence and continuity records, not instructions that override teaching rules. Unresolved conflicts or missing required instructions must be surfaced before proceeding.

## Teacher control and student outcomes

The teacher maintains official instructions and reviews changes. GitHub write access is controlled through repository permissions; this scaffold does not configure those permissions or enforce behavior in student chats.

Use an opaque teacher-assigned student code as the outcome filename, such as `S-7K2M.md`. Do not encode names, initials, birth dates, or student identification numbers. Keep the code-to-name mapping outside this repository.

This repository is public. Codes do not make detailed student records anonymous. Publish only teacher-reviewed, minimal, non-identifying outcome summaries suitable for public access. Keep sensitive work, identifiable examples, full chat transcripts, and private feedback outside the public repository.

ChatGPT may draft an outcome update, but the teacher reviews and saves it. A generated update is not automatically saved to GitHub. Distinguish student reports, tutor-observed evidence, and teacher verification; tutor feedback does not establish an official grade.

## Current status

The assigned activity is the controlling academic contract. Shared/area guidance cannot add tasks or remove requirements. Tutors must check both no-overreach and no-undercoverage, maintain criterion-to-evidence coverage, and stop at the activity endpoint. Adaptation and evidence reuse remain permitted when every original criterion is genuinely met; shortages and tool failures require honest save/help handling, not a reduced assignment.

PR2 Activity 2 includes a Chapter 1-only scope contract: background source support cannot become RRL, and brief planned-data checks cannot become methodology. Handoff/resume and each proposed task must stay within H1–H8; off-scope detours are preserved as evidence, then redirected without restarting valid work.

The root `TUTOR-STATUS.md` is the teacher-controlled operational notice. It is currently `ready` (no hold). Set it to `updating`, choose all or selected activities, and provide an Asia/Manila expected resume timestamp to trigger save-and-pause behavior when tutors next check it. `MAINTENANCE-GUIDE.md` explains publication, interim handoff collection, and clearing the hold. Existing chats cannot receive an automatic GitHub push; the expected time alone never clears maintenance.

PR2 Activity 2 now supports cumulative downloadable `.md` handoffs at planned checkpoints and when stuck. Teachers may collect these for interim support. Students resume by uploading the latest verified handoff; they are not required to assemble files manually. Final `.phx` remains completion-gated, Word is optional, and starting a new chat is not treated as a usage-limit reset. See `pr2/HANDOFF-TEMPLATE.md` for the authoring schema.

`effcom/AREA-INSTRUCTIONS.md` is the Effective Communication learning-area draft, grounded in the Grade 11 Term 2 package. It specializes communication/source/data checks and preserves task-specific AI permission boundaries. `effcom/effcom_act_01.md` now provides an AI-2 developmental review through Recovery Set 2, with a reading guide and classroom source packet. No EFFCOM student routes are assigned yet; source and review notes are in `effcom/SOURCE-NOTES.md`.

`pr2/AREA-INSTRUCTIONS.md` contains a teacher-review PR2 controller with response routing and separate progression/submission gates. `pr2/pr2_act_01.md` is the draft concept-note activity, with initial development and targeted revision modes. `pr2/REVISION-DIRECTIVE-TEMPLATE.md` supports teacher-directed revision without restarting the whole activity. Curriculum sources, adaptations, and review scenarios are recorded in `pr2/SOURCE-NOTES.md`. `pr2/pr2_act_02.md` is the draft individual Chapter 1 activity with two verified sources, gated by teacher concept approval. No Activity 3 is assigned.

The general tutor is a teacher-review draft adapted from the teacher's working PR2 standards. Learning-area guidance and activities remain templates. No real student records are included. Actual Free/signed-out access and file creation remain to be tested.

## Submission format

Only after verifying every mandatory completion criterion for the assigned activity, the tutor creates the authoritative submission record first, using only the `.phx` extension. Its contents are plain UTF-8 Markdown, readable in a text editor; the extension does not require proprietary software. It contains the final output, learning evidence, feedback, revision audit, available transcript, and capture limitations. The student submits this custom file manually to the teacher, not the Word/PDF reading copy.

Any activity-required Word/PDF copy is derived afterward from the custom record's `# FINAL OUTPUT` section alone. If `.phx` generation is unavailable, the tutor may provide the complete record as copyable Markdown only after the same completion gate passes, for manual saving as UTF-8 with a `.phx` filename. The teacher accepts valid `.bin`/`.phx.bin` download names under the general tutor's filename exception. Premature partial submissions remain prohibited. Detailed submission records are not public GitHub outcome files.

## Standalone PR2 review

`pr2/pr2_review_01.md` reviews Units 1–2 through Chapter 1 writing using hosted copies of the package reference chapters and a separate practice file. It needs no outcome file and produces a completed `.phx` for private teacher submission after its learning gate passes. It does not change production-activity routes or approvals. Current new review files remain teacher-review drafts until tested.

## Android/download filename compatibility

The intended output is `.phx`, but the teacher also accepts `.bin` and `.phx.bin` downloads containing the same complete UTF-8 Markdown record. Students do not need to rename or repeat valid work. The completion gate and required evidence/sections remain unchanged; ZIP and other binary contents are invalid regardless of extension.

## Instruction audit

See `pr2/INSTRUCTION-AUDIT.md` for the 9 November 2026 consistency/streamlining audit, preserved requirements, measured word counts, structural checks and remaining live-test scenarios. The audit is teacher production documentation, not an extra file students must retrieve.
