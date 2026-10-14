# OctoAcme Project Management Process Docs

This README centralizes the OctoAcme project management process documentation to make it easier for team members and new contributors to discover and follow our established workflows. The docs in this folder capture the lifecycle from initiation through planning, execution, release, and continuous improvement — including the roles, checklists, and communication patterns teams should use while delivering work.

OctoAcme follows a lightweight, iterative delivery model with clear ownership and measurable outcomes. Projects start with a concise Project One-pager to capture the problem, SMART objectives, success metrics, stakeholders, and a high-level timeline. Planning translates the approved initiative into a prioritized, estimated backlog with explicit acceptance criteria and a Definition of Done. During execution, teams use a project board to move work across Backlog → Ready → In Progress → In Review → QA → Done, prefer small PRs with CI and at least one approval, and maintain a regular cadence of standups, weekly delivery syncs, and demos.

Roles and personas are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedule work, manage risks, and communicate with stakeholders; Developers build and test features; QA validates acceptance criteria and runs manual/automated tests as needed; Stakeholders provide input and approvals. The docs include a risk register and escalation paths for blockers to ensure issues are surfaced and resolved quickly.

Quality and release safety are enforced through CI pipelines, automated tests (unit, integration), smoke tests for critical flows, and security scanning. Pre-release checklists require passing CI, completed acceptance criteria, release notes, rollback plans, and staging verification before production deploys. Post-release and incident learnings are captured in retrospectives with actionable items tracked back into the project backlog.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use

- Read the overview to get oriented on lifecycle and core artifacts.
- Use the Project Initiation and Planning guides to create the one-pager, capture stakeholders, and build the backlog.
- Follow the Execution & Tracking document for day-to-day conventions (board columns, PR expectations, CI requirements).
- Update the Risk Register and use the communication templates in Risk Management when escalating.
- Before a release, follow the Release & Deployment checklist and run staging smoke tests.
- After a sprint or release, run a retrospective and track improvements as backlog items.

## Contributing

To add or update content, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/ and submit a PR with your proposed changes. The issue should explain the rationale, acceptance criteria, and include suggested content if possible.

## Document status

This README is a living index. When you add or rename files in docs/, please update this README with new links and a brief summary so the content remains discoverable.
