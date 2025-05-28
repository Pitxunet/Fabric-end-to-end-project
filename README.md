# Sustainable Energy for All – End-to-End Project in Microsoft Fabric
This project demonstrates a complete data analytics pipeline using Microsoft Fabric, built around the Sustainable Energy for All (SE4ALL) dataset from the World Bank.


## 🔗  Project Highlights

Data Ingestion: Automated retrieval from the World Bank Data360 API via Microsoft Fabric Pipelines.

Data Transformation: Cleaning, reshaping, and modeling in PySpark notebooks.

Data Modeling: Star schema with one fact table and five dimension tables.

Interactive Reporting: Fully interactive Power BI report built directly in Fabric (no Power BI Desktop required).


## 📁 Repository Contents

notebook/: Fabric notebook in .ipynb, .tex, and .html formats

csv/: Source files used to populate dimension tables

report/: .pbix and .pdf format of the Power BI report

metadata/: World Bank metadata PDF for SE4ALL

README.md: This project summary


## 📊 Report Pages Overview

Overview: Line chart with indicator evolution, KPIs on latest value and growth.

Comparative Insights (Page 2 & 3): Renewable energy capacity, financial flows, consumption composition.

Coverage Metrics (Page 4 & 5): Matrix and bar chart views of year/data availability, indicator filtering.


## ⚠ Limitations

Trial version limits calculated columns in the semantic model.

Default semantic models are rigid; use custom ones for flexibility.

Semantic model UI has limited formatting compared to Power BI Desktop.

📎 Related Links

🌐 [World Bank Data360 SE4ALL API](https://data360.worldbank.org/en/api?datasetid=WB_SE4ALL)

📘 Read the full project walkthrough — 

📈 [Live Power BI report](https://app.powerbi.com/reportEmbed?reportId=6c093c51-38d0-45bc-a5cf-ada257a7f33b&autoAuth=true&ctid=e5d15069-41a2-48be-a3f3-d7f52db16425)
