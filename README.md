# Data Engineering Skill Validation

Agent skills for data work, each tried on real data before it goes on this list.

We never copy a skill. Every entry links to the author's repo and gives the install command, so you install straight from the source.

## Skills

| Skill | Use it for | Author and license | Install | Validation |
| --- | --- | --- | --- | --- |
| [data-quality-frameworks](https://github.com/wshobson/agents/blob/main/plugins/data-engineering/skills/data-quality-frameworks/SKILL.md) | Planning data quality checks with Great Expectations, dbt tests and data contracts | [wshobson/agents](https://github.com/wshobson/agents) · MIT | `npx skills add https://github.com/wshobson/agents --skill data-quality-frameworks` | [GA4 data in BigQuery](validations/data-quality-frameworks/): its own rules caught 4 of 9 issues |

## How we validate a skill

1. Install it from the author's repo.
2. Run it in Claude Code on a real table.
3. Write down what it caught, what it missed, and what it should improve.

Each result lives in [`validations/`](validations/).

## Suggest a skill

Open an issue with a link to the skill's repo.
