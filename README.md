# IBM Data Science Professional Certificate - Capstone Project

## 🚀 Predicting SpaceX Falcon 9 First Stage Landing Success

This repository contains my final capstone project for the **IBM Data Science Professional Certificate** on Coursera. The primary goal of this project is to predict whether the first stage of the SpaceX Falcon 9 rocket will land successfully.

By recovering and reusing the first stage, SpaceX can lower the cost of a launch from $165M to $62M. Predicting the success of a landing helps estimate the true cost of a launch and aids in competing for launch contracts.

---

## 🛠️ Project Methodology & Notebooks

This project follows a complete Data Science methodology, from data collection to predictive machine learning models. The notebooks have been sequentially ordered:

1. **`01_Data_Collection_API.ipynb`**: Extracted historical launch data using the official SpaceX REST API.
2. **`02_Web_Scraping.ipynb`**: Scraped and parsed additional Falcon 9 launch data from Wikipedia using BeautifulSoup.
3. **`03_EDA_with_SQL.ipynb`**: Queried launch records using SQL to extract key aggregated insights (e.g., maximum payload, first successful landings).
4. **`04_EDA_Data_Visualization.ipynb`**: Explored data relationships (Payload Mass vs. Launch Site, Success Rate vs. Orbit) using Matplotlib and Seaborn.
5. **`05_Interactive_Map_Folium.ipynb`**: Built interactive geographic maps using Folium to visualize launch sites and their proximity to coastlines and transportation infrastructure.
6. **`06_Machine_Learning_Prediction.ipynb`**: Developed and evaluated classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict landing outcomes.

---

## 🏆 Key Findings

- **Trend:** Landing success rates improved dramatically over time, peaking at 90% in 2019.
- **Geography:** All launch sites are strategically located near coastlines for safety and logistics. Launch site `KSC LC 39A` had the highest success ratio (77.3%).
- **Orbits:** Certain orbits like `ES-L1`, `GEO`, `HEO`, and `SSO` experienced 100% success in this dataset, while `GTO` was the most challenging (51.9%).
- **Machine Learning:** The **Decision Tree Classifier** was the best performing model, achieving a validation accuracy of **88.93%** and a test accuracy of **83.33%**.

---

## 💻 Technologies Used
- **Languages:** Python 3, SQL
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Folium, Plotly Dash, BeautifulSoup, Requests.

---
*This repository serves as the official submission for the Peer-Reviewed Capstone Project.*
