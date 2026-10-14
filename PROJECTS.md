# Projects

Two kinds of work are listed here:

- **Open source:** code is public and runnable.
- **Professional work:** delivered in client or employer engagements. Described at a high level only; the code, data, and client details are proprietary and not available.

---

## Open source

| Project | Summary |
|---|---|
| [**Grounded Analytics Agent**](https://github.com/BagoesSuryoNugroho/grounded-analytics-agent) | Agentic analytics that returns defensible answers. Every result is a Claim with lineage, assumptions, statistical caveats, and a confidence level. LangGraph, deterministic SQL and statistics, Claude on Bedrock, Arize Phoenix tracing. 15/15 on a four-dimension golden set. |

---

## Professional work

### Enterprise agentic AI platform (2026)
Proof of concept for building and managing multi-agent systems, designed for integration with enterprise ERP in industrial operations.
- Ran a specification-driven workflow with OpenSpec: proposal, architecture design, and validation under team review.
- Built a versioning and deployment lifecycle for LangGraph-based agents: state snapshots, diff analysis, and staged promotion.
- Added observability with Langfuse and connected agents to enterprise data stores and tools through the Model Context Protocol (MCP).

**Stack:** LangGraph, Langfuse, MCP, OpenSpec

### Application security platform with AI-assisted remediation (2025)
Requirements analysis and proof-of-concept evaluation of security tooling for secure software development.
- Designed an on-premise platform combining static application security testing (SAST) and software composition analysis (SCA).
- Added AI-generated remediation code to improve developer productivity in large, mission-critical systems.

**Stack:** SAST, SCA, LLM-based code remediation

### AI-based product recommender (2024)
Reinforcement-learning product personalization for a telecommunications operator at 100M+ user scale.
- Implemented contextual multi-armed bandits based on MABWiser (Strong, Kleynhans, Kadıoğlu, 2021).
- Operationalized the model inside the enterprise MLOps platform, with automated randomized experiments and contextual learning.
- Improved customer conversion rates, measured through the randomized experiments.

**Stack:** Reinforcement learning, MABWiser, Python, Spark, MLflow

### MLOps platform on an open-source stack (2024)
Platform built from scratch to automate and standardize the machine learning lifecycle for a telecommunications operator.
- Developed on open-source components: Kubeflow and Airflow for pipeline orchestration, MLflow for tracking and model registry, Feast for features, Evidently for monitoring, Argo Workflows for CI/CD, and Spark on Kubernetes.
- Applied across 60+ data science and AI use cases: predictive modeling, user profiling, text processing, and product recommendation.
- Automated data and ML engineering pipelines, with up to 2,400% faster processing than the original process.

**Stack:** Kubeflow, Airflow, MLflow, Feast, Evidently, Argo Workflows, Spark, Docker, Kubernetes

### Telco location intelligence (2023)
Large-scale mobility analytics using geospatial AI on anonymized internet activity data, at national scale.
- Modeled population movement patterns and combined the outputs with OpenStreetMap and spatial infrastructure layers.
- Enriched mobility models with demographic attributes to surface mobility differences and inform network planning and location-based services.

**Stack:** Geospatial AI, OpenStreetMap, Spark

### Sentiment analysis on economic sanctions activity (2024)
Public-opinion analysis of boycott and sanctions discussion on social media.
- Collected and processed nearly 100,000 tweets over six months.
- Applied Transformer and BERT models for sentiment classification.
- Used NetworkX to map the social network, identify key influencers, and trace how sentiment spreads.
- Produced reports and visualizations for stakeholders.

**Stack:** BERT, Transformers, NetworkX, Python

### Data Science Indonesia: Data Science & AI/ML Playground (2023)
Indonesia's first open-access data science playground, built through the community I help lead.
- Delivered exploratory projects across transportation, energy, and disaster management.
- Partnered with 70+ organizations for datasets, compute, and domain expertise.

**Community:** [Data Science Indonesia](https://www.datascience.or.id/)

### Enterprise logistics data warehouse (2021)
Centralized data warehouse and data lake for a national logistics company.
- Integrated 11+ data sources across AWS, GCP, CRM, and ERP systems.
- Built automated ETL pipelines in Python and Pentaho with a near real-time refresh cycle.
- Enabled analytics for forecasting, SLA performance, route optimization, and monitoring across 7,000+ agent locations.

**Stack:** Python, Pentaho, AWS Redshift, GCP

---

<sub>Professional work is summarized from my own role in each engagement. Client names, internal systems, and business figures are intentionally omitted.</sub>
