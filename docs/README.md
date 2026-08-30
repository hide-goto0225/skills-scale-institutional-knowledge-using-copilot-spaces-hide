# OctoAcme — Project Management Overview

## Purpose
A concise overview of OctoAcme’s project management processes. Use this README as the single-source summary for project teams and stakeholders; detailed process docs live in docs/.

## Team rhythm
- Daily standups (15 min) for progress and blockers
- Weekly delivery sync to surface risks and progress
- Sprint/milestone demo & review

## Workflows & board
- Use a project board with columns: Backlog → Ready → In Progress → In Review → QA → Done
- Small PRs where possible; include issue link and acceptance criteria
- Run CI (tests, lint, security) before requesting reviews
- Require at least one approval before merge (team may require more)

## Planning & backlog
- Create a Project One-pager to confirm problem, goals, and success metrics
- Prioritize backlog with clear acceptance criteria and estimates
- Timebox sprint planning; pull items that meet Definition of Done (DoD)

## Quality & testing
- Unit tests for new logic; integration tests where applicable
- E2E smoke tests for critical flows pre-release
- Security scanning in CI; manual QA when required

## Release & deployment
- Follow Release & Deployment checklist: staging verification, rollback plan, release notes
- Classify releases (patch/minor/major) and schedule appropriately
- Post-deploy verifications and stakeholder announcements

## Risk & communication
- Maintain a Risk Register (ID, impact, likelihood, owner, mitigation)
- Weekly status updates: progress, next steps, risks/blockers, asks
- Escalation: Team → PM → Product Lead → Sponsor (or Security on-call for incidents)

## Roles & responsibilities (summary)
- Product Manager: defines outcomes & success metrics
- Project Manager: coordinates delivery, risks, timelines
- Developers: implement, test, and document
- QA: validates acceptance criteria
- Stakeholders: provide approvals and inputs

## How to use this repo
- Keep the Project One-pager and release docs updated in docs/
- Use the .github/ISSUE_TEMPLATE process for proposing doc updates
- Add process-specific materials into .copilot/ if you want Copilot Spaces to use them as context
