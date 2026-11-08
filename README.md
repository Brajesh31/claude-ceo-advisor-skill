# claude-ceo-advisor-skill

A Claude Code skill for executive decision-making, strategic planning, organizational leadership, financial scenarios, board governance, and stakeholder management.

## Overview

This skill supports leadership work that requires structured analysis and clear decisions. It helps frame strategic questions, evaluate options, model scenarios, prepare governance discussions, and communicate plans to stakeholders.

It is intended as decision support. Recommendations should be evaluated against the organization's actual financial, legal, operational, and market context.

## Main Capabilities

- Strategic position and opportunity analysis.
- Executive decision frameworks.
- Financial scenario modeling.
- Board governance preparation.
- Investor relations planning.
- Organizational culture and leadership development.
- Stakeholder communication.
- Strategic initiative prioritization.
- Risk and uncertainty assessment.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-ceo-advisor-skill.git ~/.claude/skills/ceo-advisor
```

The included analysis utilities require Python 3. Review their inputs and dependencies before execution.

## Usage

Invoke the skill for executive planning or decision support:

```text
/ceo-advisor
```

Provide the organization's stage, objectives, current constraints, financial assumptions, stakeholders, and the decision deadline.

## Reference Guide

| File | Purpose |
|---|---|
| `references/board_governance_investor_relations.md` | Governance and stakeholder topics |
| `references/executive_decision_framework.md` | Structured executive decisions |
| `references/leadership_organizational_culture.md` | Leadership and organizational culture |

## Analysis Utilities

The repository includes:

- `scripts/strategy_analyzer.py`: Structured strategic analysis.
- `scripts/financial_scenario_analyzer.py`: Financial scenario calculations.

Review each script's expected input format and assumptions before relying on its output.

## Recommended Workflow

1. Define the decision and the outcome it must support.
2. Separate known facts from assumptions.
3. Identify stakeholders and constraints.
4. Build realistic options, including the option to defer.
5. Compare financial, operational, and strategic implications.
6. Model scenarios and sensitivities where data supports them.
7. Identify risks, dependencies, and leading indicators.
8. Select measurable actions and owners.
9. Define a review date and decision triggers.
10. Communicate the rationale clearly.

## Executive Decision Checklist

- The problem is clearly defined.
- Assumptions are visible.
- Options are compared fairly.
- Financial inputs are explicit.
- Risks and second-order effects are considered.
- Stakeholder impact is understood.
- Actions have owners and deadlines.
- Success measures are defined.
- Uncertainty is not hidden behind false precision.

## Repository Contents

- `SKILL.md`: Main executive-advisory instructions.
- `references/`: Governance, decision, and leadership guidance.
- `scripts/`: Strategy and financial scenario utilities.
- `README.md`: Workflow and usage guidance.

## Important Note

This skill does not replace professional legal, financial, accounting, or governance advice. Validate important decisions with qualified people and current organizational data.
