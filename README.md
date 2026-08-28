<h3>Fariz Mohamed</h3>

**Data analyst · BI · data engineering.** I turn data into reporting people can
defend.

Five years across **banking, telecom and e-commerce** in the UAE, the UK and
India. Currently a Senior Analyst at Mashreq Bank in Dubai: Power BI for senior
stakeholders, SQL and PL/SQL over Oracle, profiling and reconciliation on
reporting datasets, and automating the reporting that used to be done by hand —
**40% less manual effort**. Before that, telecom-scale Spark and Kafka at BT Group.

What I care about is being able to say *why a number is what it is* — which source
it came from, which rule let it through, and what happened to the rows that did not
make it. A dashboard nobody can defend is worse than no dashboard.

I am an analyst who can build. The engineering means I can produce the dataset I
need rather than waiting in a queue for someone else to produce it.

**[fariz7154.github.io](https://fariz7154.github.io/)** · [LinkedIn](https://www.linkedin.com/in/fariz-mohamed-b028b4137/) · farizmohd024@gmail.com

---

### Open code

Four repositories about the problems that quietly ruin reporting — the metric
nobody agreed the definition of, the control everyone stopped trusting, the chart
that lies. 218 tests, CI green, each runs from a clone in under a minute.

<table>
<tr>
<td width="50%" valign="top">

**[retail-metrics-layer](https://github.com/Fariz7154/retail-metrics-layer)** · 77 tests · **[live dashboard](https://fariz7154.github.io/retail-metrics-layer/)**

Every number on a report is a decision before it is a number. Is postage revenue?
Each metric is defined once, in YAML, with its judgement calls attached — printed
beside the figure, not buried in a query. Cohorts, KPI trends, generated dashboard,
a million real transactions.

> The source stops mid-month, so the final period is partial. Reported the usual
> way it shows revenue down 68% — a collapse that never happened.

</td>
<td width="50%" valign="top">

**[banking-data-reconciliation](https://github.com/Fariz7154/banking-data-reconciliation)** · 79 tests

A declarative reconciliation engine — two datasets, the keys that tie them, the
tolerance they must agree within — with an exception report someone actually clears
from, and a trend that shows a control degrading before it breaches.

> Tolerances compare in decimal, not float. One fils in binary floating point turns
> 325 genuine rounding differences into 236 phantom breaks — which is how a control
> gets quietly ignored by whoever clears it each morning.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[incremental-elt-warehouse](https://github.com/Fariz7154/incremental-elt-warehouse)** · 39 tests

A star schema with SCD Type 2 history, so a record reclassified today does not
silently restate last quarter's report. Plus validation that the history is
well-formed after every load.

> New dimension members open at the beginning of time. Open them at load time and
> the entire fact table lands on Unknown while every integrity check still passes.

</td>
<td width="50%" valign="top">

**[telecom-streaming-pipeline](https://github.com/Fariz7154/telecom-streaming-pipeline)** · 23 tests

Where the numbers come from before anyone reports on them. Kafka into Spark through
a medallion, where nothing is dropped silently and every rejected record carries the
rules it broke.

> Schema drift is graded rather than merely detected — a new column logs, a retyped
> column halts the run.

</td>
</tr>
</table>

---

### Stack

| | |
|---|---|
| **Analysis & BI** | Power BI · DAX · SQL · PL/SQL · Power Query · Excel · Matplotlib · Seaborn |
| **Reporting automation** | Python · Pandas · NumPy · SQLAlchemy · VBA |
| **Data quality** | Reconciliation · profiling & EDA · quality rules · exception reporting · lineage |
| **Databases** | Oracle · PostgreSQL · SQL Server · MySQL · MongoDB · Snowflake |
| **Modelling** | Star & snowflake schema · SCD Type 2 · metric & KPI definition |
| **Engineering** | Spark · PySpark · Kafka · Azure Data Factory · Databricks · Hadoop · Airflow · Docker |

---

**MSc Artificial Intelligence & Big Data**, Anglia Ruskin University, UK ·
**BE Information Technology**, VIT, India ·
Google Data Analytics Professional Certificate

<sub>Open to data analyst, data engineer and BI roles. Dubai, UAE.</sub>
