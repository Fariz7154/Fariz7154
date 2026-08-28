## Fariz Mohamed

**Data Engineer & Analyst — Dubai, UAE.** Five years across banking, telecom and
e-commerce in the UAE, the UK and India. Currently inside Mashreq Bank's data
governance function; previously engineering telecom-scale Spark pipelines at BT Group.

My work sits where the platform meets the audit trail — pipelines that hold up
under volume, and the profiling, reconciliation and lineage controls that let a
regulator, a finance team or a data scientist trust what comes out the other end.

[**Portfolio →**](https://fariz7154.github.io/) &nbsp;·&nbsp;
[LinkedIn](https://www.linkedin.com/in/fariz-mohamed-b028b4137/) &nbsp;·&nbsp;
farizmohd024@gmail.com

---

### Projects

Four repositories built around the problems that actually break data work in
practice — not the happy path. Each runs from a clone in under a minute,
and each carries the test that proves the hard part works.

| Project | What it does | The hard part |
|---|---|---|
| **[telecom-streaming-pipeline](https://github.com/Fariz7154/telecom-streaming-pipeline)** | Kafka → Spark Structured Streaming through a bronze/silver/gold medallion | Schema drift is *graded*, not just detected — a new column logs, a retyped column halts the run |
| **[banking-data-reconciliation](https://github.com/Fariz7154/banking-data-reconciliation)** | Declarative GL vs sub-ledger reconciliation, the control declared in YAML | Tolerances compare in decimal — one fils in binary floating point turns 325 rounding differences into 236 phantom breaks |
| **[incremental-elt-warehouse](https://github.com/Fariz7154/incremental-elt-warehouse)** | Star schema loaded incrementally: watermarks, SCD Type 2, idempotent facts | New dimension members open at the beginning of time — open them at load time and the whole fact table silently lands on Unknown |
| **[retail-metrics-layer](https://github.com/Fariz7154/retail-metrics-layer)** · [live dashboard](https://fariz7154.github.io/retail-metrics-layer/) | A tested metric layer over 1M real retail transactions, and the dashboard generated from it | The final month is partial — reported naively it shows revenue down 68%, a collapse that never happened |

Every record accounted for, every rejection explainable, every load repeatable,
every number traceable to the decision behind it. That is the through-line.

---

### What I work with

**Processing** &nbsp; Spark (Core, SQL, Streaming) · PySpark · Scala · Hadoop · Hive · Databricks
**Ingestion** &nbsp; Kafka · Azure Data Factory · NiFi
**Storage & modelling** &nbsp; Oracle · Azure Data Lake · Synapse · Snowflake · PostgreSQL · Star/Snowflake schema · SCD Type 2
**Analysis & BI** &nbsp; SQL · PL/SQL · Python · Pandas · Power BI · DAX
**Platform** &nbsp; Airflow · Azure DevOps · Docker · Git · Linux
**Governance** &nbsp; Data quality frameworks · reconciliation · lineage & metadata · MDM

---

### Background

**MSc Artificial Intelligence & Big Data** — Anglia Ruskin University, UK
**BE Information Technology** — Vellore Institute of Technology, India

Google Data Analytics Professional Certificate · Power BI · Advanced SQL · Advanced Python

---

<sub>Open to data engineering and analytics roles in the UAE.</sub>
