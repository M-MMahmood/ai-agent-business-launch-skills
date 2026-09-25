# Business-Building Skills Library

Agent Skills for AI harnesses (Claude Code, Codex, and compatible tools) that guide an autonomous agent through starting and scaling a business, from ideation to exit.

This repository contains 12 phase-level skill files covering the complete business lifecycle: ideation, validation, strategy, finance and funding, legal and governance, brand and product, operations, marketing and sales, team and talent, launch, growth optimization, and scale and maturity. Each file is a standalone, loadable skill that an AI agent can use to execute that phase of building a business.

## Who this is for

- Founders using an AI coding/agent tool (Claude Code, Codex, or similar) to plan and execute a new business.
- Developers building AI agent products who need a structured, reusable skill set for business-building workflows.
- Consultants and operators who want a repeatable, documented framework for taking an idea to a scaled business.

## Repository structure

```text
business-building-skills/
├── README.md
├── LICENSE
├── AGENTS.md
├── llms.txt
├── skills/
│   ├── 01-ideation/01-Ideation.md
│   ├── 02-validation/02-Validation.md
│   ├── 03-strategy/03-Strategy.md
│   ├── 04-finance-and-funding/04-Finance-and-Funding.md
│   ├── 05-legal-risk-and-governance/05-Legal-Risk-and-Governance.md
│   ├── 06-brand-product-and-delivery/06-Brand-Product-and-Delivery.md
│   ├── 07-business-operations/07-Business-Operations.md
│   ├── 08-marketing-and-sales/08-Marketing-and-Sales.md
│   ├── 09-team-and-talent/09-Team-and-Talent.md
│   ├── 10-launch/10-Launch.md
│   ├── 11-optimize-and-grow/11-Optimize-and-Grow.md
│   └── 12-scale-and-maturity/12-Scale-and-Maturity.md
```

## Phase index

| Phase | File | What it does |
|---|---|---|
| 01 | [01-Ideation.md](skills/01-ideation/01-Ideation.md) | Generate, score, and select a founder-fit business opportunity. |
| 02 | [02-Validation.md](skills/02-validation/02-Validation.md) | Test customer demand and problem fit before spending on build-out. |
| 03 | [03-Strategy.md](skills/03-strategy/03-Strategy.md) | Define value proposition, business model, pricing, and go-to-market. |
| 04 | [04-Finance-and-Funding.md](skills/04-finance-and-funding/04-Finance-and-Funding.md) | Build the financial model, unit economics, and funding strategy. |
| 05 | [05-Legal-Risk-and-Governance.md](skills/05-legal-risk-and-governance/05-Legal-Risk-and-Governance.md) | Form the entity, register the business, and manage legal risk. |
| 06 | [06-Brand-Product-and-Delivery.md](skills/06-brand-product-and-delivery/06-Brand-Product-and-Delivery.md) | Build brand identity and a market-ready MVP or service delivery. |
| 07 | [07-Business-Operations.md](skills/07-business-operations/07-Business-Operations.md) | Stand up banking, bookkeeping, tooling, SOPs, and support systems. |
| 08 | [08-Marketing-and-Sales.md](skills/08-marketing-and-sales/08-Marketing-and-Sales.md) | Build demand generation, sales process, CRM, and launch campaign. |
| 09 | [09-Team-and-Talent.md](skills/09-team-and-talent/09-Team-and-Talent.md) | Define roles, hiring plan, compensation, and onboarding. |
| 10 | [10-Launch.md](skills/10-launch/10-Launch.md) | Run readiness review, beta/pilot, public launch, and retrospective. |
| 11 | [11-Optimize-and-Grow.md](skills/11-optimize-and-grow/11-Optimize-and-Grow.md) | Improve fit, funnel, pricing, and economics using real data. |
| 12 | [12-Scale-and-Maturity.md](skills/12-scale-and-maturity/12-Scale-and-Maturity.md) | Scale organization and operations; prepare for audit, M&A, or exit. |

## How to use these skills

### Claude Code
Copy any phase folder into `.claude/skills/` in your project, or reference the file path directly in a prompt. Claude Code loads the YAML frontmatter to decide when the skill applies and the Markdown body as execution instructions.

### Codex / ChatGPT
Place the skill folder alongside your project's `AGENTS.md`, or copy the relevant `SKILL.md`-equivalent content into a custom skill per the Codex skills documentation.

### Any other agent harness
Each file is plain Markdown with YAML frontmatter (`name`, `description`, `compatibility`, `metadata`). Any harness that supports the Agent Skills open format can load these files directly.

## Compatibility

- Claude Code
- OpenAI Codex / ChatGPT Agent Skills
- Any Agent Skills-compatible harness

## Contributing

Open an issue or pull request to propose a new skill, correct a phase, or add supporting references/templates under a skill's folder.

## License

Apache License 2.0. See [LICENSE](LICENSE).
