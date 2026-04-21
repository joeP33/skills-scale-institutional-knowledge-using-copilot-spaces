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

### Interactions
- Partner with Product Managers and Business Analysts to refine requirements and acceptance criteria.
- Collaborate with UX Designers on implementation feasibility and design intent.
- Work with QA Leads on test strategy, defect triage, and release quality gates.
- Coordinate with DevOps Engineers on CI/CD, deployment readiness, and observability.
- Support Data Analysts with instrumentation and event/data quality requirements.

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

### Interactions
- Partner with Business Analysts and UX Designers in discovery to clarify user and business needs.
- Align with Project Managers on sequencing, dependencies, and delivery risk.
- Define and review acceptance criteria with QA Leads and Developers.
- Review outcomes and experimentation insights with Data Analysts.
- Align release scope and risk trade-offs with DevOps Engineers and QA Leads.

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

### Interactions
- Coordinate staffing and handoffs across Developers, QA Leads, UX Designers, and DevOps Engineers.
- Partner with Product Managers and Business Analysts on scope clarity and dependency tracking.
- Ensure Data Analysts are looped in for metric readiness and post-release reporting.
- Own stakeholder communications while using role-specific inputs from Product, QA, and Engineering.

---

## QA Lead

### Role Summary
QA Leads define and enforce quality standards across planning, execution, and release.

### Responsibilities
- Define test strategy, quality gates, and release entry/exit criteria
- Translate acceptance criteria into testable scenarios with the team
- Coordinate test execution across functional and regression scopes
- Lead defect triage and quality risk assessment
- Recommend release go/no-go from a quality perspective

### Goals
- Prevent critical defects from reaching production
- Make quality criteria explicit and measurable
- Improve confidence in releases and faster remediation of issues

### Typical Communication
- Test planning sessions with Product and Development
- Defect triage updates during execution
- Release readiness updates and go/no-go recommendations

### Interactions
- With Project Manager: escalates quality risks and release blockers.
- With Product Manager: clarifies acceptance criteria and quality priorities.
- With Developers: aligns on testability, defect fixes, and regression coverage.
- With QA/Testing contributors: coordinates execution and coverage ownership.
- With Stakeholders: shares quality status through PM-led communications.

---

## UX Designer

### Role Summary
UX Designers shape user flows and interfaces to ensure solutions are usable, accessible, and aligned with user needs.

### Responsibilities
- Conduct user discovery and usability validation
- Produce user flows, wireframes, and prototypes
- Define interaction and accessibility expectations
- Collaborate on design-system and consistency decisions
- Support design QA during implementation

### Goals
- Improve usability, adoption, and task completion outcomes
- Reduce rework caused by unclear interaction design
- Ensure accessible and consistent experiences

### Typical Communication
- Discovery workshops and design reviews
- Prototype walkthroughs with Product and Engineering
- Usability findings and recommendations

### Interactions
- With Project Manager: aligns design milestones and dependencies.
- With Product Manager: co-leads discovery and feature framing.
- With Developers: hands off specs and resolves implementation details.
- With QA/Testing: clarifies expected behavior for acceptance and exploratory testing.
- With Stakeholders: supports demos with user-centered rationale.

---

## Data Analyst

### Role Summary
Data Analysts define and evaluate outcome metrics so teams can make evidence-based decisions.

### Responsibilities
- Define success metrics and measurement plans
- Validate analytics instrumentation and data quality
- Build dashboards and periodic performance reports
- Analyze outcomes and identify optimization opportunities
- Support experiment design and interpretation

### Goals
- Make project outcomes measurable and transparent
- Improve prioritization with reliable evidence
- Detect risks and opportunities early through data signals

### Typical Communication
- Metric definition sessions during planning
- Dashboard reviews in weekly delivery/product syncs
- Post-release outcome and trend reports

### Interactions
- With Project Manager: aligns reporting cadence and escalation thresholds.
- With Product Manager: defines KPIs tied to problem statements.
- With Developers: confirms event/logging requirements and data quality fixes.
- With QA/Testing: validates analytics behavior as part of test scenarios.
- With Stakeholders: provides outcome reporting via PM/PdM channels.

---

## DevOps Engineer

### Role Summary
DevOps Engineers own build, deployment, and runtime readiness to ensure reliable releases and operations.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Define environment readiness and release runbooks
- Ensure monitoring, alerting, and rollback mechanisms are in place
- Support incident response and post-incident improvements
- Partner on security and operational hardening

### Goals
- Increase deployment reliability and speed
- Reduce mean time to detect and recover from incidents
- Provide clear operational readiness signals before release

### Typical Communication
- Deployment readiness updates in release planning
- Incident and reliability updates during execution
- Post-deploy monitoring summaries

### Interactions
- With Project Manager: flags deployment risks and readiness constraints.
- With Product Manager: aligns release timing with operational constraints.
- With Developers: collaborates on pipeline reliability and infrastructure needs.
- With QA/Testing: supports stable test environments and release validation.
- With Stakeholders: contributes operational updates through PM-led communications.

---

## Business Analyst

### Role Summary
Business Analysts convert stakeholder needs into clear, testable requirements and process context for delivery teams.

### Responsibilities
- Elicit and document business requirements and constraints
- Map workflows, edge cases, and dependencies
- Support backlog refinement with clarifying detail
- Trace requirements to acceptance criteria and test scenarios
- Maintain requirement decisions and assumptions

### Goals
- Reduce ambiguity in scope and expected outcomes
- Improve handoff quality between business and delivery teams
- Increase first-pass delivery accuracy

### Typical Communication
- Stakeholder interviews and requirement workshops
- Backlog refinement and acceptance criteria reviews
- Clarification updates during implementation and testing

### Interactions
- With Project Manager: tracks requirement dependencies and scope impacts.
- With Product Manager: translates business needs into prioritized backlog detail.
- With Developers: answers requirement questions and edge-case behavior.
- With QA/Testing: supports traceability from requirements to test coverage.
- With Stakeholders: validates documented needs and assumptions.

---

## RACI-style guidance (lightweight)
- **Discovery**: Product Manager and Business Analyst are accountable; UX Designer and key Stakeholders are consulted.
- **Acceptance criteria**: Product Manager is accountable; Business Analyst and QA Lead are responsible for drafting/refining with Developers.
- **Testing strategy and release quality gate**: QA Lead is accountable; Developers and DevOps Engineer are responsible for execution readiness.
- **Deployment readiness and execution**: DevOps Engineer is accountable; Developers and QA Lead are responsible for technical and quality readiness.
- **Monitoring and outcomes**: DevOps Engineer and Data Analyst share accountability for operational and product outcome signals.
- **Stakeholder communication**: Project Manager is accountable; Product Manager provides product context and QA/DevOps provide quality/operational updates.

## Role Interaction Matrix (primary owner)
| Activity | Primary owner | Key collaborators |
| --- | --- | --- |
| Discovery | Product Manager | Business Analyst, UX Designer, Stakeholders, Project Manager |
| Acceptance criteria | Product Manager | Business Analyst, QA Lead, Developers |
| Testing | QA Lead | Developers, QA/Testing contributors, Product Manager |
| Deployment | DevOps Engineer | Developers, QA Lead, Project Manager |
| Monitoring | Data Analyst (outcomes), DevOps Engineer (runtime) | Product Manager, Developers |
| Stakeholder communication | Project Manager | Product Manager, QA Lead, DevOps Engineer |

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
