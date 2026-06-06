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

### Primary Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **Stakeholders**: provide inputs and approvals.

### Specialized Roles (as needed by project scale)
- **QA/Testing Lead**: validates quality and acceptance criteria, owns testing strategy.
- **Release Manager**: coordinates release planning and deployment execution.
- **Technical Writer**: maintains project documentation and process guides.

For detailed role descriptions and responsibilities, see [OctoAcme Personas](./octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- Quality Assurance documentation
- Release readiness checklist

## Lifecycle (high-level)
1. **Initiation**: problem statement, stakeholders, high-level timeline.
2. **Planning**: scope, resources, milestones, dependencies.
3. **Execution**: build, test, review, iterate.
4. **Release**: deploy, verify, announce.
5. **Close & Retrospective**: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed
- Quality gates & test status reviews before release

## Quality & Testing Standards
- Unit tests for new logic (>80% coverage target)
- Integration and end-to-end tests for critical workflows
- Automated testing in CI/CD pipeline
- Manual acceptance testing by QA
- Security and performance testing pre-release

See [Quality Assurance Checklist](./octoacme-quality-assurance-checklist.md) for detailed QA process.

## Release & Deployment Process
- Coordinated by Release Manager
- Follows release readiness checklist
- Includes deployment window planning and post-release verification
- Rollback procedures documented and tested

See [Release & Deployment Guide](./octoacme-release-and-deployment.md) and [Release Readiness Checklist](./octoacme-release-readiness-checklist.md) for detailed procedures.

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Reference role descriptions when clarifying responsibilities or planning meetings.
- Use QA and Release checklists as templates for project execution.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Update these processes regularly based on retrospective learnings and team feedback.
