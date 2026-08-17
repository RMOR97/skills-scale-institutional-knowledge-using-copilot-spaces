# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects using a customer-first, iterative delivery approach with clear ownership, data-informed decision-making, and psychological safety. These documents centralize our processes, roles, and best practices so teams can plan, deliver, and improve consistently. The docs cover the full project lifecycle from initiation and planning through execution, release, and continuous improvement, plus supporting templates and communication guides.

This README provides quick navigation to the process docs, links to templates, and guidance on when to use each document. Use this as the single entry point for OctoAcme project management guidance and the canonical place to add or update process material.

## Quick Start
- New to OctoAcme? Start with the Project Management Overview: docs/octoacme-project-management-overview.md
- Starting a new project? Follow the Project Initiation Guide: docs/octoacme-project-initiation.md
- Planning delivery? See Project Planning: docs/octoacme-project-planning.md
- Running day-to-day delivery? See Execution & Tracking: docs/octoacme-execution-and-tracking.md
- Preparing releases? See Release & Deployment: docs/octoacme-release-and-deployment.md
- Running retrospectives? See Retrospective & Continuous Improvement: docs/octoacme-retrospective-and-continuous-improvement.md

## Documentation Map

### Project Phases
1. Project Initiation — docs/octoacme-project-initiation.md  
   Validate the business need, align stakeholders, and produce a lightweight one‑pager to inform planning.
2. Project Planning — docs/octoacme-project-planning.md  
   Break approved work into prioritized, estimated backlog items, define the Definition of Done, and map releases/milestones.
3. Execution & Tracking — docs/octoacme-execution-and-tracking.md  
   Manage day-to-day work via the project board, small PRs, CI gates, and a regular team rhythm (standups, weekly syncs, demos).
4. Release & Deployment — docs/octoacme-release-and-deployment.md  
   Standardized pre-release checks, automated pipelines where possible, smoke tests, and rollback playbooks.
5. Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md  
   Timeboxed retrospectives produce prioritized action items tracked into the backlog and reviewed in syncs.

### Supporting Guides
- Roles & Personas — docs/octoacme-roles-and-personas.md (PM, PdM, Developers, QA responsibilities)
- Risk Management & Communication — docs/octoacme-risks-and-communication.md (risk register, escalation, stakeholder templates)
- Issue Template for process updates — .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Core Principles
- Customer-first: prioritize customer value and usability.  
- Iterative delivery: deliver small, testable increments.  
- Clear ownership: name a Project Manager and Product Lead for each project.  
- Data-informed decisions: measure impact and iterate.  
- Psychological safety: encourage feedback and learning.

## Key Workflows & Practices (brief overview)
OctoAcme follows a clear lifecycle: initiation to confirm the problem and success metrics; planning to create a prioritized, estimated backlog; execution using a project board and small pull requests with acceptance criteria; and staged release with smoke tests and rollback plans. Pull request and CI practices encourage small, reviewable changes (aiming for small PRs), automated testing and security scanning before review, and at least one approval before merging.

Roles are explicit: the Product Manager owns outcomes and prioritization; the Project Manager coordinates schedule, risks, and communications; developers implement and maintain tests and documentation; QA validates acceptance criteria. Communication cadence includes daily standups for blockers, weekly delivery syncs (progress & risks), PM–PdM weekly alignment, and monthly stakeholder updates. Risk management uses a Risk Register and defined escalation paths from team → PM → Product Lead → Sponsor.

Quality assurance mixes automation and manual checks: unit, integration, and E2E smoke tests; security scanning in CI; and manual QA for acceptance when needed. Tests and scans should pass before requesting reviews, and retrospectives drive continuous improvements that are tracked as backlog items.

## How to use these docs
- Keep the project one‑pager and README updated in the project repo.  
- Add process-specific or project-specific notes into `.copilot/` if you want Copilot Spaces to use them as context.  
- To request an update to these process docs, use the Issue Template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Acceptance Criteria for this README
- [x] Content aligns with existing process docs  
- [x] Update improves clarity or closes a documented gap  
- [ ] Proposed content has been reviewed with stakeholders (if needed)
