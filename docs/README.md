# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, iterative project management approach centered on clear ownership, customer value, and data-informed decisions. This folder contains our complete project management playbook for delivering features, services, and integrations across the organization.

OctoAcme projects follow five core phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**—with embedded risk management and stakeholder communication throughout. During initiation, teams validate business needs and create a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Once stakeholders align and the go/no-go decision is made, projects move into planning, where work is broken into shippable increments with detailed acceptance criteria, estimates, and a risk register.

Execution and delivery are coordinated through a clear team rhythm and defined roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what should be built and measure outcomes; **Developers** implement features and write tests; and **Stakeholders** provide inputs and approvals. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs review updates and flagged risks. Work is tracked on a project board, and Pull Requests follow strict conventions—kept small, including issue links and acceptance criteria, and requiring at least one approval before merging.

Quality and risk management are embedded throughout the lifecycle. Teams practice unit testing, integration testing, and end-to-end smoke tests, with security scanning in CI and manual QA for feature acceptance. A **Risk Register** is maintained with clear escalation paths, and communication is proactive and structured through weekly status updates and monthly stakeholder briefings. The cycle completes with standardized **Release & Deployment** procedures and structured **Retrospective & Continuous Improvement** phases, where teams capture learnings and drive continuous refinement of both delivery processes and product quality.

## Quick Start

New to OctoAcme projects? Start here:

1. Read the [Project Management Overview](./octoacme-project-management-overview.md) (5 min)
2. Review [Roles and Personas](./octoacme-roles-and-personas.md) to find your role
3. Navigate to the process document relevant to your current phase

## Project Lifecycle

OctoAcme projects follow these phases:

### 1. **Initiation** — Define the Problem

- **Document:** [Project Initiation Guide](./octoacme-project-initiation.md)
- **Focus:** Business need, success metrics, stakeholder alignment
- **Output:** Project One-pager
- **Key Question:** Is this idea worth exploring?

### 2. **Planning** — Create the Roadmap

- **Document:** [Project Planning](./octoacme-project-planning.md)
- **Focus:** Backlog prioritization, dependencies, timeline
- **Output:** Release plan and sprint backlog
- **Key Question:** How do we break this into shippable increments?

### 3. **Execution** — Deliver the Work

- **Document:** [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Focus:** Daily standups, PR workflows, quality standards
- **Output:** Completed features, passing tests
- **Key Question:** Are we on track and meeting quality standards?

### 4. **Release** — Go Live

- **Document:** [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Focus:** Pre-release checklist, deployment, rollback procedures
- **Output:** Production release and release notes
- **Key Question:** Is this ready and safe to ship?

### 5. **Close & Improve** — Capture Learnings

- **Document:** [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Focus:** Team retrospective, action items, process improvements
- **Output:** Documented learnings and process updates
- **Key Question:** What went well, and what can we improve?

## Cross-Cutting Concerns

### Risk & Communication

- **Document:** [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Used in:** All phases
- **Focus:** Risk registers, escalation paths, stakeholder updates
- **Key Activities:** Maintain risk register, weekly status updates, escalation triage

### Roles & Personas

- **Document:** [OctoAcme Personas](./octoacme-roles-and-personas.md)
- **Focus:** Role definitions, responsibilities, communication patterns
- **Includes:** Developers, Product Managers, Project Managers, Stakeholders

## All Documents

| Document | Purpose | Best For |
|----------|---------|----------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme approach | Team onboarding, executive briefings |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Validate new ideas and get stakeholder buy-in | Starting a new project |
| [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments | Sprint/milestone planning |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery activities | Daily standups, PR reviews |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Manage risks and stakeholder updates | Escalations, status reporting |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize release procedures | Releases and hotfixes |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture and act on learnings | Post-sprint/release reviews |
| [OctoAcme Personas](./octoacme-roles-and-personas.md) | Define roles and responsibilities | Understanding team dynamics |

## How to Use These Docs

- **For new projects:** Start with Initiation, then Planning, then move through Execution → Release → Retrospective
- **For ongoing projects:** Reference Execution & Tracking and Risk Management & Communication for day-to-day guidance
- **For your project repo:** Keep your project's Charter/One-pager in your project README and link to these docs for team reference
- **For Copilot Spaces:** Store process-specific docs in `.copilot/` if using Copilot Spaces for additional context
- **To contribute:** Update docs via the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

## Key Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Communication Cadence

- **Daily:** 15-min standups with delivery team
- **Weekly:** PM + PdM sync; twice-weekly standups (or as agreed)
- **Monthly:** Stakeholder updates
- **Ad-hoc:** Escalations as needed

---

**Last Updated:** September 2026  
**Maintained by:** OctoAcme Project Management Team
