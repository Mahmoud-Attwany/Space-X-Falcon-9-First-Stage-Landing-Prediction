# SpaceX Falcon 9 Landing Prediction

## Overview
This project predicts whether the **Falcon 9 first stage** will land successfully.  
The goal is to understand the factors that influence landing outcomes and how they affect launch costs.

SpaceX advertises Falcon 9 rocket launches at **$62 million**, while other providers charge around **$165 million**.  
The main reason for this difference is **reusability**.  
If we can predict whether the first stage will land, we can estimate the **true cost efficiency** of a SpaceX launch.  
This analysis helps potential competitors estimate fair bids for commercial launches.

---

## Project Workflow
1. **Web Scraping (Notebook 1)**  
   Collected Falcon 9 and Falcon Heavy launch data from Wikipedia.

2. **Data Collection (Notebook 2)**  
   Used the SpaceX REST API to retrieve structured launch data.

3. **Data Wrangling and Labeling (Notebook 3)**  
   Cleaned and standardized the dataset.  
   Created labels for successful and unsuccessful landings.

4. **Exploratory Data Analysis with SQL (Notebook 4)**  
   Queried and explored the data using SQL to identify patterns.

5. **Exploratory Data Analysis with Visualization (Notebook 5)**  
   Visualized key relationships using Matplotlib and Seaborn.  
   Engineered new features from existing data.

6. **Geospatial Analysis (Notebook 6)**  
   Used **Folium** to map launch site locations and analyze geographic influence.

7. **Machine Learning Prediction (Notebook 7)**  
   Built classification models (Logistic Regression, Decision Tree, SVM, KNN).  
   Compared performance to select the best predictive model.

8. **Interactive Dashboard**  
   Created a **Dash** web application for visual analysis of launch data.

---

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Folium  
- Scikit-learn  
- SQL (via SQLite)  
- Dash (Plotly)

---

## Repository Structure
Space-X-Falcon-9-First-Stage-Landing-Prediction/

│
├── README.md
├── requirements.txt
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
│ ├── 1_web_scraping_wikipedia.ipynb
│ ├── 2_data_collection_spacex_api.ipynb
│ ├── 3_data_wrangling_labeling.ipynb
│ ├── 4_eda_sql.ipynb
│ ├── 5_eda_visualization_feature_engineering.ipynb
│ ├── 6_launch_sites_analysis_folium.ipynb
│ ├── 7_machine_learning_prediction.ipynb
│ └── dashboard_code.ipynb
├── src/
│ ├── data_collection.py
│ ├── data_cleaning.py
│ ├── feature_engineering.py
│ ├── model_training.py
│ └── dashboard_app.py
├── outputs/
│ ├── figures/
│ ├── models/
│ └── dashboard/
└── LICENSE


---

## Presentation
A project presentation summarizes the complete process — from data collection to final prediction and dashboard insights.

---

## Author
**Mahmoud Attwany**  
Data Science Professional | IBM Certified  
GitHub: [your-github-link]  
LinkedIn: [[Mahmoud Attwany LinkedIn](https://www.linkedin.com/in/mahmoud-attwany/)]
