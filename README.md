<div align="center">

# Devika Rajasekar

[![Portfolio](https://img.shields.io/badge/Portfolio-devikabuilds.pages.dev-6C0820?style=for-the-badge&logo=safari&logoColor=white)](https://devikabuilds.pages.dev)
[![Blog](https://img.shields.io/badge/Blog-Read_the_notes-6C0820?style=for-the-badge&logo=rss&logoColor=white)](https://devikabuilds.pages.dev/notes/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-devikarajasekar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/devikarajasekar)

<br>
<img src="https://readme-typing-svg.demolab.com?font=DM+Mono&size=16&duration=3000&pause=1000&color=6C0820&center=true&vCenter=true&width=600&lines=Data+Engineering+%C3%97+Data+Science;Python+%7C+SQL+%7C+dbt+%7C+Airflow+%7C+Databricks+%7C+Azure" alt="Typing SVG" />
<br><br>


</div>

---
## A few projects

### [paytrail: Payments Lakehouse](https://github.com/devika1402/paytrail)
`Databricks` `dbt` `Delta Lake` `Unity Catalog` `Azure` `SQL` `Python` · [Writeup](https://devikabuilds.pages.dev/notes/paytrail-payments-lakehouse/)

It turns 6.3 million synthetic payment transactions into a daily settled-volume report: read from Azure storage into a bronze/silver/gold lakehouse on Databricks, cleaned and reconciled in dbt, with Unity Catalog tracing every number back to the row it came from. What I focused on was the correctness a payments report needs, re-runs that never double-count and late transactions still counted in the right window, with bad rows quarantined for investigation.

---

### [Workplace Safety Analytics Pipeline](https://github.com/devika1402/workplace-safety-analysis)
`Apache Airflow` `dbt` `PostgreSQL` `Docker` `Ollama` `Pydantic` `GitHub Actions` `Python`

I worked with nearly 688,000+ workplace injury reports. Many of them contain written descriptions of what happened, so I built a system that organises the data and uses AI to read those descriptions and identify useful information, such as what may have contributed to the accident. I also checked how reliable the AI’s classifications were.

---

### [Rossmann Store Sales Forecasting](https://github.com/devika1402/rossmann-sales-forecast)
`LightGBM` `Optuna` `statsforecast (MSTL)` `Python` · [Kaggle](https://www.kaggle.com/c/rossmann-store-sales)

I built a model to predict future sales for more than 1,000 retail stores. It learns from things such as previous sales, promotions, holidays, and seasonal patterns. I then compared its predictions with simpler forecasting methods to check whether the more advanced model was better.

---

### [Authorised Push Payment Investigation](https://github.com/devika1402/authorised-push-payment)
`Python` `pandas` `NumPy` `scikit-learn` `XGBoost` `SciPy`

I built a system that looks at millions of transactions and helps decide which bank accounts should be investigated first for suspicious activity. Since an investigation team can only review a limited number of cases each day, the goal was to rank the accounts so that the most important cases appear at the top.

---

### [The Edit: H&M Recommender](https://github.com/devika1402/the-edit)
`BigQuery` `CatBoost` `FastAPI` `Python`

I built a personalised shopping system using about 31 million H&M purchases. For each shopper, it first reduces a catalogue of roughly 100,000 products to a few hundred sensible possibilities, then chooses the twelve most relevant items. I also wanted to avoid giving everyone the same popular clothes, so I added a way to make the recommendations more varied and measured how much prediction accuracy we give up as we increase that variety.

---

### [Two-Tower Movie Recommender](https://github.com/devika1402/free-lunch)
`PyTorch` `FAISS` `LightGBM` `Python` · [Writeup](https://devikabuilds.pages.dev/notes/free-lunch-multi-objective-ranking/)

I built a movie recommendation system using the MovieLens dataset of about 25 million ratings. It first finds a manageable set of films that seem relevant to a person and then decides which ones should appear at the top. The main question I explored was what happens when a recommendation system is asked to show people a broader mix of films instead of always choosing whatever is most likely to get engagement. I found that a small adjustment captured most of the possible increase in variety while reducing estimated engagement by less than 5%.

---


## Tools I have worked with (tbh, not updated)

```
Languages       Python · SQL · R
ML / DL         PyTorch · TensorFlow · Scikit-Learn · LightGBM · XGBoost · AutoGluon · H2O
NLP / Vision    Transformers · BioBERT · spaCy · OpenCV · U-Net
Data Eng        dbt · Databricks · Delta Lake · Apache Airflow · PySpark · Docker · Git · Qlik Sense
Databases       PostgreSQL
Cloud           AWS (S3, EC2) · Azure (ADLS Gen2) · Google Cloud Platform
Visualization   Power BI · Tableau · Matplotlib · Seaborn
```

---


## GitHub Activity

<!-- <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devika1402&layout=compact&hide_border=true&title_color=6C0820&text_color=333333&bg_color=00000000&langs_count=6" />
<img height="150" src="https://github-readme-streak-stats.herokuapp.com?user=devika1402&hide_border=true&ring=6C0820&fire=F2AEBC&currStreakLabel=6C0820&sideLabels=5A86CB&dates=333333" /> -->

<img src="https://raw.githubusercontent.com/devika1402/devika1402/output/github-contribution-grid-snake.svg" alt="contribution snake" />

---

