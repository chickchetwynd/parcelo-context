# Parcelo context

Metric definitions for the **Parcelo** WisdomAI domain (proddemo), used as a
Context Builder → GitHub extraction source.

- `models/semantic/parcelo_metrics.yml`: 21 additional metrics in dbt
  semantic-layer format. Each metric's `meta.sql_expression` holds the exact
  Snowflake aggregate (database `PARCELO_POC`). Every expression was validated
  against live data on 2026-09-29.
- These complement, and don't redefine, the 24 metrics already in the domain.

Groups: adjustment/surcharge leakage, cost efficiency & shipment mix,
delivery performance, carrier selection, and marketplace.
