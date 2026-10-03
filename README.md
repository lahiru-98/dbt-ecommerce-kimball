# E-commerce Dimensional Model (Kimball) — dbt + BigQuery

Project 1 of my data modeling lab. Star schema built on the `thelook_ecommerce`
public dataset: requirements → bus matrix → dimensional model → dbt implementation → analytical queries.

## Status
🚧 In progress — Phase 1: requirements

## Structure
- `docs/` — requirements, source analysis, bus matrix, data model, ADRs
- `dbt/` — dbt project (staging → intermediate → marts)
- `queries/` — analytical SQL answering each business requirement
- `scripts/` — helper scripts