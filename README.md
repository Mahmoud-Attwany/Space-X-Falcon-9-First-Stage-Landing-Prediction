# SpaceX Falcon 9 First Stage Landing Prediction

[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction)

This project predicts whether the first stage of a Falcon 9 rocket will land successfully. The core idea is to understand the factors that influence landing outcomes and how they affect launch costs.

SpaceX advertises Falcon 9 launches at **$62 million**, while other providers charge around **$165 million**. The key difference is **reusability**. By predicting landing success, we can better estimate the true cost efficiency of a launch – a valuable insight for competitors bidding on commercial contracts.

---

## Branches

The repository is organized into two main branches:

| Branch | Description |
|--------|-------------|
| [`Data`](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/tree/Data) | Contains the raw and processed datasets used throughout the analysis. |
| [`Notebooks`](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/tree/Notebooks) | Houses all Jupyter notebooks covering the complete pipeline – from data collection to machine learning. |

---

## Notebooks (in the `Notebooks` Branch)

The analysis is broken down into seven sequential notebooks:

1. **[Web Scraping (Wikipedia)](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/1_web_scraping_wikipedia.ipynb)**  
   Collects Falcon 9 and Falcon Heavy launch data from Wikipedia.

2. **[Data Collection (SpaceX API)](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/2_data_collection_spacex_api.ipynb)**  
   Retrieves structured launch data using the SpaceX REST API.

3. **[Data Wrangling & Labeling](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/3_data_wrangling_labeling.ipynb)**  
   Cleans and standardises the dataset, creating binary labels for landing success.

4. **[EDA with SQL](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/4_eda_sql.ipynb)**  
   Queries the data using SQL to uncover patterns and trends.

5. **[EDA with Visualisation & Feature Engineering](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/5_eda_visualization_feature_engineering.ipynb)**  
   Creates insightful plots with Matplotlib/Seaborn and engineers new features.

6. **[Geospatial Analysis with Folium](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/6_launch_sites_analysis_folium.ipynb)**  
   Maps launch sites using Folium to examine geographic influences.

7. **[Machine Learning Prediction](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/7_machine_learning_prediction.ipynb)**  
   Builds and compares classification models (Logistic Regression, Decision Tree, SVM, KNN) to select the best predictor.

Additionally, a **[dashboard](https://github.com/Mahmoud-Attwany/Space-X-Falcon-9-First-Stage-Landing-Prediction/blob/Notebooks/dashboard_code.ipynb)** built with Dash (Plotly) provides an interactive visual analysis of the launch data.

---

## Tools & Libraries

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Folium, Scikit‑learn)
- **SQL** (via SQLite)
- **Dash** by Plotly (interactive dashboard)

---

## Presentation

A comprehensive **[project presentation](https://github.com/user-attachments/files/22897035/ds-capstone-Mahmoud.Attwany.pdf)** summarises the entire process – from data collection to final predictions and dashboard insights. 

---

## Author

**Mahmoud Attwany**  
Data Science Professional | IBM Certified  
- [GitHub](https://github.com/Mahmoud-Attwany)  
- [LinkedIn](https://linkedin.com/in/mahmoud-attwany)  
