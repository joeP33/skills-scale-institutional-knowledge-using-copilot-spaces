# Release and Deployment Checklist

Use this checklist for coordinated, lower-risk releases. Owners can be reassigned per project, but each item should have a named owner before release day.

## Pre-release
- [ ] **Product Manager (owner):** Confirm scope, acceptance criteria, and release notes draft are complete.
- [ ] **Project Manager (owner):** Confirm release window, stakeholder communication plan, and escalation contacts.
- [ ] **QA Lead (owner):** Confirm test plan completion and open defects are triaged with go/no-go recommendation.
- [ ] **Developers (owner):** Confirm required code reviews, merged PRs, and feature flags/config readiness.
- [ ] **DevOps Engineer (owner):** Verify CI/CD pipeline health, environment readiness, and rollback procedure.
- [ ] **Data Analyst (owner):** Confirm KPI dashboard/report readiness and instrumentation checks.

## Deployment
- [ ] **DevOps Engineer (owner):** Execute deployment pipeline and validate stage gates.
- [ ] **QA Lead (owner):** Run smoke tests for critical user journeys in target environment.
- [ ] **Developers (owner):** Support rapid triage/fix for deployment-time defects.
- [ ] **Project Manager (owner):** Coordinate release room updates and timeline checkpoints.
- [ ] **Product Manager (owner):** Validate key product behavior against release goals.

## Post-deploy verification
- [ ] **QA Lead (owner):** Confirm no critical regressions and report release quality status.
- [ ] **DevOps Engineer (owner):** Confirm system health (errors, latency, alerts) is within thresholds.
- [ ] **Data Analyst (owner):** Validate telemetry flow and baseline KPI capture.
- [ ] **Project Manager (owner):** Send stakeholder update with release status and known issues.
- [ ] **Product Manager (owner):** Confirm customer-facing messaging or support notes if needed.

## Rollback
- [ ] **DevOps Engineer (owner):** Trigger rollback to last known-good version when rollback criteria are met.
- [ ] **QA Lead (owner):** Re-run critical smoke checks after rollback.
- [ ] **Developers (owner):** Diagnose root cause and prepare corrective action.
- [ ] **Project Manager (owner):** Coordinate incident communication and next decision checkpoint.
- [ ] **Product Manager (owner):** Reassess release scope and prioritize remediation.
