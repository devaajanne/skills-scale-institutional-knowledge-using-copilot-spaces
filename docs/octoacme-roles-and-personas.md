# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They protect the team's focus and help maintain a sustainable delivery pace.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and remove blockers that slow the team
- Coach team members on agile principles and practices
- Shield the team from unplanned interruptions during a sprint
- Track team health and surface process improvement opportunities

### Goals
- Enable consistent, predictable delivery cadence
- Foster a culture of continuous improvement
- Keep ceremonies efficient and focused

### Typical Communication
- Daily standups and impediment tracking
- Sprint retrospective action items
- Coordination with PM and PdM on capacity and planning

### Interactions
- **PM**: Coordinates on sprint scope, timeline risks, and escalation of unresolved blockers.
- **PdM**: Aligns on backlog readiness and ensures stories meet the Definition of Ready before planning.
- **Developers**: Removes technical or organisational blockers; coaches on agile practices.
- **QA**: Ensures testing tasks are accounted for in sprint capacity and DoD.
- **Stakeholders**: Facilitates demo/review sessions and manages expectations on velocity.

---

## UX Designer

### Role Summary
UX Designers are responsible for user research, interaction design, and usability validation. They translate user needs into wireframes, prototypes, and design specifications that guide implementation.

### Responsibilities
- Conduct user research, interviews, and usability tests
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns and accessibility requirements
- Collaborate with PdM on feature requirements and acceptance criteria
- Review implemented UI against designs and flag discrepancies

### Goals
- Deliver intuitive, accessible user experiences
- Reduce usability-driven rework in later stages
- Ensure design decisions are grounded in user evidence

### Typical Communication
- Design reviews and prototype walkthroughs with PdM and Developers
- Usability test reports shared with the wider team
- Annotations and design specs in the project design tool

### Interactions
- **PM**: Aligns design milestones with the project schedule; flags scope impacts of design changes.
- **PdM**: Co-owns acceptance criteria for UX; validates that designs meet product goals.
- **Developers**: Provides design specs, answers implementation questions, and reviews delivered UI.
- **QA**: Supports usability and accessibility test cases.
- **Stakeholders**: Presents prototypes for feedback and incorporates sign-off on major design decisions.

---

## Technical Writer

### Role Summary
Technical Writers capture, organise, and maintain documentation so that all team members and end users can understand and use the product effectively.

### Responsibilities
- Write and maintain user guides, API docs, release notes, and process artifacts
- Interview subject-matter experts to gather accurate information
- Review documentation for accuracy, consistency, and clarity
- Maintain the docs versioning and publication pipeline
- Ensure documentation is updated as part of each release

### Goals
- Reduce support burden through clear, accurate documentation
- Shorten onboarding time for new team members and users
- Provide a single source of truth for product and process knowledge

### Typical Communication
- Sync with Developers and PdM during feature development and release prep
- Release note drafts shared with PM for sign-off
- Documentation reviews embedded in the PR/review process

### Interactions
- **PM**: Coordinates documentation deliverables within the release schedule.
- **PdM**: Reviews feature descriptions and success metrics for accuracy in docs.
- **Developers**: Collaborates on API documentation, code comments, and technical accuracy.
- **QA**: Cross-references test scenarios with documented expected behaviour.
- **Stakeholders**: Shares release notes and user-facing docs for review before publication.

---

## Business Analyst

### Role Summary
Business Analysts elicit requirements, map business processes, and bridge communication between stakeholders and the delivery team to ensure the right problems are solved.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create process maps, user stories, and acceptance criteria
- Analyse data and workflows to identify gaps and improvement opportunities
- Facilitate workshops and requirements sessions with stakeholders
- Maintain the requirements traceability matrix

### Goals
- Ensure the team builds solutions that address real business needs
- Reduce ambiguity and rework caused by unclear requirements
- Support data-driven decision-making across the project

### Typical Communication
- Requirements workshops and story-refinement sessions
- Business requirements documents (BRDs) and user story write-ups
- Regular syncs with PdM and Stakeholder Representatives

### Interactions
- **PM**: Supports scope definition, change control, and risk identification related to requirements.
- **PdM**: Co-owns the backlog refinement process; translates business needs into product requirements.
- **Developers**: Clarifies requirements and acceptance criteria during implementation.
- **QA**: Provides requirements context to inform test case design.
- **Stakeholders**: Facilitates requirement elicitation sessions and validates documented needs.

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives act as the voice of the business or end-user community. They provide strategic direction, clarify priorities, and approve key deliverables throughout the project.

### Responsibilities
- Articulate business goals and priorities to the project team
- Review and approve key deliverables (requirements, designs, release readiness)
- Participate in demos, milestone reviews, and steering meetings
- Escalate business-critical issues and unblock decisions
- Communicate project status to the broader business community

### Goals
- Ensure the project delivers measurable business value
- Maintain stakeholder confidence and alignment
- Enable timely decisions to keep delivery on track

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalations and decision requests via PM
- Demo attendance and sign-off at end of each major sprint or phase

### Interactions
- **PM**: Primary point of contact for status updates, escalations, and change requests.
- **PdM**: Aligns on product vision, priorities, and success metrics.
- **Developers**: Provides context during demos; rarely interacts during day-to-day delivery.
- **QA**: Reviews and approves acceptance test results before release.
- **Business Analyst**: Collaborates closely to validate that documented requirements reflect business intent.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

