# OctoAcme Project Management Docs

This folder centralizes OctoAcme's project management processes, templates, and checklists to make it easy to discover, follow, and contribute to how we plan, deliver, and improve work.

## Brief overview of OctoAcme project management processes

OctoAcme follows a customer-first, iterative delivery model. Projects begin with a lightweight Project One‑pager to validate the problem, stakeholders, success metrics, and a go/no‑go decision. Approved initiatives move into planning where work is broken into prioritized backlog items with acceptance criteria, estimates, and a release/milestone map. Planning produces a clear Definition of Done and a test plan so that each increment is shippable and measurable.

During execution, teams follow a disciplined workflow (project board columns such as Backlog → Ready → In Progress → In Review → QA → Done), use timeboxed planning to respect team capacity, and prefer small pull requests with CI gates. Communication cadence includes daily standups to surface blockers, regular PM+PdM alignment, sprint demos/reviews, and weekly stakeholder updates as needed. Blockers escalate from team triage to PM to Product Lead and, if necessary, sponsor‑level escalation.

Quality and release practices are integrated into the pipeline: unit and integration tests, security scanning in CI, end‑to‑end smoke tests for critical flows, and manual QA where needed. Releases follow pre‑release checks (passing CI, release notes, rollback plan), staging smoke tests, automated deployment pipelines when possible, and post‑deploy verification. Retrospectives after sprints, releases, or incidents capture learnings as action items that are added to the backlog with owners and due dates to support continuous improvement.

## Quick links to process documents

- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

## How to use these docs

- Start with the Project One-pager and Project Management Overview to understand the lifecycle and roles.
- Use the Planning and Execution guides to create and manage backlog items, define the Definition of Done, and run sprint ceremonies.
- Follow Release & Deployment and Execution & Tracking checklists for pre-release checks, CI, smoke tests, and post-deploy verification.
- Maintain a Risk Register and use the Communication Templates for stakeholder updates and incident communication.
- After each sprint or release, run a retrospective and convert action items into backlog issues with owners and due dates.

## Contributing and updates

- To propose an addition or change, use the repository's process doc issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
- Keep changes small and link them to a real need (gap, improvement, or team feedback). Tag PM/PdM stakeholders for review as needed.

## Acceptance criteria

- [ ] Content aligns with existing process docs
- [ ] Improves discoverability and clarity of processes
- [ ] Reviewed by PM or Product Lead (if needed)

(See issue: https://github.com/patricktoohey/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)
