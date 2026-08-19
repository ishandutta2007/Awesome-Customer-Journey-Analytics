# Awesome-Customer-Journey-Analytics

┌─────────────────────────────────┐
                    │        Customer Touchpoints      │
                    │ Web / Mobile / Product / Email  │
                    │ Ads / Support / Offline / IoT   │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │       Event Collection           │
                    │ Snowplow / RudderStack /        │
                    │ PostHog / Custom SDKs            │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │        Event Streaming           │
                    │ Kafka / Flink / Kafka Connect   │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │        Data Warehouse            │
                    │ ClickHouse / PostgreSQL /       │
                    │ DuckDB / BigQuery / Snowflake   │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │      Identity & Transformation   │
                    │ dbt / Airbyte / Spark /          │
                    │ Customer Identity Resolution     │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
              ┌─────────────────────┴─────────────────────┐
              │                                           │
              ▼                                           ▼
 ┌───────────────────────────┐             ┌───────────────────────────┐
 │   Behavioral Analytics    │             │      Session Replay        │
 │ PostHog / Matomo /        │             │ OpenReplay / rrweb         │
 │ Countly / Umami           │             │                           │
 └──────────────┬────────────┘             └──────────────┬────────────┘
                │                                         │
                └──────────────────┬──────────────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────────┐
                    │      Journey Intelligence       │
                    │ Funnels / Paths / Cohorts /    │
                    │ Retention / Segmentation /     │
                    │ Conversion / Friction           │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │       Visualization & BI         │
                    │ Grafana / Superset / Metabase   │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │     Experimentation & Action     │
                    │ GrowthBook / Unleash /          │
                    │ Flagsmith / Personalization     │
                    └─────────────────────────────────┘
