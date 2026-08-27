# The Eyes — Codex Development Instructions

## Project
The Eyes is an election monitoring and reporting platform. This repository currently contains the Field Agent Prototype V1.

## Current scope
Build a polished prototype for:
- Polling Unit Agent
- Ward Collation Agent

Use simulated data only. Do not connect live election feeds or production electoral systems during this phase.

## Rules
- Preserve approved user workflows and labels from the product specification.
- Do not invent missing electoral form fields.
- Keep Polling Unit Agent and Ward Collation Agent workflows separate.
- Prefer reusable components for navigation, status cards, forms, evidence uploads, tables, and confirmation states.
- Prioritize responsive, mobile-first UI.
- Use a professional enterprise/government-grade design system.
- Clearly label simulated/prototype information.
- Do not remove approved functionality when adding new functionality.
- When requirements are ambiguous, preserve the known workflow and document the ambiguity.
- Run linting, type checking, and tests before completing implementation tasks.

## Development workflow
1. Read docs/product-specification.md and docs/user-flows.md before implementing.
2. Make the smallest coherent change that satisfies the task.
3. Add/update tests for meaningful behavior.
4. Run the available checks.
5. Update documentation when requirements change.
