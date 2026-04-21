# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing and QA Lead: validate quality, define quality gates, and support release decisions.
- UX Designer: supports discovery, prototyping, and usability alignment.
- Business Analyst: documents requirements and maps business workflows.
- DevOps Engineer: owns deployment readiness and runtime reliability.
- Data Analyst: defines and reports success metrics.
- Stakeholders: provide inputs and approvals.

See [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) for detailed responsibilities and interactions, and [`checklists/role-onboarding-quick-reference.md`](./checklists/role-onboarding-quick-reference.md) for a quick role reference.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Initiation and planning loop-in guidance
- **Discovery:** Loop in Product Manager (lead), Business Analyst, UX Designer, and key Stakeholders; include Project Manager for timeline/dependency alignment.
- **Acceptance criteria:** Loop in Product Manager (owner), Business Analyst, QA Lead, and Developers to ensure clarity and testability.
- **Test planning:** Loop in QA Lead (owner), Developers, Product Manager, and DevOps Engineer for environment/readiness dependencies.
- **Release readiness:** Loop in DevOps Engineer and QA Lead as readiness gate owners, with Project Manager coordinating stakeholder timing and Product Manager confirming scope/value.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
