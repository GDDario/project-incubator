# Project Incubator Instructions

When the user provides a project, product, or business idea, treat it as an
incubation request. Use this repository to turn the idea into validated,
engineering-ready planning artifacts; do not begin implementation here.

## Required Workflow

Load and follow every project-local skill below with the `skill` tool. Run
them in this order, carrying the artifacts and decisions from each stage into
the next one:

1. `problem-framing-canvas`: establish the problem, users, context, and
   constraints.
2. `epic-hypothesis`: express the initiative as a testable hypothesis.
3. `opportunity-solution-tree`: identify opportunities, solution options, and
   tests.
4. `derisk-measurement-advisor`: identify the highest-risk assumptions and
   measurements that can reduce them.
5. `pol-probe`: design the cheapest credible Proof of Life experiment.
6. `discovery-process`: plan discovery interviews, synthesis, and experiments.
7. `prd-development`: create an engineering-ready PRD from the validated
   discovery output.
8. `roadmap-planning`: prioritize and sequence the initiative into releases.
9. `epic-breakdown-advisor`: split roadmap epics into safe, estimable slices.
10. `user-story-mapping`: map the end-to-end user journey and release slices.
11. `user-story`: write development-ready stories with Gherkin acceptance
    criteria for the selected first release.

## Collaboration Rules

- Begin with the idea the user supplied. Ask concise clarification questions
  only when information required by the current skill is missing or when a
  consequential decision has no defensible default.
- State assumptions explicitly and mark them for validation rather than
  inventing facts.
- Do not skip, substitute, or merely summarize a listed skill. Invoke each
  skill and follow its instructions before proceeding.
- Produce the artifact requested by each skill. Keep outputs linked: later
  artifacts must trace back to the problem, hypothesis, risks, and evidence.
- Present the complete incubation package in a clear sequence. Distinguish
  validated evidence, unvalidated assumptions, recommended experiments, and
  delivery commitments.
- Conclude by identifying the recommended next decision or experiment. This
  repository prepares work for an SDD implementation repository; it does not
  contain application implementation work.
