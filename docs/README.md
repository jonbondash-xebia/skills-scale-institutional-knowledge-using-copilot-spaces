# OctoAcme Project Management Docs

This repository contains OctoAcme's program and project management process documents. The README serves as a single entrypoint that explains the purpose of these docs, provides a summary of our project management approach, and links to each document in the docs/ folder.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process is organized into five core phases: **Initiation**, where business needs are validated and stakeholders align on success metrics; **Planning**, where work is broken into shippable increments with defined acceptance criteria and dependencies; **Execution**, where teams deliver through daily standups and sprint cycles with continuous quality checks; **Release**, where features are deployed to production with minimal risk; and **Closure**, where learnings are captured through retrospectives.

The organization assigns clear ownership across three primary roles working in concert. **Project Managers** coordinate delivery schedules, manage risks and dependencies, and ensure transparent communication with stakeholders. **Product Managers** define what should be built by owning the vision, prioritizing the backlog, and validating outcomes through metrics and user research. **Developers** implement features collaboratively, write and maintain tests, and help identify technical risks.

Communication and transparency are woven throughout OctoAcme's workflows via a regular cadence: daily standups focus on progress and blockers; weekly PM-PdM syncs align on priorities and risks; twice-weekly team standups keep execution on track; and monthly stakeholder updates maintain visibility. Risk management is continuous—risks are identified during planning, assessed for impact and likelihood, and reviewed weekly with clear owners and mitigation plans.

Quality and delivery excellence are ensured through disciplined execution practices. Teams use GitHub Projects to track work through defined columns (Backlog, Ready, In Progress, In Review, QA, Done), maintain a Definition of Done that all items must meet before closure, and enforce a pull request workflow with automated CI testing, code review requirements, and security scanning. Pre-release requirements include passing acceptance criteria, CI and security checks, documented rollback plans, and smoke tests. Post-release, teams conduct retrospectives to capture what went well, identify improvements, and track action items.

## Process Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise intro to OctoAcme's principles, core roles, key artifacts, and high-level lifecycle.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and initiation checklist.

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery. Covers backlog items, sprint planning, risk and dependency management.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones. Includes team rhythm, PR workflow, quality and testing practices, and blocker escalation.

- **[Risks & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies. Includes risk register template, communication templates, and escalation paths.

- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklist, and rollback playbook.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements. Includes retrospective structure and action item tracking.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Defines typical roles and responsibilities used in OctoAcme projects, including Developers, Product Managers, and Project Managers.

## How to Use These Docs

- **Getting Started**: New team members should start with the [Project Management Overview](octoacme-project-management-overview.md) to understand OctoAcme's approach and roles.

- **Adding or Updating Process Docs**: When you want to add new content or update an existing process document, use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) in this repository.

- **Keeping Docs Current**: Keep checklists and decision gates up to date to ensure consistent execution across all projects.

- **Using in Copilot Spaces**: These docs can be attached to a Copilot Space to provide context-specific guidance for project execution.

## Key Principles

OctoAcme's project management is built on these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions.
- **Iterative delivery**: Deliver small, testable increments rather than monolithic releases.
- **Clear ownership**: Each project has named roles with defined responsibilities.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback, learning, and continuous improvement.
