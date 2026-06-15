<div align="center">

# Devika Rajasekar

[![Portfolio](https://img.shields.io/badge/Portfolio-your--url.com-6C0820?style=for-the-badge&logo=safari&logoColor=white)](https://your-portfolio-url.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-devikarajasekar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/devikarajasekar)
![Profile Views](https://komarev.com/ghpvc/?username=devika1402&color=6C0820&style=for-the-badge&label=VIEWS)

<br>
<img src="https://readme-typing-svg.demolab.com?font=DM+Mono&size=16&duration=3000&pause=1000&color=6C0820&center=true&vCenter=true&width=600&lines=Data+Engineering+%7C+ML+%7C+Analytics;Python+%7C+dbt+%7C+Airflow+%7C+LightGBM+%7C+PyTorch" alt="Typing SVG" />
<br><br>

</div>

Data engineering, ML, and analytics projects. Professional context at [portfolio](https://your-portfolio-url.com) and [LinkedIn](https://linkedin.com/in/devikarajasekar).

---

## Projects

### [Rossmann Store Sales Forecasting](https://github.com/devika1402/rossmann-sales-forecast) — Top 5% of 3,738 Kaggle teams
`LightGBM` `Optuna` `statsforecast (MSTL)` `Python` · [Kaggle](https://www.kaggle.com/c/rossmann-store-sales)

Daily sales forecasting for 1,115 retail stores, six weeks ahead. Single LightGBM model with retail-aware feature engineering: date-aware Promo2 decoding, holiday-proximity ramps, 365-day lags, per-store trend aggregates. Walk-forward cross-validation matched to the test horizon with no future leakage. Result: 11.5% RMSPE, 67% better than a naive baseline.

---

### [EHS&S Incident Intelligence Pipeline](https://github.com/devika1402/ehss-incident-intelligence) — 688K+ records · 81 automated tests · CI on every push
`Apache Airflow` `dbt` `PostgreSQL` `Docker` `Ollama` `Pydantic` `GitHub Actions` `Python`

End-to-end batch pipeline ingesting 688K+ OSHA workplace injury records into a PostgreSQL star-schema warehouse (1 fact, 5 dimensions) with dbt, orchestrated by a 7-task Airflow DAG, runnable with a single `docker compose up`. LLM enrichment layer (locally hosted via Ollama, Pydantic-validated structured output, SHA-256 caching for idempotent reruns) classifies free-text incident narratives at 96.5% coverage for $0 inference cost. 50 dbt data-quality tests + 31 Python unit tests wired into GitHub Actions CI — build fails on any data contract violation.

---

### [Multi-System Entity Resolution](https://github.com/devika1402/Multi-System-Customer-Data-Integration-Entity-Resolution) — 98% FK mismatch resolution · ~2M rows
`Python` `SQL` `Entity Resolution`

Integrated fragmented CRM, ERP, and payment data from Stripe, Salesforce, and NetSuite. Designed entity-resolution workflows with ER diagrams and schema corrections, built rule-based matching logic, and resolved 98% of foreign key mismatches across roughly two million rows into a unified customer view.

---

### [Biomedical NER with BioBERT](https://github.com/devika1402/ade-ner) — rare-entity F1 from 0% to 21.5%
`PyTorch` `Hugging Face Transformers` `BioBERT` `Focal Loss`

Named entity recognition on the CSIRO Adverse Drug Event corpus (CADEC) for adverse drug reaction detection. Fine-tuned BioBERT with Focal Loss to handle severe class imbalance: overall accuracy 88.92%, F1 88.04%. Rare-entity recovery: B-Finding 0% to 21.51%, I-Disease 1.68% to 17.33%.

---

### [Lead Conversion Analytics](https://github.com/devika1402/lead-conversion-analytics)
`PostgreSQL` `Docker Compose` `Python` `Streamlit` `SQL`

Containerised data product in Docker Compose: Postgres database, REST API, ETL pipeline, and Streamlit dashboard as separate services. Relational schema for lead-to-member conversion, SQL queries tracking 4 revenue and sales KPIs through an interactive dashboard.

---

### [Fashion Sales Analyzer](https://github.com/devika1402/fashion-analyzer)
`PySpark` `Python`

Two PySpark analytical pipelines over a 10,000-record fashion dataset: a trend analyzer across 9 categories, 10 styles, 13 colors, 4 seasons, and 5 regions, and a retail-catalog pipeline modeled on fast-fashion product attributes. Spark window functions for top-N seasonal color ranking; outputs in JSON and CSV for downstream use.

---

### [Energy Time-Series Forecasting](https://github.com/devika1402/energy-forecasting)
`ARIMA` `SARIMA` `Prophet` `Python`

Hydro energy generation forecasting on 16 months of live data from India's National Power Portal. Model selection by AIC/BIC. Best result: SARIMA at RMSE 153.55, MAE 78.03.

---

### [Graph Anonymization Study](https://github.com/devika1402/privacy-anonymization)
`Python` `Network Analysis`

Evaluated 4 anonymization methods across 5 real-world graphs. Measured structural preservation (modularity shift <3%) and re-identification risk (<1%).

---

## Stack

```
Languages       Python · SQL · R
ML / DL         PyTorch · TensorFlow · Scikit-Learn · LightGBM · XGBoost · AutoGluon · H2O
NLP / Vision    Transformers · BioBERT · spaCy · OpenCV · U-Net
Data Eng        dbt · Apache Airflow · PySpark · Docker · Git · Qlik Sense
Databases       PostgreSQL
Cloud           AWS (S3, EC2) · Google Cloud Platform
Visualization   Power BI · Tableau · Matplotlib · Seaborn
```

---

## GitHub Activity

<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devika1402&layout=compact&hide_border=true&title_color=6C0820&text_color=333333&bg_color=00000000&langs_count=6" />
<img height="150" src="https://github-readme-streak-stats.herokuapp.com?user=devika1402&hide_border=true&ring=6C0820&fire=F2AEBC&currStreakLabel=6C0820&sideLabels=5A86CB&dates=333333" />

<img src="https://raw.githubusercontent.com/devika1402/devika1402/output/github-contribution-grid-snake.svg" alt="contribution snake" />

---

<div align="center">

📄 [Portfolio](https://your-portfolio-url.com) · 💼 [LinkedIn](https://linkedin.com/in/devikarajasekar)

</div>
