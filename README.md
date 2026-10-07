# Overview

This project focuses on **daily revenue forecasting** using historical sales, Cost of Goods Sold (COGS), and promotional campaign data. The objective is to build a machine learning pipeline that not only forecasts future revenue but also provides insights into the key factors influencing revenue performance.
The project uses **LightGBM (Light Gradient Boosting Machine)** as the primary forecasting model. Historical revenue and COGS data are combined with information on promotional campaigns to construct and enrich predictive features, such as **lag features, moving averages, rolling statistics, and promotion-related features**.

# Business Objectives 

The project aims to support data-driven revenue planning and business decision-making through the following objectives:
1. **Forecast future revenue**
Develop a machine learning model to forecast daily revenue based on historical sales performance, COGS, and promotional activities.
2. **Understand revenue drivers**
Identify the key factors associated with changes in revenue, including historical sales patterns, recent revenue trends, and promotional campaigns.
3. **Evaluate the impact of promotions**
Incorporate promotional campaign information into the forecasting process to understand how promotions contribute to revenue fluctuations.
4. **Improve business planning**
Provide reliable revenue forecasts that can support planning activities such as sales target setting, inventory planning, budgeting, and promotional strategy.
5. **Ensure model interpretability**
Apply SHAP to explain model predictions and identify the features that have the greatest influence on forecasted revenue, making the model more transparent and easier to interpret from a business perspective.

# Datasets 

The project uses two datasets:

| Dataset | Description |
|---------|-------------|
| sales | Daily sales and COGS records |
| promotions | Information about promotional campaigns taking place during the observation period |

# Installation Guide

## 1. Clone the repository

```bash
git clone https://github.com/klee528/Fuzzy-Factory-Ecommerce-Analytics.git
cd Fuzzy-Factory-Ecommerce-Analytics
```

## 2. Install the required packages

```bash
pip install -r requirements.txt
```

## 3. Run the project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
notebooks/sales_forecasting.ipynb
```

or run the notebook directly in Visual Studio Code.
