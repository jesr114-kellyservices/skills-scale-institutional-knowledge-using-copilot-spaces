# OctoAcme — Release Readiness Checklist

Use this checklist before every release to confirm the team has met all quality, communication, and operational requirements. The **PM owns the checklist**; QA, DevOps/Dev Lead, and PdM each sign off on their sections.

> **Template instructions**: Copy this file into the release folder or issue, fill in the release details at the top, and work through each section. Do not mark the checklist complete until all items are checked or explicitly waived with a documented reason.

---

## Release Details

| Field | Value |
|---|---|
| Release name / version | |
| Release type | Patch / Minor / Major — see [Release & Deployment Guide](octoacme-release-and-deployment.md) for definitions |
| Target deploy date | |
| PM | |
| Dev Lead / Engineer on duty | |
| QA Lead | |
| PdM sign-off | |

---

## 1. Scope & Requirements

- [ ] All features and fixes in scope are merged to the release branch
- [ ] All acceptance criteria for in-scope stories are met and verified
- [ ] Scope freeze date was observed; any late scope additions were approved by PdM
- [ ] Open bugs assessed: critical/high bugs are resolved or have an accepted mitigation
- [ ] Definition of Done (DoD) satisfied for all stories

**Notes / Exceptions:**

---

## 2. Testing & Quality

- [ ] Unit tests pass (CI green)
- [ ] Integration tests pass (CI green)
- [ ] End-to-end / smoke tests pass in staging
- [ ] Regression test suite executed by QA with no unresolved blockers
- [ ] Security scan (SAST/DAST) shows no new critical or high findings
- [ ] Accessibility review completed (if applicable)
- [ ] Performance tests run; results within acceptable thresholds (if applicable)

**QA sign-off** (name / date): ___________________________

**Notes / Exceptions:**

---

## 3. Documentation & Release Notes

- [ ] Release notes drafted and reviewed by PdM and Technical Writer
- [ ] API documentation updated (if applicable)
- [ ] User-facing docs updated for new or changed features
- [ ] Internal runbooks updated (if operations changed)
- [ ] CHANGELOG updated

**Notes / Exceptions:**

---

## 4. Operational Readiness

- [ ] Deployment runbook reviewed; steps are current and accurate
- [ ] Rollback plan documented and tested/verified
- [ ] Feature flags / toggles configured correctly for release
- [ ] Database migrations reviewed; rollback scripts prepared (if applicable)
- [ ] Monitoring and alerting confirmed for new components or changes
- [ ] On-call schedule confirmed for post-release window

**Dev Lead sign-off** (name / date): ___________________________

**Notes / Exceptions:**

---

## 5. Stakeholder & Communication Readiness

- [ ] PdM has approved the release scope
- [ ] Stakeholder communication plan is ready (email, Slack, etc.)
- [ ] Support team briefed on new features and known issues
- [ ] Marketing / customer-facing teams notified (if applicable)
- [ ] Deployment window communicated to relevant stakeholders

**PdM sign-off** (name / date): ___________________________

**Notes / Exceptions:**

---

## 6. Go / No-Go Decision

The **Project Manager (PM) is the final decision owner** for release go/no-go. PdM, QA Lead, and Dev Lead each provide their sign-off, but the PM is accountable for the final call and must explicitly record the decision below.

| Role | Sign-off | Date |
|---|---|---|
| Project Manager (PM) — **final decision owner** | | |
| Product Manager (PdM) | | |
| QA Lead | | |
| Dev Lead | | |

**Final Decision (PM)**: ☐ GO &nbsp;&nbsp;&nbsp; ☐ NO-GO

**If NO-GO — reason and next review date:**

---

## Related Documents
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [RACI & Ownership](octoacme-raci-ownership.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
