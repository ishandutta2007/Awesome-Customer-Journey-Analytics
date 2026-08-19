# Awesome-Customer-Journey-Analytics

### Top Customer Journey Analytics Tools Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**
*Focused on Customer Journey Analytics, Product Analytics, Digital Experience Analytics, Session Replay & Behavioral Analytics*
**Last updated: August 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Customer Journey Analytics (CJA)**. These tools help organizations understand how customers move across websites, mobile applications, products, campaigns, support channels, and other touchpoints — and identify friction, drop-offs, conversion opportunities, and behavioral patterns.

**Examples** include Contentsquare, Quantum Metric, Glassbox, Adobe Customer Journey Analytics, Amplitude, Mixpanel, Pendo, Heap, FullStory, Indicative, and other digital experience and product analytics platforms.

Customer Journey Analytics overlaps with **product analytics, digital experience analytics, web analytics, behavioral analytics, session replay, funnel analytics, path analysis, customer data platforms (CDPs), experimentation, conversion optimization, UX analytics, voice-of-customer, and marketing analytics**.

**Open-source emphasis**: This repository heavily emphasizes open-source software that can be self-hosted and adapted for custom analytics stacks. The open-source section includes product analytics platforms, web analytics, session replay, event tracking, customer data pipelines, behavioral analytics, funnel analysis, journey visualization, experimentation, and supporting data infrastructure.

