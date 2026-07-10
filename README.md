# SalesSense-AI

AI-Powered Retail Analytics Dashboard using Machine Learning, Time Series Forecasting, Anomaly Detection, and Interactive Business Intelligence
---
### 📖 Project Overview

SalesSense AI is an end-to-end retail analytics solution designed to help businesses make data-driven decisions using historical sales data.

The system combines Machine Learning, Time Series Forecasting, Anomaly Detection, and Interactive Business Intelligence to forecast future sales, identify unusual sales behavior, analyze customer demand, and provide actionable business insights through an interactive Streamlit dashboard.

This project was developed as part of an AI & Data Science Internship.

---
### 🎯 Project Objectives

The primary objective of this project is to build an intelligent retail analytics platform capable of:

- 📊 Analyzing historical retail sales data
- 📈 Forecasting future sales demand
- 🤖 Comparing multiple Machine Learning forecasting models
- 🚨 Detecting unusual sales anomalies automatically
- 📦 Segmenting products based on demand
- 📉 Visualizing business insights using an interactive dashboard
- 💡 Supporting data-driven business decision making

---

### 🚀 Features

#### 📊 Sales Analytics
- Historical Sales Analysis
- Monthly Sales Trends
- Regional Performance Analysis
- Category-wise Sales
- Interactive Charts
---

#### 📈 Sales Forecasting
- Time-Series Forecasting
- Machine Learning Forecasting
- Multiple Model Comparison
- Best Model Selection
- 3-Month Sales Forecast
---

#### 🚨 Anomaly Detection
- Automatic Detection of Sales Anomalies
- Weekly Sales Monitoring
- Outlier Identification
- Business Event Detection

---
#### 📦 Demand Intelligence
- Product Demand Segmentation
- High / Medium / Low Demand Analysis
- Inventory Planning Support
- Business Recommendations
---
#### 📊 Interactive Dashboard

##### Built using Streamlit

###### Dashboard Pages:

- 🏠 Home
- 📊 Sales Overview
- 📈 Forecast Explorer
- 🚨 Anomaly Report
- 🎯 Demand Segments
- ℹ About
---
### 🏗 Project Workflow
```
 Retail Sales Dataset
           │
           ▼
     Data Cleaning
           │
           ▼
Exploratory Data Analysis (EDA)
           │
           ▼
   Feature Engineering
           │
           ▼
 Train Multiple Forecasting Models
           │
           ▼
    Model Evaluation
           │
           ▼
 Best Model Selection (XGBoost)
           │
           ▼
   Sales Forecasting
           │
           ▼
   Anomaly Detection
           │
           ▼
  Demand Segmentation
           │
           ▼
Interactive Streamlit Dashboard

```

### 🧠 Machine Learning Models Used

#### The following models were trained and evaluated:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Prophet (if used)
- Time Series Models (if applicable)
##### 🏆 Best Model

- XGBoost
---
#### Evaluation Metrics
 Metric | Value |
|------|------|
| `MAE` | 14,537.39 |
| `RMSE` | 17,093.03 |

---

### 📂 Dataset

#### Dataset contains retail sales information including:

- Order Date
- Ship Date
- Region
- Category
- Product
- Sales
- Quantity
- Discount
- Profit

#### The project performs:

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Date Parsing
- Feature Engineering
  
### 📈 Exploratory Data Analysis

#### The project includes:

- Monthly Sales Trend
- Yearly Sales Trend
- Region-wise Sales
- Category-wise Sales
- Profit Analysis
- Seasonal Analysis
- Weekly Sales Aggregation
- Monthly Sales Aggregation
---

### 🔮 Forecasting

#### The forecasting module:

- Builds multiple forecasting models
- Compares model performance
- Selects the best model
- Predicts future sales
- Supports 1–3 Month Forecast Horizon

---
### 🚨 Anomaly Detection

The dashboard identifies unusual sales patterns using Machine Learning.

#### Benefits:

- Detect unexpected sales spikes
- Detect sudden sales drops
- Identify unusual purchasing behavior
- Improve operational planning
---

### 📦 Product Demand Segmentation

 Products are grouped into:

#### 🟢 High Demand
- High inventory
- Frequent replenishment
- Priority stock management
#### 🟡 Medium Demand
- Balanced inventory
- Weekly monitoring
- Moderate replenishment
#### 🔴 Low Demand
- Limited inventory
- Reduce storage costs
- Promotional strategies
---

### 💻 Technology Stack
#### Programming Language
- Python
#### Data Analysis
- Pandas
- NumPy
#### Machine Learning
- Scikit-learn
- XGBoost
#### Visualization
- Plotly
- Matplotlib
#### Dashboard
- Streamlit
----

### ⚙ Installation

Clone the repository
---
    https://github.com/Subhrajyoti-Halder/SalesSense-AI/tree/main
---
#### Go to the project directory

- cd SalesSenseAI

#### Install dependencies

- pip install -r requirements.txt

#### Run the application

- streamlit run app.py
---

### 📊 Business Impact

 The system helps retail businesses to:

- Improve inventory planning
- Reduce stock shortages
- Minimize overstocking
- Forecast future sales
- Detect unusual business events
- Support strategic planning
- Improve supply chain decisions
---

### 🔮 Future Enhancements
- Deep Learning (LSTM) Forecasting
- Real-Time Sales Prediction
- Automatic Model Retraining
- Inventory Optimization
- Supplier Recommendation System
- Customer Segmentation
- Power BI Integration
- REST API Integration

---


###  Support

If you found this project useful:

- ⭐ Star this repository

- 🍴 Fork this repository

- 💡 Share your feedback



### Thank You!

#### SalesSense AI — Turning Retail Data into Business Intelligence
  
