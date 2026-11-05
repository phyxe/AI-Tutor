# Practical Research 2: AI-Guided Activities

Shared instructions: [`pr2-ai-standards.md`](pr2-ai-standards.md) (v0.9-draft)

## Activities

- [`activities/pr2-ai-a01-research-declaration.md`](activities/pr2-ai-a01-research-declaration.md) (v1.8-draft; `pr_act_01`, individual preliminary research declaration)
- [`activities/pr2-ai-a02-chapter-1.md`](activities/pr2-ai-a02-chapter-1.md) (v1.2-draft; `pr_act_02`, individual Chapter 1 from a teacher-approved concept)

## Activity 01 student starter prompt

> Read and follow these two PR2 instruction files completely: https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/pr2-ai-standards.md and https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/activities/pr2-ai-a01-research-declaration.md.
>
> If either file is inaccessible or cannot be read completely, stop and instruct me to contact my teacher. If my teacher has assigned a code, it is [STUDENT CODE]; otherwise do not invent one.

The historical November 4, 2026 deadline, interaction rules, ten approximate checkpoints, and final submission requirements are contained in the two instruction files, not in the starter prompt. The AI still assists after the deadline, without granting an extension or deciding whether late work is accepted. The preliminary declaration may be compiled after the learning-completion gate passes even when its teacher-review label is **Revise While Moving** for a nonblocking teacher decision. This does not grant approval to collect data.

**Start-of-activity test:** After a student replies `English` to the language-choice question, the AI must ask `What concern or research idea would you like to investigate?` in the **very next response**. An acknowledgment or "Let's begin" message alone is not sufficient.

When testing in ChatGPT Free, verify that the full file content was read instead of inferring access from a filename, a preview, or a search snippet. GitHub hosting does not guarantee every ChatGPT retrieval attempt will succeed.

## Final file delivery for both activities

Each completed activity produces two intended downloads **in this order**:

1. **Teacher submission:** `[student_code]_[activity_code].pr2`, an ordinary UTF-8 text file readable in Notepad++ and organized with YAML metadata, the exact `# MANUSCRIPT` section, original student responses, AI feedback, alignment/revision audit, available conversation transcript, and integrity/capture status. Activity 01 uses `pr_act_01_unassigned.pr2` if no code was issued.
2. **Student copy:** `[student_code]_[activity_code].docx`, a formatted Word document **derived only from `# MANUSCRIPT` in the completed `.pr2` record**. Do not include teacher-only evidence or transcript in Word.

The student **downloads both** when successful, **keeps the Word file**, and **manually submits the `.pr2` text record to the teacher**. No ZIP, PDF, automatic email, or background upload. If Word creation fails, the `.pr2` must still be supplied. If the custom file extension is blocked, the identical teacher-record content may be saved as `.md`; if no file tools work, display its **entire text** to copy into a UTF-8 editor. Never invent download links or transcript turns.

## Student codes and approved-outcome record

Each student has one persistent Markdown file at `pr2/approved/[student_code].md`; e.g. `pr2/approved/pr2_pru_01.md`. The teacher assigns and manages the middle segment of the student code. **Do not publish names, sections, marks, personal records, or a code-to-identity roster.**

Within that file, each activity's approved entry begins with one exact Markdown Level 1 heading, e.g. `# pr_act_02 | Approved Input from pr_act_01`; subsequent field headings use `##`. The entry ends at the next Level 1 heading or file end. Later approved outcomes may be appended as `# pr_act_03`, etc. The required entry needs its own **Approval status: Approved for Chapter 1 drafting** and actual approved title, problem, questions, variables, design, boundaries, and teacher conditions. Approval of one section is not approval of every section.

See [the sample record](approved/pr2_pru_00.md), which is deliberately **SAMPLE ONLY** and cannot launch a real student activity.

## Activity 02 student starter prompt (three URLs)

The teacher must create the individual approved-outcome record before giving a student the third URL. Replace the illustrative third URL with the exact URL for that student's file.

> Hi ChatGPT. Please read these three files in full and begin `pr_act_02`:
>
> 1. https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/pr2-ai-standards.md
> 2. https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/activities/pr2-ai-a02-chapter-1.md
> 3. https://raw.githubusercontent.com/phyxe/AI-Tutor/main/pr2/approved/pr2_pru_01.md
>
> Use the student code from the third URL, match it against the file's `student_code`, and read only the approved `# pr_act_02` section. If any file is unreadable, that section is missing or unapproved, or the codes disagree, stop and direct me to my teacher.

Student names and sections are not required in the ChatGPT starter prompt. The teacher keeps the real mapping separately. The sample `pr2_pru_00` must never be used as a real approved record.

The activity controls two-source verification and comprehension, LM05–LM07 Chapter 1 work, original individual student responses, tutor feedback, and the UTF-8 `.pr2` teacher record plus derived `.docx` student copy. It records the **approximate activity start** and **the READY-for-compilation end time** when verifiable; wall-clock duration is not active learning time.

**Deployment test:** Check that all three URLs truly load in ChatGPT Free, the file's student code matches its URL, and the tutor selects exactly one current `# pr_act_02` section. After the language choice, the next reply must ask an actionable question about the approved research context, using clear Grade 10-accessible conversational wording. The public demonstration file is intentionally unapproved and should cause a stop.
