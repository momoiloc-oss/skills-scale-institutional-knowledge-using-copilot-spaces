# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The README provides a short summary of our approach and direct links to each doc for quick discovery.

## Summary of project management processes

OctoAcme runs a lightweight, repeatable delivery framework that moves work from idea to production through five stages: Initiation, Planning, Execution, Release, and Close/Retrospective. Initiation captures the problem, success metrics, stakeholders, and a high-level timeline in a Project One-pager. Planning turns approved initiatives into a prioritized backlog, estimates, a Definition of Done, and a release plan so the team can deliver in small, testable increments.

Execution is managed on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows a CI-first pull request workflow with small PRs and explicit acceptance criteria. Releases are classified (patch, minor, major) and gated by pre-release checks: passing CI and security scans, release notes, rollback plans, and smoke tests. The Release & Deployment guide and incident playbook define verification and rollback steps for production changes.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide inputs and approvals. Communication follows a regular cadence—daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates—paired with a simple, versioned Risk Register and tiered escalation paths.

Quality assurance is multi-layered: unit and integration tests, end-to-end smoke tests for critical flows, automated security scanning in CI, and manual QA as required. Retrospectives after sprints, releases, or incidents convert learnings into tracked action items that feed the backlog for continuous improvement.

## Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use

- Link this README from the repository root README or navigation for easier discovery.
- Keep links updated when documents are added, renamed, or moved.

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
