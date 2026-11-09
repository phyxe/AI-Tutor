# Student outcomes

Store one Markdown file per teacher-assigned student code, such as `S-7K2M.md`. Start from `OUTCOME-TEMPLATE.md`; append session entries to preserve previous evidence.

Use only minimal, teacher-reviewed, non-identifying summaries suitable for this public repository. Keep the identity mapping and sensitive student information elsewhere. Do not store names or full chat transcripts here.

Separate student reports, tutor observations, and teacher verification. ChatGPT drafts updates; the teacher reviews and saves them.

## Starting through one outcome URL

The student can use: “I am taking PR2 and you will help me by following my progress located in: [my teacher-issued outcome URL]”. Each record links to the general tutor, PR2 controller, and `../ROUTING.md`. The route selects the activity file; the tutor must actually retrieve all required text. This is a designed workflow, not a guarantee of linked-file retrieval in every ChatGPT access mode.

All 31 initialized records (17 `pr2_pru` and 14 `pr2_cou`) currently route to `pr2_act_01` with `route_action: INITIAL`. No student work or approval is implied.

Teacher updates:

- To resume unfinished work: set RESUME, identify the baseline/checkpoint, and make the actual in-progress evidence available through the teacher-designated source.
- To require a repair: set REVISION, identify the directive and baseline, and write the checkpoint-specific repair and authorized scope in the selected section's Revision Routing. Teacher's Comments can explain the issue.
- To advance to Chapter 1: save the accepted concept and explicit Chapter 1 drafting authorization in `# pr2_act_02`, then set `route_activity: pr2_act_02` and `route_action: INITIAL`.
- To wait for review or finish the assigned route: set WAIT or COMPLETE with an accurate explanation in the selected section.

Do not change only a comment while leaving a contradictory route. Do not use a generated submission as proof of teacher approval. Keep sensitive feedback and full baselines in appropriate teacher-designated storage rather than automatically publishing them here.

The linked raw GitHub paths work only once the corresponding reviewed files are published and accessible. Test one complete student-entry flow before rollout; current local edits are not automatically available at those URLs.


## Collected handoffs

After reviewing a collected handoff, use ../RESUME-PLAN-TEMPLATE.md to set the exact checkpoint/action, next prompt, matched file ID and teacher evidence dispositions. Set RESUME for unfinished work or REVISION for directed repairs. Put only the minimal plan in the selected public activity section and retain detailed work privately; the student can upload the exact teacher-identified handoff. Receipt does not mean completion or approval. Do not reset other learners or invent progress.
