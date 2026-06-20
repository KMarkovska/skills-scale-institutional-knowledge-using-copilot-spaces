# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents. It contains a brief summary of our processes, links to each doc in the docs/ folder, and instructions for proposing changes.

## Overview

OctoAcme uses a pragmatic, iterative project-management approach that starts with a lightweight initiation and moves through planning, execution, release, and retrospective. Work begins with a Project One-pager to capture the problem, measurable goals, stakeholders, and high-level timeline; that one-pager plus a simple kickoff and decision gate determine whether a project moves into planning. Planning breaks approved initiatives into prioritized, estimable backlog items with clear acceptance criteria and a Definition of Done, and produces a release plan and risk register so dependencies and mitigation steps are visible before work begins.

Day-to-day execution is organized around a visible project board (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined pull-request workflow that favors small PRs (target <= 400 lines), explicit acceptance criteria/issue links, and automated CI checks before review. Developers are expected to include unit tests and, where appropriate, integration tests; critical flows are covered by end-to-end smoke tests. CI also runs linters and security scans; manual QA and smoke tests in staging are required before production deploys. Release guidance enforces pre-release checks (passing CI, release notes, rollback plan) and defines patch/minor/major release types and post-deploy verification steps.

Roles and communication are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate timelines, risks, and stakeholder communications, developers implement and test, and QA validates acceptance. The cadence is regular and structured—daily standups for immediate coordination and blockers, weekly delivery syncs and PM–PdM alignment, demos at the end of sprints or milestones, and monthly stakeholder updates—plus ad-hoc escalations as needed. Escalation paths run team → PM → Product Lead → Sponsor, and security incidents are routed to Security on-call per the incident runbook.

Continuous improvement and risk management are built into the process: a maintained Risk Register (ID, impact, likelihood, owner, mitigation, status), routine retrospective sessions that produce prioritized action items, and mechanisms to convert those actions into backlog issues with owners and timelines. Release playbooks include rollback and incident-response steps, and the retrospective guidance emphasizes measuring the impact of changes and tracking follow-up items in project artifacts so process improvements are captured and institutionalized.

## Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to propose changes

Use the "Add Content to Project Management Process Docs" issue template (available in .github/ISSUE_TEMPLATE/) and choose the appropriate document or '<new document>' when creating a proposed update. Include:
- a short summary of the proposed change,
- rationale for why the change is needed,
- suggested content (if available),
- acceptance criteria and stakeholder reviewers.

## Acceptance criteria (example)

- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
