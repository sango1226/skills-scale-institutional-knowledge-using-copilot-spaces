# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, iterative project management approach centered on clear ownership, customer value, and data-informed decisions. Our methodology emphasizes transparency, collaboration, and continuous improvement across all project phases. This folder contains our complete project management playbook and serves as the authoritative hub for all process documentation.

## Quick Start

New to OctoAcme projects? Start here:

1. Read the [Project Management Overview](./octoacme-project-management-overview.md) (5 min)
2. Review [Roles and Personas](./octoacme-roles-and-personas.md) to find your role
3. Navigate to the process document relevant to your current phase

## Project Lifecycle

OctoAcme projects follow these five phases:

### 1. **Initiation** — Define the Problem

- **Document:** [Project Initiation Guide](./octoacme-project-initiation.md)
- **Focus:** Business need, success metrics, stakeholder alignment
- **Output:** Project One-pager
- **When to use:** Starting a new project or initiative

### 2. **Planning** — Create the Roadmap

- **Document:** [Project Planning](./octoacme-project-planning.md)
- **Focus:** Backlog prioritization, dependencies, timeline
- **Output:** Release plan and sprint backlog
- **When to use:** Sprint/milestone planning

### 3. **Execution** — Deliver the Work

- **Document:** [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Focus:** Daily standups, PR workflows, quality standards
- **Output:** Completed features, passing tests
- **When to use:** Daily delivery activities and PR reviews

### 4. **Release** — Go Live

- **Document:** [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Focus:** Pre-release checklist, deployment, rollback procedures
- **Output:** Production release and release notes
- **When to use:** Releases and hotfixes

### 5. **Close & Improve** — Capture Learnings

- **Document:** [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Focus:** Team retrospective, action items, process improvements
- **Output:** Documented learnings and process updates
- **When to use:** Post-sprint/release reviews

## Cross-Cutting Concerns

These processes apply across all project phases:

### Risk & Communication

- **Document:** [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Used in:** All phases
- **Focus:** Risk registers, escalation paths, stakeholder updates
- **When to use:** Escalations and status reporting

### Roles & Personas

- **Document:** [OctoAcme Personas](./octoacme-roles-and-personas.md)
- **Focus:** Role definitions, responsibilities, communication patterns
- **Includes:** Developers, Product Managers, Project Managers
- **When to use:** Understanding team dynamics and responsibilities

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

- **Keep your project's Charter/One-pager** in your project repo
- **Link to these docs** from your project README for team reference
- **Update docs** via the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
- **Store process-specific docs** in `.copilot/` if using Copilot Spaces for additional context
- **Reference relevant documents** in sprint planning, retrospectives, and onboarding sessions

## Process Flow Diagram

```
┌─────────────────────────────────────────────────────────────────┐
│ Initiation: Define the Problem                                  │
│ (Project One-pager, Success Metrics)                           │
└────────────────────┬────────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────────┐
│ Planning: Create the Roadmap                                    │
│ (Release Plan, Sprint Backlog)                                 │
└────────────────────┬────────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────────┐
│ Execution: Deliver the Work                                     │
│ (Daily Standups, PR Workflows, Quality Standards)              │
└────────────────────┬────────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────────┐
│ Release: Go Live                                                │
│ (Pre-release Checklist, Deployment, Rollback)                 │
└────────────────────┬────────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────────┐
│ Close & Improve: Capture Learnings                             │
│ (Retrospective, Action Items, Process Updates)                │
└─────────────────────────────────────────────────────────────────┘
                     │
             ┌───────▼──────────────────────┐
             │ Loop back to Planning or     │
             │ Initiation for next phase    │
             └──────────────────────────────┘

Throughout all phases:
• Risk Management & Communication
• Cross-functional collaboration
• Stakeholder engagement
```

## Key Principles

1. **Clear Ownership:** Every task, decision, and deliverable has a clear owner
2. **Customer Value:** Every feature and process improvement directly serves customer needs
3. **Data-Informed Decisions:** Metrics and feedback guide prioritization and decisions
4. **Iterative Improvement:** We continuously refine our processes based on learnings
5. **Transparency:** Information is shared openly across teams and phases
6. **Collaboration:** Cross-functional teams work together from initiation to retrospective

## Getting Help

- **Onboarding?** Start with the [Quick Start](#quick-start) section and [Project Management Overview](./octoacme-project-management-overview.md)
- **Stuck on a specific phase?** Find your phase above and reference the corresponding process document
- **Need to escalate a risk?** See [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Want to improve the process?** Document the gap or suggestion and open an issue using the process docs update template
- **Questions about roles?** Check [OctoAcme Personas](./octoacme-roles-and-personas.md)

## Contributing to Process Documentation

We welcome improvements to these processes. To suggest updates:

1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Describe the gap or suggested improvement
3. Include specific examples from your project experience
4. Get feedback from stakeholders before implementation

---

*Last Updated: September 2026*  
*For questions or feedback, please open an issue in this repository.*