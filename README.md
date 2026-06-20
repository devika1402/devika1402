<div align="center">

# Devika Rajasekar

[![Portfolio](https://img.shields.io/badge/Portfolio-devikabuilds.pages.dev-6C0820?style=for-the-badge&logo=safari&logoColor=white)](https://devikabuilds.pages.dev)
[![Blog](https://img.shields.io/badge/Blog-Read_the_notes-6C0820?style=for-the-badge&logo=rss&logoColor=white)](https://devikabuilds.pages.dev/notes/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-devikarajasekar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/devikarajasekar)

<br>
<img src="https://readme-typing-svg.demolab.com?font=DM+Mono&size=16&duration=3000&pause=1000&color=6C0820&center=true&vCenter=true&width=600&lines=Data+Engineering+%C3%97+Data+Science;Pipelines+that+hold+up%2C+models+you+can+trust;Python+%7C+dbt+%7C+Airflow+%7C+LightGBM+%7C+PyTorch" alt="Typing SVG" />
<br><br>


</div>

---
## Projects

### [The Edit: H&M Recommender](https://github.com/devika1402/the-edit)
`BigQuery` `CatBoost` `FastAPI` `Python`

It picks clothes for one shopper in two passes: a quick first pass narrows a hundred thousand items down to a few hundred that might suit them, and then a careful model puts the best twelve in order. It learns from 31 million H&M purchases. What I liked working on was keeping the list varied instead of piling on the same bestsellers everyone sees, and putting a number on what that variety costs in accuracy.

---

### [Two-Tower Movie Recommender](https://github.com/devika1402/free-lunch)
`PyTorch` `FAISS` `LightGBM` `Python` · [Writeup](https://devikabuilds.pages.dev/notes/free-lunch-multi-objective-ranking/)

It recommends movies in two passes: a model narrows 25 million ratings down to a short list, and then a ranker decides the final order. The bit I liked working on was letting us trade off how engaging the feed is against how varied it is, with a single dial we turn after training instead of one baked in.

---

### [Rossmann Store Sales Forecasting](https://github.com/devika1402/rossmann-sales-forecast)
`LightGBM` `Optuna` `statsforecast (MSTL)` `Python` · [Kaggle](https://www.kaggle.com/c/rossmann-store-sales)

It predicts six weeks of daily sales for over a thousand stores using one model instead of a big ensemble. Most of my time went into the features and into setting up the validation so the model never accidentally peeks at the future.

---

### [Workplace Safety Analytics Pipeline](https://github.com/devika1402/ehss-incident-intelligence)
`Apache Airflow` `dbt` `PostgreSQL` `Docker` `Ollama` `Pydantic` `GitHub Actions` `Python`

It takes 688,000 messy OSHA injury records and turns them into a clean database we can spin up with one command. A local language model reads the written incident reports and pulls out structured fields, and tests run on every push so the build breaks the moment the data does.

---

### [SHAP Stability Across the Rashomon Set](https://devikabuilds.pages.dev/notes/can-you-trust-a-shap-value/)
`AutoGluon` `H2O` `SHAP` `Python` · [Writeup](https://devikabuilds.pages.dev/notes/can-you-trust-a-shap-value/)

My thesis asks a simple question: if two models are equally accurate, do they actually agree on why they made their predictions? I found that whether they agree depends a lot more on how you searched for the models than on the data itself.

---

### [Multi-System Entity Resolution](https://github.com/devika1402/Multi-System-Customer-Data-Integration-Entity-Resolution)
`Python` `SQL` `Entity Resolution`

It merges customer records spread across Stripe, Salesforce, and NetSuite into one clean view. Working out which records across two million rows were actually the same person was the real challenge.

---

### [Lead Conversion Analytics](https://github.com/devika1402/lead-conversion-analytics)
`PostgreSQL` `Docker Compose` `Python` `Streamlit` `SQL`

It tracks how leads turn into paying members, with a database, an API, an ETL job, and a dashboard all running as separate containers. I built it more structured than it needed to be on purpose, just to practice wiring up a proper multi-service setup.

---

### [Biomedical NER with BioBERT](https://github.com/devika1402/ade-ner)
`PyTorch` `Hugging Face Transformers` `BioBERT` `Focal Loss`

It reads patient forum posts and pulls out mentions of bad drug reactions. Those mentions are rare, so I had to train the model in a way that stops it from just ignoring them to look accurate.

---

### [Fashion Sales Analyzer](https://github.com/devika1402/fashion-analyzer)
`PySpark` `Python`

It runs two Spark pipelines over a fashion dataset, one to spot trends and one to model a retail catalog. It was mostly me practicing the kind of code that would still hold up if the data got a lot bigger.

---

### [Energy Time-Series Forecasting](https://github.com/devika1402/energy-forecasting)
`ARIMA` `SARIMA` `Prophet` `Python`

It forecasts hydro power generation from about sixteen months of real data off India's power portal. I compared a few classic forecasting models, and SARIMA won, though cleaning the data well mattered more than the choice of model.

---

### [Graph Anonymization Study](https://github.com/devika1402/privacy-anonymization)
`Python` `Network Analysis`

It looks at how much we can scramble a social network to protect people's identities before we wreck the structure we wanted to study. I tested four ways of doing it across five real networks and watched where privacy and usefulness pull against each other.


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

<!-- <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devika1402&layout=compact&hide_border=true&title_color=6C0820&text_color=333333&bg_color=00000000&langs_count=6" />
<img height="150" src="https://github-readme-streak-stats.herokuapp.com?user=devika1402&hide_border=true&ring=6C0820&fire=F2AEBC&currStreakLabel=6C0820&sideLabels=5A86CB&dates=333333" /> -->

<img src="https://raw.githubusercontent.com/devika1402/devika1402/output/github-contribution-grid-snake.svg" alt="contribution snake" />

---

