# OctoAcme Project Management Docs

This README provides a summary of OctoAcme project management processes and convenient links to all related documentation.

## Project Management Processes Summary

OctoAcme runs projects using an iterative, outcome-oriented lifecycle designed to deliver small, testable increments of value while keeping stakeholders aligned and risks visible. Projects begin with a lightweight initiation: a Project One-pager that defines the problem, measurable success criteria, primary stakeholders, and a high-level timeline. Planning converts approved initiatives into a prioritized backlog of shippable items with clear acceptance criteria, estimates, and a Definition of Done. Core artifacts include the Project One-pager, release plan, sprint backlog, risk register, and retrospective action items.

Execution emphasizes small-batch delivery and visible status via a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request workflow that enforces small PRs, linked issues and acceptance criteria, CI gating, and at least one reviewer approval. Teams keep a regular rhythm—daily standups to address blockers, weekly delivery syncs to align on progress and risks, demos at the end of sprints or milestones, and periodic stakeholder updates. Cross-team dependencies and blockers are escalated through a defined path (Team → PM → Product Lead → Sponsor).

Roles are explicit: Project Managers coordinate schedules, risks, and communications; Product Managers (PdMs) define outcomes and prioritize the backlog; Developers implement and test; QA verifies acceptance criteria and quality; and Stakeholders provide input and approvals. Communication uses templates (weekly status, incident triage) and a single source of truth in the project README or release doc to ensure clarity and reduce confusion.

Quality assurance is integrated into the delivery pipeline: unit and integration tests, CI security scans, end-to-end smoke tests for critical flows, and manual QA where needed. Releases require passing CI and security checks, release notes, and a rollback plan. Retrospectives after sprints and incidents turn learnings into tracked action items with owners and due dates, which feed back into the backlog to drive continuous improvement and reduce single-person risk.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
