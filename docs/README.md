# OctoAcme Project Management Docs

This README serves as a central index for OctoAcme project management process documentation. It summarizes our approach and links directly to each process doc for quick reference.

OctoAcme runs projects through a clear lifecycle—initiation, planning, execution, release, and retrospective. Initiation focuses on a one‑pager, stakeholder alignment, and a go/no‑go decision. Planning breaks the work into prioritized, estimable backlog items with defined acceptance criteria and a Definition of Done. Execution uses timeboxed iterations, small pull requests, CI validation, and regular demos to ensure incremental delivery. Releases follow a checklist including pre‑release checks, rollback plans, and post‑deploy verification, and retrospectives capture learnings and action items that are tracked back into the backlog for continuous improvement.

Workflows are lightweight and concrete: teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done, a backlog item template (title, description, acceptance criteria, estimate, owner), and a PR workflow that emphasizes small changes, linked issues, CI checks, and at least one approval. Roles include Product Managers (define outcomes and success metrics), Project Managers (coordinate schedules, risks, and communications), Developers (implement and test), QA (validate acceptance), and Stakeholders (approve priorities). Communication rhythms center on daily standups, weekly delivery syncs, sprint demos, PM+PdM alignment, and monthly stakeholder updates; escalation paths are defined for blockers and incidents.

Quality assurance is embedded in the process: unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA where required. Pre‑release gates enforce acceptance criteria and passing CI/security checks, and the deployment checklist specifies staging verification, production deployment steps, and rollback procedures. Retrospectives after sprints, releases, or incidents capture "what went well," "what could improve," and prioritized action items that are tracked into the backlog so improvements are measured and iterated on.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution &amp; Tracking](octoacme-execution-and-tracking.md)
- [Risk Management &amp; Communication](octoacme-risks-and-communication.md)
- [Release &amp; Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective &amp; Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs

Keep the Project Charter updated in the project repo and add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context. If you update any process document, add a note in the CHANGELOG section of this README with the date and summary of the change.
