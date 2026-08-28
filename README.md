<h3>Fariz Mohamed</h3>

**Banking data engineer, Dubai.** I build the pipelines a bank reports from, and
the controls that prove the numbers.

Currently a Senior Analyst at **Mashreq Bank**, inside the data governance
function — PL/SQL and Python over Oracle, across the regulatory, management and
financial reporting datasets that have to survive an audit. Before that,
telecom-scale Spark and Kafka at **BT Group**.

Inside a bank the pipeline is the easy half. The hard half is being able to say
*why a number is what it is* — which source it came from, which rule let it
through, and what happened to the rows that did not make it.

**[fariz7154.github.io](https://fariz7154.github.io/)** · [LinkedIn](https://www.linkedin.com/in/fariz-mohamed-b028b4137/) · farizmohd024@gmail.com

---

### Open code

Four repositories, 218 tests, CI green. Each runs from a clone in under a minute.
They are all built around the same idea: **the interesting engineering is in the
4% of records that go wrong**, not the 96% that behave.

<table>
<tr>
<td width="50%" valign="top">

**[banking-data-reconciliation](https://github.com/Fariz7154/banking-data-reconciliation)** · 79 tests

A declarative GL-versus-sub-ledger control. The reconciliation is YAML that
finance can sign off; the engine classifies every key and exits non-zero so the
scheduler stops a report that did not tie out.

> Tolerances compare in decimal, not float. One fils in binary floating point
> turns 325 genuine rounding differences into 236 phantom breaks — which is how
> a control gets quietly ignored by whoever clears it each morning.

</td>
<td width="50%" valign="top">

**[retail-metrics-layer](https://github.com/Fariz7154/retail-metrics-layer)** · 77 tests · **[live dashboard](https://fariz7154.github.io/retail-metrics-layer/)**

Every number on a report is a decision before it is a number. Each metric is
defined once, in YAML, with its judgement calls attached — and they are printed
beside the figure, not buried in a query.

> The source stops mid-month, so the final period is partial. Reported the usual
> way it shows revenue down 68% — a collapse that never happened.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[incremental-elt-warehouse](https://github.com/Fariz7154/incremental-elt-warehouse)** · 39 tests

A star schema loaded incrementally — watermarks with a lookback window, SCD Type
2 history, idempotent facts. The interesting part is the second and third load.

> New dimension members open at the beginning of time. Open them at load time and
> the entire fact table lands on Unknown while every integrity check still passes.

</td>
<td width="50%" valign="top">

**[telecom-streaming-pipeline](https://github.com/Fariz7154/telecom-streaming-pipeline)** · 23 tests

Kafka into Spark Structured Streaming through a medallion. Nothing is dropped
silently; every rejection carries the list of rules it broke.

> Schema drift is graded rather than merely detected — a new column logs, a
> retyped column halts the run.

</td>
</tr>
</table>

---

### Stack

| | |
|---|---|
| **Banking platform** | Oracle · PL/SQL · OFSAA · SQL Server · PostgreSQL |
| **Governance** | Reconciliation · data quality frameworks · lineage & metadata · MDM |
| **Processing** | Python · Spark · PySpark · Scala · Pandas · Hadoop · Databricks |
| **Pipelines** | Azure Data Factory · Kafka · Airflow · Azure DevOps · Git · Docker |
| **Modelling** | Star & snowflake schema · SCD Type 2 · Azure Data Lake · Synapse |
| **Reporting** | Power BI · DAX · Power Query · Excel |

---

**MSc Artificial Intelligence & Big Data**, Anglia Ruskin University, UK ·
**BE Information Technology**, VIT, India

<sub>Open to banking data roles in the UAE. Dubai · 30 days notice.</sub>
