# AI Tutor workspace guide

Use `11-AI Tutor` as the single working folder. The former `10-CY-Researches` materials were consolidated here on November 26, 2026. The old folder contains only a relocation notice.

## Where files belong

| Location | Purpose | Git |
| --- | --- | --- |
| `GENERAL-TUTOR.md` | Shared tutor behavior, source retrieval, conduct and delivery | Included |
| `TUTOR-STATUS.md` | Current availability, holds and priority notices | Included |
| `MAINTENANCE-GUIDE.md`, `RECOVER.md` | Teacher maintenance and student continuity procedures | Included |
| `pr2/`, `effcom/` | Live area rules, activities, sources and coded outcomes | Included |
| `_learning-area-template/` | Scaffold for a future learning area | Included |
| `INSTRUCTION-STREAMLINE-REVIEW.md`, `pr2/*REVIEW.md`, `pr2/INSTRUCTION-AUDIT.md` | Editorial decisions and historical audits; read their current-policy notices | Included |
| `docs/CHANGELOG.md` | Dated workspace and behavior maintenance notes | Included |
| `_private/studentcodes.md` | Private student identity mapping | Ignored |
| `_private/pr2/submissions/Courage/`, `submissions/Prudence/` | Submissions organized by section, then student; includes earlier activities and clean copies | Ignored |
| `_private/pr2/submissions/Needs-review/` | Artifacts whose ownership/section is not established | Ignored |
| `_private/pr2/submissions/SUBMISSION-INDEX.csv` | Submission locations, dates, timestamp evidence and original paths | Ignored |
| `_private/pr2/records/Courage/`, `records/Prudence/` | Cohort review evidence, dated decisions, recovery plans and before-edit snapshots | Ignored |
| `_private/pr2/records/shared/` | Cross-cohort teacher directive snapshots | Ignored |
| `_private/pr2/reports/` | Submission summaries, dated monitors and reconstruction reports | Ignored |
| `_private/pr2/exports/capacities/` | Capacities exports and verification logs | Ignored |
| `_private/workspace-migration-2026-11-26/` | Old-to-new file map, SHA-256 hashes and consolidation verification | Ignored |

## Which instructions govern

Read current `TUTOR-STATUS.md`, `GENERAL-TUTOR.md`, the selected area/activity, and the student's exact official outcome. Current directives select authorized work. Dated reports, exported data, earlier directives and before-edit snapshots are evidence of earlier states; they do not replace the current controls or grant approval. Keep academic completion, teacher acceptance and fieldwork clearance distinct.

Ordinary PR2 activities retain their own finite targets and question budgets. Explicitly assigned assessment evidence recovery uses `pr2/ASSESSMENT-RECOVERY-PROTOCOL.md` within the existing activity: at most 10 main questions, 30 shared follow-ups and 40 total. Preserve actual earlier work, accepted decisions and scores. A newly authorized attempt has its own ID; returning to the same attempt retains its answers and counters. At the endpoint, compile the available complete or incomplete teacher record and give the submission step. Only the teacher decides reassessment or progression.

PHX is the teacher record; current PR2 production activities also call for a clean student DOCX from actual final output. Follow the runtime controls for fallback delivery. File creation is not submission or approval. Published Markdown guides model behavior but cannot guarantee it; editorial checks do not establish live student-chat behavior.

The November 25 status file currently says `ready`. November 26 outcome directives include newer improvement attempts. This guide is a dated orientation, not a second status source: reread the live files before acting.

## Daily maintenance

1. Place incoming submissions in `_private/pr2/submissions/<section>/<student>/`. Use `Needs-review/` for unestablished ownership. Preserve file contents and record the original filename. Follow the naming and timestamp rules in the submissions README; use `undated` when a submission date cannot be traced.
2. Keep detailed feedback, student explanations, transcripts, grades, exports and dated backups in `_private/`. Put only minimal teacher-reviewed coded directives in public outcomes.
3. Before changing an outcome, preserve its existing state in a dated cohort record folder. Preserve attempt boundaries and actual learner evidence.
4. Update the owning runtime file when behavior changes. Add a concise dated entry to `docs/CHANGELOG.md` with the reason and actual verification; link sensitive evidence through local private paths only when needed.
5. Check `git status --short` and `git diff` before committing. `_private/` must remain ignored; do not force-add private files. Local changes reach student chats only after publication.

## Finding relocated evidence

The migration's `file-map.csv` and `file-map.json` map every original path relative to `10-CY-Researches` to its new path relative to this workspace. Use `current_destination` for the latest location after submission organization; `destination` preserves the initial consolidation location. `_private/submission-organization-2026-11-26/` records the subsequent submission renames and timestamp evidence. Historical records retain their original bytes, including old absolute paths and snapshot references. Submission duplicates with identical SHA-256 hashes share one retained file; every original filename remains recorded in the map. Identical backups in separate audits remain in place to preserve audit context.

The identity mapping was previously tracked at the repository root. Its relocation removes it from the current working tree's public layout when the deletion is committed; prior Git history is unaffected. This consolidation does not rewrite history or publish changes.
