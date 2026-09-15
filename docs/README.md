# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This directory contains lightweight, practical guides for running projects at OctoAcme.

## Our Approach

OctoAcme follows a customer-first, iterative delivery model with clear ownership and data-informed decisions. Each project has a named Project Manager and Product Lead, supported by developers, QA, and key stakeholders.

**Core Principles:**
- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: named PM and PdM for each project
- **Data-informed**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## OctoAcme Project Management Summary

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles. Projects progress through five distinct phases—Initiation, Planning, Execution, Release, and Close & Retrospective—each with defined deliverables and decision gates. The Initiation phase validates business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, SMART objectives, success metrics, and initial risk assessment. Once approved, the Planning phase breaks work into shippable increments, establishes a prioritized backlog with acceptance criteria, and creates a release plan with clear Definition of Done. This deliberate sequencing ensures that teams move into execution only when success criteria are clear, stakeholders agree on priority, and team availability is confirmed.

Execution and delivery are orchestrated through a disciplined team rhythm and structured communication cadence. Daily standups (15 minutes) focus on progress, blockers, and dependencies, while weekly delivery syncs showcase progress and flagged risks. Work is managed on a GitHub Projects board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done, supported by small, focused pull requests (≤400 lines when possible) that include issue links and acceptance criteria. Quality assurance is embedded throughout the cycle, requiring unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. A three-level escalation path—Team-level triage → PM escalation to Product Lead → Sponsor-level escalation—ensures blockers are surfaced and resolved quickly without stalling delivery.

Roles and responsibilities are clearly defined across three primary personas. Project Managers coordinate delivery activities, manage schedules and risks, and ensure consistent communication and documentation; Product Managers define what should be built, prioritize the backlog, and measure outcomes; and Developers implement features, write tests, participate in design reviews, and help identify technical risks. This tripartite model is reinforced by a weekly sync between PM and PdM, twice-weekly standups for the delivery team, and monthly stakeholder updates, ensuring alignment across all levels. Risk management is formalized through a Risk Register (captured during planning and updated weekly) that tracks ID, description, impact, likelihood, owner, and mitigation plan, creating visibility and accountability for managing uncertainties.

Release and post-project activities complete the cycle with equal rigor. Releases are categorized by type (Patch, Minor, Major), governed by pre-release checklists that verify passing CI, security scans, and prepared smoke tests, and documented with release notes and rollback plans to minimize production risk. After each sprint, release, or milestone, the team conducts a timebox retrospective (45–75 minutes) to capture learnings, identify 2–3 prioritized action items with clear owners, and review progress on previous improvements. This commitment to continuous improvement—measuring impact, celebrating wins, and iterating on processes—ensures that OctoAcme's project execution becomes more efficient and effective over time, while the living documentation in `docs/` remains a single source of truth for all teams.

## Documentation by Project Phase

### 1. **Initiation** — Validate and authorize work
📄 [Project Initiation Guide](octoacme-project-initiation.md)
Use this to confirm business need, identify stakeholders, and decide go/no-go for planning.

### 2. **Planning** — Turn ideas into actionable plans
📄 [Project Planning](octoacme-project-planning.md)
Break work into increments, estimate scope, define acceptance criteria, and identify dependencies.

### 3. **Execution** — Build, test, and iterate
📄 [Execution & Tracking](octoacme-execution-and-tracking.md)
Manage day-to-day delivery, track progress, and escalate blockers.

### 4. **Release** — Deploy to production
📄 [Release & Deployment Guide](octoacme-release-and-deployment.md)
Standardize releases, prepare deployment checklists, and plan rollbacks.

### 5. **Retrospective** — Capture learnings
📄 [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Convert learnings into actionable improvements.

## Cross-cutting Topics

- 📄 [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- 📄 [Roles and Personas](octoacme-roles-and-personas.md) — Key responsibilities and communication patterns
- 📄 [Project Management Overview](octoacme-project-management-overview.md) — High-level framework and roles

## Quick Start

**New to OctoAcme projects?**
1. Start with [Project Management Overview](octoacme-project-management-overview.md) for context
2. Read [Roles and Personas](octoacme-roles-and-personas.md) to understand your responsibilities
3. Follow the phase-specific guides as your project progresses

**Looking for something specific?**
- How do I start a new project? → [Project Initiation Guide](octoacme-project-initiation.md)
- How do I plan sprints? → [Project Planning](octoacme-project-planning.md)
- What's our PR and testing workflow? → [Execution & Tracking](octoacme-execution-and-tracking.md)
- How do we release? → [Release & Deployment Guide](octoacme-release-and-deployment.md)
- How do we handle risks? → [Risk Management & Communication](octoacme-risks-and-communication.md)

## Key Roles at a Glance

| Role | Responsibility |
|------|----------------|
| **Project Manager** | Coordinates delivery, schedules, risks, communications |
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success |
| **Developers** | Implement features, collaborate on design and testing |
| **QA/Testing** | Validate quality and acceptance criteria |
| **Stakeholders** | Provide inputs, approvals, and strategic guidance |

See [Roles and Personas](octoacme-roles-and-personas.md) for detailed responsibilities.
