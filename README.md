# Easy Starter PRD

[![Persian README](https://img.shields.io/badge/README-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-blue?style=for-the-badge)](./README.fa.md)
![PRD Template](https://img.shields.io/badge/PRD-Template-2ea44f?style=for-the-badge)
![Design Brief](https://img.shields.io/badge/Design-Brief-7c3aed?style=for-the-badge)
![Spec Driven](https://img.shields.io/badge/Spec--Driven-Development-f97316?style=for-the-badge)
![AI Agent Ready](https://img.shields.io/badge/AI%20Agent-Ready-0ea5e9?style=for-the-badge)
![License MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

> “What do we build for, if not to lessen each other’s hardship?”

## What is this?

A starter kit for turning product ideas into clear PRDs, design briefs, specs, plans, and implementation-ready tasks.

Before the first line of code, this repository helps your team answer the questions that actually shape a product:

- **What are we building?**
- **Who are we building it for?**
- **Why does it matter?**
- **What does success look like?**
- **What should the designer, developer, QA, and AI coding agent follow?**

The goal is simple: **make the docs the single source of truth, not scattered chats, vague memories, or hidden assumptions.**

---

## Why this exists?

Most projects fail because the team starts building before the problem, user, scope, edge cases, and success criteria are clear.

**Easy Starter PRD** gives you a repeatable workflow for moving from a raw idea to a product-ready specification. It is useful for solo builders, freelancers, startups, product teams, and AI-first development workflows.

---

## What you can create with this repository?

- Product One-Pagers
- User Research Notes
- Personas and JTBD docs
- PRDs
- Design Briefs
- UX/UI Specifications
- Technical Briefs
- API and Data Specs
- Feature Specs
- Implementation Plans
- Test-first Task Lists
- Launch Plans
- Post-launch Learning Notes

---

## The workflow

Each step turns uncertainty into something easier to discuss, review, design, build, test, and improve.

```text
Idea
  ↓
Product One-Pager
  ↓
Research
  ↓
PRD
  ↓
Design Brief
  ↓
UX/UI Spec
  ↓
Technical Brief
  ↓
Feature Spec
  ↓
Plan
  ↓
Test-first Tasks
  ↓
Implementation
  ↓
Release
  ↓
Post-launch Learning
```

---

## Repository structure

```text
templates/                  English product, design, and engineering templates
specs/_feature-template/       Reusable feature folder for spec-driven development
specs/features/                Real feature specs live here
prompts/                    English prompts for product, design, and coding agents
checklists/                    Review gates before moving forward
examples/                      Filled examples for faster understanding
.github/                       Issue and pull request templates
```

---

## Recommended starting point

Start here:

```text
templates/en/00-product-one-pager.md
```

Then continue step by step. Do not rush into implementation too early. A few extra minutes in the docs can save hours of rework later.

---

## Requirement IDs

Use stable IDs across PRDs, specs, tasks, commits, pull requests, and test cases.

| ID         | Meaning                                |
| ---------- | -------------------------------------- |
| `GOAL-001` | Product or business goal               |
| `USER-001` | User segment, persona, or actor        |
| `REQ-001`  | Functional requirement                 |
| `NFR-001`  | Non-functional requirement             |
| `AC-001`   | Acceptance criterion                   |
| `EVT-001`  | Analytics event                        |
| `RISK-001` | Risk, assumption, or open question     |
| `DEC-001`  | Product, design, or technical decision |

This makes every implementation decision traceable back to the product intent.

---

## How to use this repository?

1. Clone or use this repository as a template.
2. Fill the Product One-Pager first.
3. Use the prompts in `prompts/` to clarify missing context.
4. Write the PRD and Design Brief.
5. Create a new feature folder under `specs/features/001-feature-name/`.
6. Copy the files from `specs/_feature-template/` into that feature folder.
7. Turn the feature spec into `plan.md` and `tasks.md`.
8. Ask your coding agent to implement only what is written in the spec and tasks.
9. Make every pull request reference the related requirement IDs.
10. After release, document what you learned and update the source of truth.

---

## Working with AI coding agents

This repo is designed to work well with tools like coding agents, AI IDEs, and spec-driven development workflows.

A good rule:

> Do not ask the agent to “build the app.”  
> Ask the agent to implement a specific feature spec with clear requirements, acceptance criteria, tests, and constraints.

That small shift makes AI-assisted development much more predictable, maintainable, and reviewable.

---

## Best for

- Freelance projects
- SaaS products
- MVPs
- Internal tools
- AI-first development workflows
- Product design handoff
- Startup discovery and validation
- Teams that want clearer collaboration

---

## License

MIT License. Use it, adapt it, remix it, and make your product process a little smoother.
