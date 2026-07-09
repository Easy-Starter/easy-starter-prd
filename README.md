# Easy Starter PRD

[![Persian README](https://img.shields.io/badge/README-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-blue?style=for-the-badge)](./README.fa.md)
![PRD Template](https://img.shields.io/badge/PRD-Template-2ea44f?style=for-the-badge)
![Design Brief](https://img.shields.io/badge/Design-Brief-7c3aed?style=for-the-badge)
![Spec Driven](https://img.shields.io/badge/Spec--Driven-Development-f97316?style=for-the-badge)
![AI Agent Ready](https://img.shields.io/badge/AI%20Agent-Ready-0ea5e9?style=for-the-badge)
![Markdown](https://img.shields.io/badge/Docs-Markdown-111827?style=for-the-badge&logo=markdown)
![License MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

A bilingual template repository for writing PRDs, Design Briefs, and Spec-Driven Development artifacts before implementation begins.

## Goal

Make documentation the single source of truth for product, design, engineering, QA, launch, and learning.

## Flow

Idea → Product One-Pager → Research → PRD → Design Brief → UX/UI Spec → Technical Brief → Feature Spec → Plan → Test-first Tasks → Implementation → Release → Post-launch Learning

## Structure

```text
templates/en/                 English product/design/engineering templates
templates/fa/                 Persian product/design/engineering templates
specs/_feature-template/       Spec-driven feature artifact template
specs/features/                Real feature specs go here
prompts/en/                    English AI prompts
prompts/fa/                    Persian AI prompts
checklists/                   Review gates
examples/                     Filled examples
.github/                      Issue and PR templates
```

## Requirement IDs

Use stable IDs everywhere:

- `GOAL-001` product/business goals
- `USER-001` user segments/personas
- `REQ-001` functional requirements
- `NFR-001` non-functional requirements
- `AC-001` acceptance criteria
- `EVT-001` analytics events
- `RISK-001` risks
- `DEC-001` decisions

## How to use

1. Start with `templates/en/00-product-one-pager.md` or `templates/fa/00-product-one-pager.fa.md`.
2. Use prompts in `prompts/` to clarify the idea and fill missing context.
3. Write the PRD and Design Brief.
4. Create one feature folder under `specs/features/001-feature-name/`.
5. Copy files from `specs/_feature-template/`.
6. Ask your coding agent to create `plan.md` and `tasks.md` from the spec.
7. Every PR should cite requirement IDs.
