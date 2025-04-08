# 🚲 Bike-Sharing Demand Prediction

## 📌 Project Overview

Building a model to predict daily bike rental counts based on environmental and seasonal conditions.

## 🧩 Problem Statement

BoomBikes, a US-based bike-sharing provider, has faced a significant drop in revenue due to the COVID-19 pandemic. The company aims to understand the post-pandemic demand for shared bikes. The objective is to:

- Identify which variables significantly influence bike demand
- Build a model to predict demand and guide strategic decisions

## 🎯 Goal

Develop a predictive model to determine the significant factors influencing the demand for shared bikes. The model will assist management in crafting effective business strategies to meet customer demand.

## 📊 Data Source

- Dataset: `day.csv`

## 🛠 Tools Used

- Jupyter Notebook
- Python

## 🔧 Data Preparation Steps

- Data loading and initial inspection
- Handling missing values
- Data cleaning and formatting

## 📈 Data Analysis

Performed in a structured, business-aligned manner:

- Univariate analysis
- Bivariate analysis

## 🧠 Model Building

- Target variable: `cnt` (total number of rentals, including casual and registered users)
- Built a regression model to predict `cnt`

## 🧪 Model Evaluation

```python
from sklearn.metrics import r2_score
r2_score(y_test, y_pred)
## 📌 Conclusion

- 🌸 **Spring** is the ideal season to expand business due to favorable weather and increased outdoor activities.
- 📆 **September** shows high demand — suitable for business promotions and growth initiatives.
- 🌧 **Light snow or rain** typically sees a dip in demand — can be leveraged for maintenance work.
- 📢 Post-pandemic, **launch promotional offers** especially in spring to attract more users.
- 🎯 **Advertise aggressively in September** to capitalize on high booking rates.