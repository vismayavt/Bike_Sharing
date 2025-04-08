# Bike-Sharing

### Predicting daily bike rental counts based on environmental and seasonal settings

---

## Problem Statement

BoomBikes, a US-based bike-sharing provider, has suffered a dip in revenues due to the COVID-19 pandemic. As the situation begins to normalize, the company wants to anticipate customer demand for bikes in a post-pandemic scenario.

**Key Business Questions:**
- Which variables are significant in predicting bike demand?
- How effectively can these variables describe changes in demand?

---

## Goal

To develop a predictive model that identifies the significant variables impacting daily bike rentals. This model will help management make informed decisions, adjust strategies, and meet customer expectations efficiently.

---

## Data Source

- Dataset: `day.csv` (provided)

---

## Tools Used

- Python  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## Data Preparation

Tasks performed in the initial stage:

- Data Loading and Inspection  
- Handling Missing Values  
- Data Cleaning and Formatting  

---

## Data Analysis

Exploratory Data Analysis performed to understand the relationships and patterns in the dataset:

- **Univariate Analysis**  
- **Bivariate Analysis**  

---

## Model Building

- Target Variable: `cnt` (Total number of bike rentals including casual and registered users)  
- Linear Regression model used to predict `cnt`  

---

## Model Evaluation

- Metric: **R-squared (R²) Score**  
- Evaluation Code:
  ```python
  from sklearn.metrics import r2_score
  r2_score(y_test, y_pred)
## Conclusion

- The company's growth strategy should focus on **expanding operations during spring**, capitalizing on favorable weather and increased outdoor activity.

- **September** shows a peak in demand — ideal for boosting **marketing and operations**.

- **Light snow or rain** results in **lower demand** — this time can be utilized for **bike servicing** without significantly affecting business.

- **Promotional offers** should be launched during the **spring season** to attract customers post-pandemic.

- **Significant Variables Affecting Bike Demand**:`holiday`,`temp`,`humidity`,`windspeed`,`season`,`month`,`year,``Sunday`,`weathersit`

---