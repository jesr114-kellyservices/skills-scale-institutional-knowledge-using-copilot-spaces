# OctoAcme — RACI & Ownership

## Purpose
Make artifact ownership and decision authority explicit across the project lifecycle.
This document is the single source of truth for "who owns what" and "who approves what",
reducing handoff ambiguity and preventing items from falling through the cracks.

> **Key**: R = Responsible (does the work) · A = Accountable (final sign-off) · C = Consulted (input required) · I = Informed (kept in the loop)

---

## Artifact Ownership

| Artifact | Project Manager (PM) | Product Manager (PdM) | Developer | QA Engineer | UX Designer | Technical Writer | Business Analyst |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project One-pager / Charter | **A** | C | I | I | I | I | C |
| Stakeholder Communication Plan | **A/R** | C | I | I | I | I | C |
| Prioritized Backlog | C | **A/R** | C | C | C | I | C |
| Acceptance Criteria (per story) | I | **A** (approves) | C | C | C | I | **R** (writes) |
| Definition of Done (DoD) | C | **A** | C | **R** | I | C | I |
| Sprint/Iteration Plan | **A/R** | C | C | I | I | I | I |
| Technical Design Docs | I | I | **A/R** | C | C | I | I |
| UX Design Specifications | I | C | C | I | **A/R** | I | I |
| Test Plan & Test Cases | C | I | C | **A/R** | I | I | I |
| Risk Register | **A/R** | C | C | C | I | I | C |
| Weekly Status Report | **A/R** | I | I | I | I | I | I |
| Release Notes | C | C | C | C | I | **A/R** | I |
| Release Readiness Checklist | **A** | C | C | **R** | I | C | I |
| Rollback Plan | **A** | I | **R** | C | I | I | I |
| Retrospective Action Items | **A/R** | C | C | C | I | I | I |
| Process Documentation (docs/) | C | I | I | I | I | **A/R** | I |

---

## Decision Authority

| Decision | Owner (Accountable) | Must Consult | Must Inform |
|---|---|---|---|
| Approve project go/no-go (initiation) | Sponsor / Product Leadership | PdM, PM, BA | All team members |
| Scope change (add/remove features mid-project) | PdM | PM, BA, Dev Lead | QA, UX, TW |
| Prioritization change to backlog | PdM | PM, BA | Dev, QA |
| Accept/reject a release (go/no-go) | PM | PdM, QA, Dev Lead | All stakeholders |
| Rollback decision in production | PM (on-call Lead if PM unavailable) | PdM, Dev Lead | Stakeholders, Support |
| Escalate blocker to sponsor | PM | PdM | Affected team members |
| Approve Definition of Done changes | PdM | PM, Dev Lead, QA | Full team |
| Accept security incident escalation | Security On-call | PM, Dev Lead | PdM, Stakeholders |
| Close retrospective action item | PM | Item Owner | Full team |

---

## Ownership by Lifecycle Phase

### Initiation
| Activity | Owner |
|---|---|
| Draft project one-pager | Business Analyst (with PdM input) |
| Stakeholder identification | PM |
| Approval to proceed (gate) | Sponsor / Product Leadership |
| Create project board / repo structure | PM |

### Planning
| Activity | Owner |
|---|---|
| Backlog prioritization | PdM |
| Acceptance criteria definition | PdM + Business Analyst |
| Definition of Done | Dev Lead + QA |
| Test plan creation | QA Engineer |
| Release plan & milestones | PM |
| Risk register (initial) | PM + BA |
| Design specifications ready | UX Designer |
| Documentation plan | Technical Writer |

### Execution & Tracking
| Activity | Owner |
|---|---|
| Daily standup facilitation | PM |
| Feature development | Developer |
| Design QA / fidelity review | UX Designer |
| Test execution & defect filing | QA Engineer |
| Risk register updates | PM |
| Documentation drafts | Technical Writer |
| Requirement clarifications | Business Analyst |

### Release & Deployment
| Activity | Owner |
|---|---|
| Release readiness sign-off | PM |
| Pre-release QA sign-off | QA Engineer |
| Deployment execution | Developer (DevOps/Eng Lead) |
| Release notes finalization | Technical Writer |
| Rollback plan documentation | Developer (reviewed by PM) |
| Stakeholder release announcement | PM |

### Retrospective
| Activity | Owner |
|---|---|
| Retrospective facilitation | PM |
| Action item assignment | PM (with team input) |
| Action item tracking | PM |
| Process documentation updates | Technical Writer |

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Release Readiness Checklist](octoacme-release-readiness-checklist.md)