Modern journey analytics increasingly combines **event streams + identity + session replay + funnels + paths + cohorts + segmentation + experimentation + qualitative context** to explain not only *what customers did*, but also *why they behaved that way*.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Additional Open-Source & Research Projects](#additional-open-source--research-projects)
* [Building a Custom Open-Source Customer Journey Analytics Stack](#building-a-custom-open-source-customer-journey-analytics-stack)
* [Important Customer Journey Analytics Concepts](#important-customer-journey-analytics-concepts)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Contentsquare](https://contentsquare.com/)** | Digital experience analytics platform providing journey analysis, session replay, heatmaps, funnels, mobile analytics, and experience monitoring. | Paid Growth plan starts at $39/month (billed annually) | Free forever plan includes up to 200,000 monthly sessions, session replays, heatmaps, funnels, and basic surveys (plus 15-day free trial of Growth plan) |
| **[Quantum Metric](https://www.quantummetric.com/)** | Enterprise digital analytics platform combining behavioral, product, and journey analytics with friction detection, session replay, and call-center data integration. | Enterprise contracts start at ~$40,000/year (Salesforce AppExchange add-on starts at $75,000/org/year) | No free tier; customized live product demos available upon request |
| **[Glassbox](https://www.glassbox.com/)** | Digital experience intelligence platform capturing web and mobile customer journeys, session replay, friction detection, and behavioral insights. | Enterprise contracts start at ~$10,000–$50,000/year | No free tier; personalized product consultations and interactive demos available upon request |
| **[Adobe Customer Journey Analytics](https://business.adobe.com/products/analytics/customer-journey-analytics.html)** | Enterprise omnichannel customer journey analytics built on Adobe Experience Platform (AEP) for cross-channel customer profile and interaction analysis. | Enterprise contracts start at ~$50,000–$100,000+/year (priced by data ingestion volume and AEP compute) | No free tier or self-serve trial; enterprise proof-of-concept and guided demos available via sales |
| **[Amplitude](https://amplitude.com/)** | Product and digital analytics platform providing behavioral analytics, funnels, journey paths, retention, cohorts, session replay, and experimentation. | Starter plan is $0/month; Plus plan starts at $0/month (scales with event volume above 2M events/mo) | Free forever plan includes up to 2,000,000 events/month, unlimited seats, session replay, core analytics, AI agents, and unlimited feature flags |
| **[Mixpanel](https://mixpanel.com/)** | Event-based product analytics platform for user flows, funnel analysis, cohort segmentation, retention, and product experimentation. | Free plan is $0/month; paid Growth plan starts at $0/month (first 1M events free, then scales with usage) | Free forever plan includes up to 1,000,000 events/month, 10,000 session replays/month, core analytics (insights, funnels, retention, flows), and 5 saved reports per seat |
| **[Pendo](https://www.pendo.io/)** | Product experience platform combining product analytics, user behavior analysis, in-app guides, onboarding, and NPS feedback. | Pendo Free is $0/month; paid Base plans start at ~$7,000/year (~$583/month) | Free forever plan includes up to 500 Monthly Active Users (MAUs), core analytics, and in-app guides; 30-day free trial available for full platform features |
| **[Heap](https://www.heap.io/)** | Digital insights and behavioral analytics platform featuring automatic event capture, journey mapping, funnels, and friction detection. | Free plan is $0/month; paid Growth plans start at ~$3,600/year (~$300/month) | Free forever plan includes up to 10,000 monthly sessions, charts, funnels, journey reports, and 6 months data history; 14-day free trial of paid tiers (no credit card required) |
| **[FullStory](https://www.fullstory.com/)** | Digital experience intelligence platform combining session replay, product analytics, journey mapping, and behavioral diagnostics. | FullstoryFree is $0/month; paid Business plans start at ~$299–$899/month (custom quote based on volume) | Free forever plan (FullstoryFree) includes up to 30,000 sessions/month, 10 user seats, 12 months data retention, and core session replay/analytics; 14-day free trial of paid plans |
| **[Indicative](https://www.indicative.com/)** | Customer journey analytics platform for multi-path journey mapping, funnel analysis, cohort tracking, and behavioral segmentation (acquired by mParticle). | Free plan is $0/month; paid Standard plans start at $249/month | Free forever plan includes up to 25,000,000 events/month, 3 users, 3 integrations, and 6 months data history; 14-day free trial of paid features |
| **[Google Analytics](https://marketingplatform.google.com/about/analytics/)** | Web and mobile app analytics platform providing acquisition, behavioral analysis, conversion tracking, audience journeys, and BigQuery export. | Free ($0/month standard version) | Free forever with standard limits (up to 14 months user data retention, standard reporting quotas; official demo account with live data available) |
| **[Google Analytics 360](https://marketingplatform.google.com/about/analytics-360/)** | Enterprise edition of Google Analytics providing higher event volume limits, unsampled reporting, advanced BigQuery export, SLAs, and enterprise support. | Starts at ~$50,000/year (covers up to 25 million monthly events) | No free tier; demo and sandbox environments available via Google Marketing Platform Sales Partners |
| **[Microsoft Clarity](https://clarity.microsoft.com/)** | Free behavioral analytics and session recording platform providing heatmaps, session replays, frustration signals (rage/dead clicks), and AI insights. | $0 (100% free forever, no paid tiers) | 100% free forever with unlimited sessions/traffic, unlimited websites, unlimited team seats, and 90-day recording retention |
| **[Hotjar](https://www.hotjar.com/)** | Product and experience analytics tool providing heatmaps, session recordings, conversion funnels, feedback widgets, and user interviews. | Free Basic is $0/month; paid Observe plans start at $39/month (billed annually) | Free forever Basic plan includes up to 35 daily sessions (1,050 sessions/month) and unlimited heatmaps; 15-day free trial of paid Business plans |
| **[Smartlook](https://www.smartlook.com/)** | Digital experience and session replay platform for web and mobile apps with funnels, heatmaps, event tracking, and anomaly detection (Cisco). | Free plan is $0/month; paid Pro plans start at $55/month | Free forever plan includes up to 3,000 monthly sessions and 1-month data retention; 30-day free trial of paid plans |
| **[Decibel](https://www.decibel.com/)** | Digital experience analytics technology scoring digital experiences (DXS), detecting friction, and providing session replays and journey heatmaps (Medallia). | Enterprise contracts start at ~$20,000/year (priced by Experience Data Records / EDR) | No free tier; personalized live product demo available upon request |
| **[Mouseflow](https://mouseflow.com/)** | Behavior analytics platform offering session replay, dynamic heatmaps, conversion funnels, form analytics, user feedback, and friction detection. | Free plan is $0/month; paid Essential plan starts at €25/month (~$27/month, billed annually) | Free forever plan includes up to 500 recordings/month for 1 website and 1 month storage; 14-day free trial of paid plans (no credit card required) |
| **[Lucky Orange](https://www.luckyorange.com/)** | Conversion rate and behavioral analytics suite featuring session recordings, heatmaps, conversion funnels, form analytics, and live chat. | Free plan is $0/month; paid Build plan starts at $32/month (billed annually) | Free forever plan includes up to 100 sessions/month for 1 site (30-day storage); 7-day free trial with full access to all features |
| **[Crazy Egg](https://www.crazyegg.com/)** | Website optimization and behavior analysis tool featuring heatmaps, scroll maps, session recordings, A/B testing, and traffic analysis. | Paid plans start at $29/month (billed annually); Instant Heatmaps feature is $0/month | 30-day free trial for all paid subscription plans; Instant Heatmaps tool is free forever with no credit card required |
| **[Woopra](https://www.woopra.com/)** | Customer journey analytics platform offering real-time user profiles, journey visualization, retention analysis, and automated triggers. | Core plan is $0/month; paid Pro plan starts at $999/month | Free forever Core plan includes up to 500,000 actions/month, 90-day data retention, and 30+ integrations; 14-day free trial of Pro plan |
| **[Kissmetrics](https://www.kissmetrics.io/)** | Person-based product and customer journey analytics platform focused on cohort analysis, funnels, user retention, and revenue attribution. | Free workspace is $0/month; paid plans start at $99/month | Free forever workspace includes up to 100,000 events/month, 3 seats, tracking, attribution, and 1 dashboard (no credit card required) |
| **[Countly](https://countly.com/)** | Product analytics and user engagement platform tracking customer journeys across web, mobile, desktop, and IoT devices. | Countly Flex Cloud starts at $175/month; self-hosted Lite edition is $0 (open source) | 14-day free trial for Countly Flex Cloud; self-hosted Countly Lite is free forever (community edition) |
| **[Plausible Analytics](https://plausible.io/)** | Lightweight, open-source, privacy-first web analytics platform providing essential traffic and goal conversion metrics without personal data tracking. | Hosted cloud starts at $9/month (up to 10,000 monthly pageviews); self-hosted is $0 (open source) | 30-day free trial with full features (no credit card required); self-hosted Community Edition is free forever |
| **[Matomo](https://matomo.org/)** | Privacy-centric web and digital analytics platform offering heatmaps, session recordings, funnels, goals, and custom reports. | Matomo Cloud starts at $23/month (up to 50,000 monthly hits); Matomo On-Premise is $0 (open source) | 21-day free trial for Matomo Cloud (no credit card required); self-hosted On-Premise version is free forever with no data limits |
| **[Snowplow](https://snowplow.io/)** | Behavioral data platform generating granular event streams for customer journey and product analytics. | Snowplow BDP Cloud starts at ~$1,500/month (managed pipeline); open-source edition is $0 | 14-day free trial of Snowplow BDP Cloud (full pipeline functionality, no credit card required); open-source pipeline is free forever self-hosted |
| **[mParticle](https://www.mparticle.com/)** | Customer Data Platform (CDP) providing data infrastructure, identity resolution, audience segmentation, and journey data activation. | Enterprise contracts start at ~$2,000–$5,000/month (~$25,000–$60,000/year based on mParticle Credits) | No permanent free tier; guided product demo and proof-of-concept trial available upon request |
| **[Segment](https://segment.com/)** | Customer data platform (CDP) for collecting, cleaning, and routing behavioral event streams to analytics, warehouse, and journey activation tools. | Free plan is $0/month; paid Team plan starts at $120/month (includes 10,000 MTUs) | Free forever plan includes up to 1,000 Monthly Tracked Users (MTUs), 2 sources, 700+ integrations, and 1 warehouse destination; 14-day free trial for Team plan |


## Open-Source GitHub Projects

* **[PostHog](https://github.com/PostHog/posthog)**
  One of the most comprehensive open-source product analytics ecosystems. Provides product analytics, web analytics, session replay, funnels, paths, retention, feature flags, experimentation, surveys, error tracking, and a data warehouse. PostHog supports self-hosting as well as its hosted platform.

* **[OpenReplay](https://github.com/openreplay/openreplay)**
  Open-source self-hostable session replay and product analytics platform. It captures user interactions together with network activity, console logs, JavaScript errors, application state, and performance information.

* **[Countly](https://github.com/countly/countly-server)**
  Open-source product analytics and engagement platform supporting customer behavior and journey analysis across web, mobile, IoT, and connected environments. The server is licensed under AGPL-3.0 with a modified Section 7.

* **[Matomo](https://github.com/matomo-org/matomo)**
  Open-source web analytics platform providing traffic analytics, events, goals, funnels, campaigns, user flows, and other behavioral analytics capabilities.

* **[PostHog JS Library](https://github.com/PostHog/posthog-js)**
  Open-source JavaScript SDK for capturing product and website events and feeding them into PostHog analytics.

* **[Snowplow](https://github.com/snowplow/snowplow)**
  Open-source event-tracking ecosystem for collecting granular behavioral data and building first-party customer journey analytics pipelines.

* **[Snowplow JavaScript Tracker](https://github.com/snowplow/snowplow-javascript-tracker)**
  Open-source JavaScript tracking library for collecting granular web interaction events.

* **[Snowplow Android Tracker](https://github.com/snowplow/snowplow-android-tracker)**
  Open-source Android event-tracking library for collecting mobile behavioral data.

* **[Snowplow iOS Tracker](https://github.com/snowplow/snowplow-ios-tracker)**
  Open-source iOS event-tracking library for capturing mobile customer interactions.

* **[Plausible Analytics](https://github.com/plausible/analytics)**
  Open-source privacy-friendly web analytics platform designed as a lightweight alternative to traditional analytics systems.

* **[Umami](https://github.com/umami-software/umami)**
  Open-source, privacy-focused web analytics platform with dashboards, events, sessions, campaigns, and website behavior analysis.

* **[Ackee](https://github.com/electerious/Ackee)**
  Self-hosted, privacy-focused analytics platform for websites providing visitor and event analytics.

* **[GoatCounter](https://github.com/arp242/goatcounter)**
  Open-source web analytics platform designed around simple, privacy-friendly website statistics.

* **[Shynet](https://github.com/milesmcc/shynet)**
  Self-hosted privacy-friendly web analytics platform supporting website traffic and behavioral analysis.

* **[Open Web Analytics](https://github.com/Open-Web-Analytics/owa)**
  Open-source web analytics framework providing page views, events, visitor tracking, and website behavior analysis.

* **[Fathom Lite](https://github.com/usefathom/fathom)**
  Open-source website analytics software designed for simple privacy-conscious traffic measurement.

* **[Pirsch Analytics](https://github.com/pirsch-analytics/pirsch)**
  Open-source, privacy-friendly web analytics platform with event tracking, goals, funnels, and dashboarding.

* **[GoAccess](https://github.com/allinurl/goaccess)**
  Open-source real-time web log analyzer useful for infrastructure-level traffic and behavioral analysis.

* **[Ackee Tracker](https://github.com/electerious/ackee-tracker)**
  Lightweight open-source tracking client for sending website analytics data to Ackee.

* **[PostHog Python](https://github.com/PostHog/posthog-python)**
  Open-source Python SDK for capturing backend events and associating them with customer and product behavior.

* **[PostHog Node](https://github.com/PostHog/posthog-js)**
  JavaScript ecosystem for instrumenting customer interactions and sending behavioral events to analytics infrastructure.

* **[OpenReplay Tracker](https://github.com/openreplay/openreplay)**
  Open-source instrumentation and replay infrastructure for capturing detailed customer interactions.

## Additional Open-Source & Research Projects

The following projects and ecosystems can complement dedicated customer journey analytics platforms.

### Product Analytics

* **[PostHog](https://github.com/PostHog/posthog)** — Product analytics, funnels, paths, retention, cohorts, experiments, and session replay.
* **[Countly](https://github.com/countly/countly-server)** — Product analytics and engagement.
* **[Matomo](https://github.com/matomo-org/matomo)** — Web and behavioral analytics.
* **[Umami](https://github.com/umami-software/umami)** — Lightweight privacy-focused analytics.
* **[Plausible](https://github.com/plausible/analytics)** — Privacy-first web analytics.
* **[Ackee](https://github.com/electerious/Ackee)** — Self-hosted website analytics.
* **[Pirsch](https://github.com/pirsch-analytics/pirsch)** — Privacy-friendly analytics with events and funnels.

### Session Replay & Experience Analytics

* **[OpenReplay](https://github.com/openreplay/openreplay)** — Open-source session replay.
* **[PostHog](https://github.com/PostHog/posthog)** — Session recordings integrated with product analytics.
* **[rrweb](https://github.com/rrweb-io/rrweb)** — Open-source web session-recording framework for recording and replaying DOM interactions.
* **[OpenReplay](https://github.com/openreplay/openreplay)** — Session replay with technical context including network activity and console information.
* **[LogRocket](https://github.com/)** — Commercial platform with session replay and behavioral debugging; useful as a conceptual reference for the category.

### Event Collection & Customer Data Infrastructure

* **[Snowplow](https://github.com/snowplow/snowplow)** — Granular event collection and behavioral data infrastructure.
* **[Segment](https://github.com/segmentio/analytics-next)** — Open-source client-side analytics/event collection components.
* **[RudderStack](https://github.com/rudderlabs/rudder-server)** — Open-source customer data infrastructure and event pipeline.
* **[PostHog](https://github.com/PostHog/posthog)** — Event collection combined with analytics.
* **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-specification)** — Open standard for telemetry that can complement behavioral and technical journey analysis.

### Customer Journey Data Processing

* **[Apache Kafka](https://github.com/apache/kafka)** — Event streaming infrastructure.
* **[Apache Flink](https://github.com/apache/flink)** — Real-time event processing.
* **[Apache Spark](https://github.com/apache/spark)** — Large-scale behavioral-data processing.
* **[DuckDB](https://github.com/duckdb/duckdb)** — Embedded analytical SQL engine useful for local journey analysis.
* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** — High-performance analytical database well suited to large event datasets.
* **[Trino](https://github.com/trinodb/trino)** — Distributed SQL query engine for querying behavioral data across multiple sources.
* **[Apache Druid](https://github.com/apache/druid)** — Real-time analytical database suitable for event and time-series analytics.

### Visualization & Exploration

* **[Grafana](https://github.com/grafana/grafana)** — Open-source visualization and analytics dashboards.
* **[Apache Superset](https://github.com/apache/superset)** — Open-source data visualization and BI platform.
* **[Metabase](https://github.com/metabase/metabase)** — Open-source business intelligence and analytics.
* **[Redash](https://github.com/getredash/redash)** — Open-source SQL-based analytics and visualization.
* **[Evidence](https://github.com/evidence-dev/evidence)** — Code-based BI and data applications.
* **[Lightdash](https://github.com/lightdash/lightdash)** — Open-source BI layer for analytics engineering stacks.

### Experimentation & Optimization

* **[GrowthBook](https://github.com/growthbook/growthbook)** — Open-source experimentation and feature-management platform.
* **[Flagsmith](https://github.com/Flagsmith/flagsmith)** — Open-source feature-flag and remote-configuration platform.
* **[Unleash](https://github.com/Unleash/unleash)** — Open-source feature management platform.
* **[PostHog](https://github.com/PostHog/posthog)** — Product analytics combined with experimentation and feature flags.
* **[Wasabi](https://github.com/)** — Open experimentation ecosystems can be connected to journey analytics pipelines for optimization workflows.

### Identity & Customer Data

* **[RudderStack](https://github.com/rudderlabs/rudder-server)** — Event collection and customer data infrastructure.
* **[Apache Kafka](https://github.com/apache/kafka)** — Streaming customer events.
* **[dbt-core](https://github.com/dbt-labs/dbt-core)** — Transforming raw behavioral events into analytics-ready customer datasets.
* **[Airbyte](https://github.com/airbytehq/airbyte)** — Open-source data integration for consolidating journey data.
* **[Meltano](https://github.com/meltano/meltano)** — Open-source ELT platform for building analytics pipelines.
* **[Dagster](https://github.com/dagster-io/dagster)** — Data orchestration for customer analytics pipelines.
* **[Apache Airflow](https://github.com/apache/airflow)** — Workflow orchestration for journey-data processing.

## Building a Custom Open-Source Customer Journey Analytics Stack

A production-oriented open-source journey analytics platform can be assembled from several layers:

```text
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
```

### Recommended Open-Source Combinations

**Lightweight Website Journey Analytics**

`Umami + rrweb + PostgreSQL + Metabase`

Suitable for smaller websites that need privacy-friendly analytics, basic behavioral analysis, and optional session replay.

**Product Analytics Stack**

`PostHog + ClickHouse + PostgreSQL`

A strong developer-oriented stack combining event analytics, funnels, paths, retention, cohorts, session replay, feature flags, and experimentation. PostHog itself provides many of these capabilities in one platform.

**Enterprise Behavioral Data Stack**

`Snowplow + Kafka + ClickHouse + dbt + Superset`

Useful for organizations wanting ownership of granular first-party event data while building customized journey analytics on top.

**Experience Analytics Stack**

`OpenReplay + PostHog + ClickHouse + Grafana`

Combines session replay with behavioral analytics, technical diagnostics, and customizable dashboards.

**Privacy-First Web Analytics Stack**

`Plausible + Matomo/Umami + PostgreSQL`

Suitable for organizations prioritizing first-party analytics and minimizing dependence on third-party tracking.

**Full Open-Source Customer Journey Analytics Architecture**

`Snowplow/RudderStack → Kafka → ClickHouse → dbt → PostHog/OpenReplay → Superset/Grafana → GrowthBook`

This architecture can reproduce many of the major functional layers found in commercial customer journey analytics platforms while retaining control over the underlying behavioral data.

## Important Customer Journey Analytics Concepts

A complete customer journey analytics system typically combines several capabilities:

* **Event Tracking** — Capturing clicks, page views, purchases, searches, feature interactions, and other customer actions.
* **Autocapture** — Automatically capturing interactions without requiring every event to be manually instrumented.
* **Session Tracking** — Grouping events into user sessions.
* **Identity Resolution** — Connecting activity across anonymous and identified users and multiple devices.
* **Customer Profiles** — Building unified behavioral profiles around customers or accounts.
* **Journey Mapping** — Visualizing sequences of interactions across digital and offline touchpoints.
* **Path Analysis** — Discovering the paths users take through a website or product.
* **Funnel Analysis** — Measuring conversion and drop-off between defined steps.
* **Retention Analysis** — Measuring whether users return and continue engaging with a product.
* **Cohort Analysis** — Comparing groups of customers based on shared characteristics or behaviors.
* **Segmentation** — Filtering users based on demographics, events, properties, or behavioral patterns.
* **Session Replay** — Replaying real customer sessions to understand actual behavior.
* **Heatmaps** — Visualizing clicks, scrolling, attention, and interaction density.
* **Rage Click Detection** — Identifying repeated interactions that may indicate frustration.
* **Dead Click Detection** — Identifying interactions that do not produce expected outcomes.
* **Friction Detection** — Finding UX problems that cause customers to struggle or abandon journeys.
* **Conversion Optimization** — Identifying opportunities to improve business outcomes.
* **Journey Orchestration** — Connecting analytics insights to actions across customer touchpoints.
* **Cross-Channel Analytics** — Connecting web, mobile, email, advertising, call center, CRM, and offline interactions.
* **Offline Data Integration** — Combining digital behavior with transactions, support interactions, and other offline events.
* **Customer Data Platform Integration** — Feeding behavioral data into broader customer-data infrastructure.
* **Real-Time Analytics** — Analyzing events as they happen.
* **Behavioral Anomaly Detection** — Identifying unusual changes in customer behavior.
* **Experience Monitoring** — Continuously monitoring critical customer journeys.
* **Session-Level Diagnostics** — Connecting aggregate analytics to individual customer sessions.
* **Product Analytics** — Understanding how customers use software products.
* **UX Analytics** — Measuring usability and identifying interaction problems.
* **Experimentation** — Testing changes to customer experiences.
* **Feature Flags** — Controlling feature exposure while measuring behavioral impact.
* **Personalization** — Using behavioral insights to tailor customer experiences.
* **Voice of Customer** — Combining quantitative behavior with qualitative feedback.
* **Customer Satisfaction Analysis** — Connecting behavioral journeys with satisfaction metrics.
* **Journey Attribution** — Understanding which interactions contribute to conversions or outcomes.
* **Customer Lifetime Value** — Connecting behavioral journeys to long-term economic value.
* **Predictive Analytics** — Predicting churn, conversion, purchase, or other customer outcomes.
* **AI-Assisted Analytics** — Using AI to query behavioral data, identify anomalies, summarize sessions, and surface insights.
* **Data Activation** — Sending analytics-derived audiences and signals into operational systems.
* **Privacy & Consent Management** — Managing tracking, consent, retention, and sensitive customer data appropriately.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow the existing format).
3. Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/hosted or open-source.
4. Prefer projects with active repositories and meaningful documentation.
5. For open-source projects, accurately identify the primary capability — product analytics, web analytics, session replay, event collection, journey analysis, experimentation, data infrastructure, or supporting analytics infrastructure.
6. Verify the project's current license before adding it.
7. Submit a PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated** list — not exhaustive and not an endorsement.
* Customer Journey Analytics overlaps significantly with product analytics, digital experience analytics, web analytics, session replay, CDPs, and business intelligence; some listed projects therefore provide supporting rather than complete journey-analytics functionality.
* Open-source, source-available, open-core, and hosted offerings are not equivalent. Always verify the current license and self-hosting terms before adoption.
* Some commercial platforms provide substantially broader enterprise capabilities than their open-source counterparts.
* Behavioral analytics may involve sensitive personal data. Organizations should implement appropriate consent, privacy, access-control, encryption, retention, and governance policies.
* Session replay should be configured carefully to prevent collection of passwords, payment information, health information, or other sensitive data.
* Analytics results can be affected by sampling, instrumentation quality, identity resolution, bot traffic, attribution models, and data-quality issues.

---

**Made for product managers, growth teams, UX researchers, digital analysts, data engineers, marketers, designers, and developers building customer-centric digital experiences.**
Let's make customer journey analytics more **open, privacy-conscious, scalable, and developer-friendly**.

