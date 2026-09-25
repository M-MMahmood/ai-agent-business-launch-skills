# AGENTS.md

## Purpose

This repository is a library of Agent Skills for building a business end-to-end. Each skill in `skills/` corresponds to one phase of the business lifecycle: ideation, validation, strategy, finance and funding, legal and governance, brand and product, operations, marketing and sales, team and talent, launch, optimization and growth, and scale and maturity.

## How to work in this repository

- Each phase has exactly one skill file, located at `skills/<phase-folder>/<Phase-Name>.md`.
- Do not merge multiple phases into one file. Do not split a single phase into multiple files.
- Every skill file must retain the required YAML frontmatter fields: `name`, `description`, `license`, `compatibility`, `metadata`.
- The `description` field must state both what the skill does and when to use it, since agents route to skills based on this field.
- Keep the Markdown body sections consistent across all phase files: Objective, Use when, Do not use when, Prerequisites, Required inputs, Process (Plan/Do/Check/Act), Required research and evidence rules, Deliverable, Acceptance criteria, Handoffs, Risks and escalation.

## Editing conventions

- Use sentence-case headers.
- Cite external sources inline when adding market, legal, or financial claims.
- Do not present legal, tax, or licensed-financial guidance as final; flag such items for professional review, consistent with existing phase files.
- Preserve the "Handoffs" section in every file — it defines the dependency chain between phases.

## Testing changes

Before committing a change to any skill file:
1. Confirm the YAML frontmatter is valid (parses as YAML, has required fields).
2. Confirm all internal links (e.g., in `README.md`'s phase index) still resolve to the correct file path.
3. Confirm the phase's `metadata.phase` number matches its folder and filename numbering.
