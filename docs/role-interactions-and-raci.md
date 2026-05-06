# OctoAcme — Role Interactions & RACI Matrix

## Purpose
This document clarifies ownership and collaboration for common project activities across all OctoAcme roles. It is intended to:

- **Reduce handoff confusion** by making accountability explicit.
- **Speed up onboarding** so new team members know who to involve at each stage.
- **Provide escalation paths** when decisions stall or requirements are unclear.

---

## RACI Key

| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; signs off |
| **C** | Consulted — provides input; two-way communication |
| **I** | Informed — kept up-to-date; one-way communication |

---

## RACI Matrix

| Activity | PdM | PM | Developers | QA | Scrum Master | UX Designer | Technical Writer | Business Analyst | Stakeholder Rep |
|---|---|---|---|---|---|---|---|---|---|
| Requirements & backlog grooming | A | C | C | C | C | C | I | R | C |
| Design & UX | C | I | C | I | I | R/A | I | C | C |
| Implementation | C | I | R/A | C | I | C | I | I | I |
| Code review | C | I | R/A | C | I | I | I | I | I |
| Testing / QA | C | I | C | R/A | I | C | I | C | I |
| Release & deployment | A | R | R | C | C | I | C | I | C |
| Stakeholder sign-off | C | C | I | I | I | C | C | C | R/A |

> **Note:** Where a cell shows **R/A**, that role is both doing the work and accountable for the outcome. Multiple **R** entries in a row mean the work is shared; there should still be a single **A**.

---

## Practical Guidance

### Typical Handoffs

| From | To | Trigger |
|---|---|---|
| Business Analyst → PdM | Validated requirements and user stories | After requirements workshop is completed |
| PdM → Developers | Groomed backlog with acceptance criteria | Sprint planning session |
| UX Designer → Developers | Approved design specs | Design review signed off by PdM |
| Developers → QA | Feature branch ready for testing | PR merged to integration branch |
| QA → PM | Test results and release readiness report | Test cycle complete |
| PM → Stakeholder Rep | Release readiness summary | Pre-release review meeting |
| Technical Writer → PM | Draft release notes | Final QA sign-off received |

### Escalation Paths

| Situation | Who to Contact First | Escalate To |
|---|---|---|
| Requirements are unclear or conflicting | Business Analyst | PdM, then Stakeholder Representative |
| Blocker is unresolved after daily standup | Scrum Master | PM for cross-team escalation |
| Design decision needed urgently | UX Designer | PdM |
| Release readiness is in question | QA | PM, then Stakeholder Representative |
| Scope change is requested mid-sprint | PM | PdM and Stakeholder Representative |
| Documentation accuracy questioned | Technical Writer | Relevant Subject-Matter Expert (Developer or PdM) |

---

## Cross-Role Collaboration Notes

- **PdM and Business Analyst** should align early so requirements reflect both product strategy and business process needs.
- **Scrum Master and PM** work together on sprint capacity; the Scrum Master owns the team process while the PM owns external commitments and stakeholder communication.
- **UX Designer and QA** should coordinate on usability and accessibility acceptance criteria so testing covers design intent, not just functional correctness.
- **Technical Writer** should be looped into sprint planning so documentation work is treated as a first-class deliverable alongside code.
- **Stakeholder Representative** approval is required before any major release or scope change; involve them early to avoid last-minute blockers.
