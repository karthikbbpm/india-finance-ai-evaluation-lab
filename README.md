# India Finance AI Evaluation Lab

A public portfolio of original, synthetic finance cases designed to test whether AI systems can reason accurately through Indian accounting, controllership, FP&A and assurance workflows.

## Why this repository exists

AI can draft a finance answer quickly, but professional-quality work requires more than fluent text. A strong answer must identify missing evidence, apply the correct accounting logic, calculate accurately, distinguish estimates from facts, and make review conditions explicit.

Each case includes:

1. A fictional business scenario and synthetic source data
2. A task that can be given to an AI model or finance candidate
3. A reviewed expected answer
4. A weighted evaluation rubric
5. Common failure modes and red flags
6. Explicit assumptions and escalation conditions

## Published cases

| Case | Topic | Primary capabilities tested | Status |
|---|---|---|---|
| [001](cases/001-ind-as-115-time-and-materials/case.md) | Ind AS 115 — time-and-materials services | Performance obligations, over-time recognition, variable consideration, contract assets and journal entries | Published |

## Evaluation philosophy

- **Evidence before confidence:** Unsupported certainty is penalised.
- **Calculations must reconcile:** Conclusions must trace to the supplied data.
- **Ambiguity must be surfaced:** Missing contract terms should trigger assumptions or review flags.
- **Accounting and billing are different:** Invoice timing does not by itself determine revenue timing.
- **Human review remains essential:** These cases are evaluation material, not automated accounting advice.

## Repository structure

- cases/ — individual evaluation cases
- Each case contains the scenario, task, expected answer, rubric and machine-readable data

## Data and confidentiality

All names, entities, contracts, amounts and operational facts are fictional and created solely for demonstration. No employer, client or customer information is used.

## Important limitation

This is an educational and professional-portfolio project. It is not legal, tax, audit or accounting advice. Users should consult the latest notified Indian Accounting Standards, applicable legislation and professional advisers before making decisions.

## Roadmap

Planned cases include project profitability, month-end accruals and deferrals, working-capital drawing power, receivables ageing, cash-flow forecasting and internal-audit action tracking.
