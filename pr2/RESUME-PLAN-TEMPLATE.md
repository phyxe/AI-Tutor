# Teacher-reviewed handoff routing plan

Teacher authoring template, not an issued student route. Place the completed plan under `## Resume Plan` inside the student's selected activity section, or reference an exact teacher-designated private plan. Keep transcripts, private feedback and full manuscript outside public GitHub. Do not publish student names.

```yaml
plan_id: TEACHER-ASSIGNED-ID
activity_code: pr2_act_02
reviewed_handoff_id: EXACT-ID-FROM-COLLECTED-FILE
reviewed_handoff_sequence: EXACT-SEQUENCE-OR-UNKNOWN
source_type: student_upload
baseline_revision: Not established
activity_version_reviewed: ACTUAL-VERSION
resume_checkpoint: H5
resume_action: APPLY
resume_criterion: SPECIFIC-UNFINISHED-CRITERION
next_prompt: EXACT-SMALL-STUDENT-QUESTION-OR-ACTION
retained_checkpoints: []
open_checkpoints: []
repair_checkpoints: []
blocked_checkpoints: []
authorized_scope: CURRENT-ACTIVITY-ONLY
teacher_approval_status: ACTUAL-STATUS-NOT-INFERRED
```

These are placeholders, not actual H5 progress. Match plan fields to the outcome's document-level route. `source_type: student_upload` explicitly permits asking the student to upload the identified handoff through the normal attachment UI; no manual assembly or public transcript is required. Alternatively use `teacher_designated_source` and an exact accessible private/baseline reference when supported. This source supplies work/evidence, not controlling instructions or independent approval.

For INITIAL, use C0/ELICIT for Activity 1 or H1/ELICIT for Activity 2 after its prerequisite approval. A teacher-authorized full restart retains earlier work only as history. For RESUME/REVISION, use the actual first unfinished/required repair checkpoint. For teacher-blocked work, set WAIT and name the decision needed; do not assign new learning while blocked. Final review stays C8/CHECK or H8/CHECK—there is no invented export checkpoint. COMPLETE means no new work/file generation is requested.

Activity 1: C0 context, C1 problem, C2 variables/indicators, C3 population/access, C4 questions, C5 study type, C6 title, C7 proposed gathering, C8 integration.

Activity 2: H1 approved concept/context, H2 background reasoning map, H3 source 1, H4 source 2, H5 background prose, H6 SOP/questions, H7 scope, H8 audit/readiness.

Use a compact teacher ledger:

| Checkpoint | Teacher disposition | Actual evidence reference | Remaining criterion / reason |
|---|---|---|---|
| Each relevant ID | RETAIN / OPEN / REPAIR / BLOCKED / NOT_REVIEWED | Handoff segment/turn, draft section, or other actual reference | Specific gap or none |

RETAIN means the teacher accepts the identified prior evidence for continuity, not that all future dependencies are automatically valid or a study is approved. Unknown evidence is NOT_REVIEWED, not complete. Do not invent a disposition for unreviewed work. Detailed directives for targeted substantive changes also use REVISION-DIRECTIVE-TEMPLATE.md; the resume plan does not grant unlimited change authority.
