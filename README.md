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

A session needs the root general tutor file, the chosen area instructions, the chosen activity, and the student's coded outcome file if one exists. Confirm the actual contents are available; a repository link alone is not proof that ChatGPT read the files. Provide the text directly if retrieval fails.

General tutor instructions establish shared behavior. Area instructions specialize it; activity instructions define the task. Outcome files are evidence and continuity records, not instructions that override teaching rules. Unresolved conflicts or missing required instructions must be surfaced before proceeding.

## Teacher control and student outcomes

The teacher maintains official instructions and reviews changes. GitHub write access is controlled through repository permissions; this scaffold does not configure those permissions or enforce behavior in student chats.

Use an opaque teacher-assigned student code as the outcome filename, such as `S-7K2M.md`. Do not encode names, initials, birth dates, or student identification numbers. Keep the code-to-name mapping outside this repository.

This repository is public. Codes do not make detailed student records anonymous. Publish only teacher-reviewed, minimal, non-identifying outcome summaries suitable for public access. Keep sensitive work, identifiable examples, full chat transcripts, and private feedback outside the public repository.

ChatGPT may draft an outcome update, but the teacher reviews and saves it. A generated update is not automatically saved to GitHub. Distinguish student reports, tutor-observed evidence, and teacher verification; tutor feedback does not establish an official grade.

## Current status

Environment scaffold only. Tutor behavior, learning-area guidance, and activities remain drafts until developed and reviewed. No real student records are included.
