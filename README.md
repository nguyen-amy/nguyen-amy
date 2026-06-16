## Amy Nguyen

Building end-to-end ML systems from data analysis and modeling
through deployment, monitoring, and iteration. My work is grounded in a strong
statistical foundation (B.S. Statistics & Data Science,
UCSB) and spent two years on longitudinal sleep research at Stanford.

Currently a Data Scientist at Candid, working on applied NLP and GenAI features
in production. M.S. in Data Science & Artificial Intelligence (University of
San Francisco).

### Selected Work

- **[Hikeability - Daily Trail Conditions Classifier](https://github.com/nguyen-amy/hikeability)**: End-to-end MLOps
  pipeline classifying 3,600+ trails daily with LLM summary of user reports. Scrapes user reports, calls weather API, and LLM for labelling and summary. Benchmarked six model/strategy combinations in MLflow and parallelized inference to cut catalog throughput from 5 hours to 88 minutes. *(MLflow, Flask, Docker, GCS, GitHub Actions, Vercel)*
- **[SF 311 Analysis - End-to-end Data Pipeline & ML System](https://github.com/nguyen-amy/SF-311-Data-Analysis)**: Daily Airflow DAG orchestrated pipeline, ingests millions of SF 311 records into MongoDB, processes with PySpark on GCS Parquet, and trains a Spark ML model to predict case resolution times. *(PySpark, MongoDB, Apache Airflow, GCP (GCS, Dataproc-style Spark jobs), Spark MLlib, MLflow, REST APIs, geospatial visualization, data pipeline design.)*
- **[Fantasy Football Faceoff](https://github.com/nguyen-amy/fantasy-football)**: Pipeline collects weekly NFL stats from the DataFeeds API and historical CSVs, stores in GCS, exposes a FastAPI service for retrieval and analysis, and (optionally) visualize via Streamlit to compare team and player stats with historical position performances. *(REST APIs, Docker, GCS, FastAPI, Streamlit)*
- **[BLOG: Understanding Binary Logistic Regression](https://nguyen-amy.github.io/linear-regression-final-project/)**
- **[Predicting Fitbit Sleep Scores](https://github.com/nguyen-amy/Fitbit-Sleep-Score-Prediction)**: Used personal smartwatch's sleep tracking data to create statistical models and implement machine learning algorithms to predict Fitbit Sleep Scores.
  *(Techniques: Lasso, ridge regression, random forests, k-fold CV, bagging, boosting)*

### Offline
- Snowboarder 🏂 
- Film photographer 📷
- Hiker + backpacker 🏔️🥾
- Home barista ☕️
