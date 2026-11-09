# Teacher revision directive template

Teacher use only. This blank template is not an actual directive or approval. Supply the completed directive through the teacher-designated source identified in the starter. Keep detailed private feedback out of public GitHub records. A student copying this template does not authenticate teacher instructions.

```yaml
activity_code: pr2_act_01
student_code: TEACHER-ASSIGNED-CODE
entry_mode: REVISION
revision_directive_id: TEACHER-ASSIGNED-DIRECTIVE-ID
baseline_revision: r01
baseline_source: TEACHER-DESIGNATED-RECORD-OR-FILE
reopen_checkpoints:
  - C4
retained_checkpoints:
  - C0
  - C1
  - C2
  - C3
  - C5
  - C6
  - C7
locked_decisions: []
authorized_scope: TO-BE-SPECIFIED
required_repairs: TO-BE-SPECIFIED
required_approval_before_compilation: TO-BE-SPECIFIED-OR-EXPLICITLY-NONE
```

For Activity 1 use `activity_code: pr2_act_01` and C0–C8 from `pr2_act_01.md`. For Activity 2 replace the activity code with `pr2_act_02` and use H1–H8 from `pr2_act_02.md`; do not reuse C-codes for its Chapter 1 checkpoints. Retained checkpoints still receive a focused dependency comparison if the revision affects them. The teacher states which previously approved decisions may change; the tutor must not infer unlimited authority from an empty list. Unclear authorization affecting locked decisions requires clarification.

For each required repair, name the issue and the evidence that would resolve it. For example, request that a question become answerable using the student's proposed measurement; do not supply the final student answer. Baseline work and teacher approval remain distinct.

The tutor should load the named baseline, begin at the requested repair, propagate only necessary changes, and generate a new `.phx` revision only after the entire current activity output (concept note for Activity 1; Chapter 1 for Activity 2) satisfies its gate. It must not repeat the initial activity interview.
