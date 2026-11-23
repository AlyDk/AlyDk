<h1 align="center">Hi, I'm Ali 👋</h1>

<p align="center">
  <b>Data Analyst moving into Analytics Engineering &nbsp;|&nbsp; dbt · Data Vault 2.0 · SAP HANA · Power BI · Python</b><br/>
  5 years building the data layer behind reporting: pipelines, models and tests, not just dashboards.
</p>

<p align="center">
  <a href="https://cutt.ly/ali-resume-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://alydk.github.io/erp-data-vault-dbt/"><img src="https://img.shields.io/badge/dbt%20Docs-FF694B?style=for-the-badge&logo=dbt&logoColor=white"/></a>
  <a href="https://cutt.ly/ali-resume-dsportfolio"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=githubpages&logoColor=white"/></a>
  <a href="https://cutt.ly/ali-resume-tableau"><img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/></a>
</p>

---

## What I do

I build the data layer that makes reporting possible & reliable.

That means extracting from ERP systems, modelling data so it keeps its history, testing it so the
numbers tie back to the source, and serving clean star schemas to Power BI. As the **sole analyst**
at an electronics distributor, I own everything from raw SAP HANA extracts to the executive dashboard.

- Replaced manual Excel workflows with automated SAP HANA to Power BI pipelines
- Built a central Power Query M function library so channel logic lives in one place across all fact tables
- Implemented Price-Volume-Mix decomposition with DAX text cards that write the executive summary for the current slicer context
- Built a Data Vault 2.0 warehouse in dbt with 81 automated tests and a daily scheduled pipeline (see below)

---

## Featured project

### [ERP sales and inventory warehouse on Data Vault 2.0](https://github.com/AlyDk/erp-data-vault-dbt)

[![daily-pipeline](https://github.com/AlyDk/erp-data-vault-dbt/actions/workflows/pipeline.yml/badge.svg)](https://github.com/AlyDk/erp-data-vault-dbt/actions/workflows/pipeline.yml)

ERP sales and inventory data (AdventureWorks) loaded through a Python bronze layer into a hand-written
Data Vault 2.0 model in dbt: 4 hubs, 3 links and 6 insert-only satellites that keep the full history
of every price, status and stock level. A star schema feeds a Power BI report saved as PBIP under
version control. GitHub Actions rebuilds and tests everything daily, and every run reconciles the
warehouse totals back to the ERP.

A small, focused showcase of the engineering behind reporting. The Power BI report is a thin layer
on top to show the marts in use; the pipeline, model and tests are the point.

**[Live dbt docs and lineage](https://alydk.github.io/erp-data-vault-dbt/)**

`dbt` `Data Vault 2.0` `DuckDB` `Python` `GitHub Actions` `Power BI` `ELT` `Data quality testing`

---

## Tech stack

**Data engineering**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**ERP and source systems**

![SAP HANA](https://img.shields.io/badge/SAP%20HANA-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![SAP B1](https://img.shields.io/badge/SAP%20Business%20One-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**BI and visualisation**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Power Query M](https://img.shields.io/badge/Power%20Query%20M-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel%20Advanced-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

---

## More projects

### Production work

**[Power BI Distribution Analytics](https://github.com/AlyDk/powerbi-dist-analytics)**
Star schema with three fact tables fed by SAP HANA native SQL, a central Power Query M function
library for channel classification, and 6 dashboard pages covering sales, open orders, inventory and
weekly sell-out. Includes a fix for the week-01 edge case that kept weekly data aligned across tables.
`SAP HANA` `Power Query M` `DAX` `Star Schema` `ETL`

**[Sales Performance Dashboard](https://github.com/AlyDk/sales-performance-dashboard)**
Price-Volume-Mix decomposition of the year-over-year sales change by category and channel, with
DAX-generated summary text, a budget vs actual tracker and a salesperson margin monitor.
`PVM Analysis` `DAX` `Power Query M` `Budget Tracking`

### Practice and learning

**[IBM HR Insights](https://github.com/AlyDk/ibm-hr-insights)**
Employee attrition analysis in Power BI on the IBM HR dataset.
`Power BI` `HR Analytics`

**[AdventureWorks Sales Analysis](https://github.com/AlyDk/AdventureWorks)**
Sales dashboard covering regional trends, customer segmentation and profit drivers.
`Power BI` `Sales Analytics`

**[Striker Performance](https://github.com/AlyDk/Striker-Performance)**
Football analytics measuring striker efficiency with Python.
`Python` `Sports Analytics`

---

<p align="center">
  Open to Analytics Engineer, Data Engineer and BI Engineer roles in Germany and the Netherlands.<br/>
  German B1 &nbsp;|&nbsp; Lived in Germany 4 years &nbsp;|&nbsp; Relocating with family
</p>
