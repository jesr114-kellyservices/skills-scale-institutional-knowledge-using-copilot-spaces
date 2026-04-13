# OctoAcme Project Management Docs

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle that emphasizes customer value, iterative delivery, and clear ownership. Work moves through five phases: **Initiation** (validate the problem, define SMART outcomes, and align stakeholders), **Planning** (turn the approved initiative into a prioritized backlog and release plan with acceptance criteria and a Definition of Done), **Execution** (deliver in small, testable increments tracked on a project board with columns Backlog → Ready → In Progress → In Review → QA → Done), **Release** (deploy with risk controls, a staged deployment checklist, and post-deploy verification), and **Close & Retrospective** (capture learnings and feed improvements back into the backlog). Core artifacts—Project Charter/One-pager, roadmap and release plan, sprint backlog, risk register, and retrospective action items—serve as the single source of truth and keep work transparent and measurable. The PR workflow reinforces quality: keep PRs small, link the related issue and acceptance criteria, pass CI (tests, lint, security scans) before requesting review, and require approvals before merging.

Roles and responsibilities are intentionally explicit to reduce ambiguity. Each project has a named **Project Manager (PM)** who coordinates delivery execution—schedule, risks, dependencies, facilitation, and status reporting—and a **Product Manager / Product Lead (PdM)** who defines outcomes, prioritizes the backlog, and measures impact. **Developers** implement features, write and maintain tests, participate in design and code reviews, and help identify technical risks. **QA/Testing** validates acceptance criteria and quality standards. **Stakeholders** provide inputs and approvals. The model stresses psychological safety so teams can surface risks early, make data-informed decisions, and improve continuously.

Communication follows a defined cadence and clear escalation paths. Teams maintain a consistent rhythm: daily standups (progress, blockers, dependencies), weekly delivery syncs (progress demos, risks), and sprint/milestone reviews. Stakeholder communication is supported by a regular PM+PdM sync, monthly stakeholder updates as needed, and lightweight weekly status templates (progress, next steps, risks/blockers, asks/decisions). Risks and dependencies are managed through a **risk register** (impact, likelihood, owner, mitigation, status) reviewed at least weekly. Blockers escalate from team triage → PM → Product Lead/dependent teams → sponsor/product leadership for business-impacting issues, with a separate security incident runbook for security escalations.

Quality assurance is built into delivery and release workflows rather than treated as an afterthought. Testing expectations include unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, CI security scanning, and manual QA for feature acceptance when needed. Releases follow standardized pre-release requirements—acceptance criteria met, CI/security scans passing, release notes prepared, rollback plan documented, smoke tests passing—and a deployment checklist covering staging verification, production deploy, post-deploy checks, and stakeholder announcements. An incident/rollback playbook supports fast recovery, and blameless **retrospectives** after every sprint, release, or incident produce a small set of owned, time-bound improvement actions tracked back into the backlog.

---

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, principles, core roles, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Problem validation, stakeholder alignment, and project charter |
| [Project Planning](octoacme-project-planning.md) | Backlog building, acceptance criteria, estimation, and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Board workflow, PR process, standups, and delivery cadence |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, team rhythm, status updates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, and incident/rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action items, and improvement tracking |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each project role |
