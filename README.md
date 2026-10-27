# Awesome Data Agent Skills

Agent skills for data work in Claude Code and Codex, each tested on real data before it goes on this list.

We never copy a skill. Every entry links to the author's repo and gives the install command, so you install straight from the source.

## Data engineering

| Skill | Use it for | Author and license | Install | Field test |
| --- | --- | --- | --- | --- |
| [data-quality-frameworks](https://github.com/wshobson/agents/blob/main/plugins/data-engineering/skills/data-quality-frameworks/SKILL.md) | Planning data quality checks with Great Expectations, dbt tests and data contracts | [wshobson/agents](https://github.com/wshobson/agents) · MIT | `npx skills add https://github.com/wshobson/agents --skill data-quality-frameworks` | [GA4 data in BigQuery](data-engineering/data-quality-frameworks/): its own rules caught 4 of 9 issues |
| [bigquery-schema-design](https://github.com/justvinhhere/bigquery-expert/blob/main/skills/bigquery-schema-design/SKILL.md) | Designing BigQuery tables: partitioning, clustering, nested fields, table types, and data types | [justvinhhere/bigquery-expert](https://github.com/justvinhhere/bigquery-expert) · Apache-2.0 | `npx skills add https://github.com/justvinhhere/bigquery-expert --skill bigquery-schema-design` | [GA4 data in BigQuery](data-engineering/bigquery-schema-design/): its rules added 43 column descriptions, a date-and-time column, and 3-column sorting |

## Data analysis

No skills tested yet. See [`data-analysis/`](data-analysis/).

## How we test a skill

1. Install it from the author's repo.
2. Run it in Claude Code on a real table.
3. Write down what it caught, what it missed, and what it should improve.

Each field test sits in its role's folder, next to the skill it covers.

## Suggest a skill

Open an issue with a link to the skill's repo and the role it is for.
