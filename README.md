# 🛒 AI-Powered E-Commerce Customer Intelligence System

An end-to-end data science and machine learning application developed for the **Data Science Final Hackathon**. It combines SQL business analytics, machine learning for customer churn, deep learning/NLP for review sentiment analysis, and an interactive Streamlit web dashboard.

---

## 🚀 Live Demo

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://muhammad-shafiq-ur-rehman-e-commerce-analysis-ml-nl-main-syohfp.streamlit.app/)

> **Try the deployed application:** [E-Commerce Intelligence Streamlit App](https://muhammad-shafiq-ur-rehman-e-commerce-analysis-ml-nl-main-syohfp.streamlit.app/)

![Python 3.10](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-success)

---

## 📌 Project Overview

This application empowers business users to analyze real-time sales performance, identify at-risk customers before they churn, and classify customer sentiment from reviews.

### Core Capabilities
* **SQL Business Analytics:** Database querying for revenue metrics, top products, and user trends.
* **Exploratory Data Analysis (EDA):** In-depth visual analysis of customer purchase behavior.
* **Customer Churn Prediction:** Machine Learning models to calculate churn probability.
* **NLP Sentiment Analysis:** Text classification for customer feedback.
* **Interactive Dashboard:** Deployed web interface built with Streamlit.

---

## 🛠 Project Components

### 1. Database Cleaning
The underlying SQLite database was systematically cleaned and sanitized by:
* Handling missing values and null entries.
* Correcting invalid numerical and text values.
* Removing duplicated record inconsistencies.
* Standardizing categorical text fields across datasets.

### 2. Business Analytics
Structured SQL queries were executed to extract actionable KPIs:
* Total Revenue & Monthly Revenue Trends
* Top High-Value Customers
* Category-wise Revenue Breakdown
* Top-Performing Products

### 3. Customer Churn Prediction

| Category | Details |
| :--- | :--- |
| **Models Evaluated** | Logistic Regression, Random Forest, Neural Network |
| **Best Performing Model** | **Logistic Regression** |
| **Key Features** | Total Orders, Total Spending, Average Order Value, Days Since Last Order, Return Rate, Avg Delivery Days, Age, Membership Type |

### 4. NLP Sentiment Analysis

* **Sentiment Mapping:**
  * Rating 1–2 $\rightarrow$ **Negative**
  * Rating 3 $\rightarrow$ **Neutral**
  * Rating 4–5 $\rightarrow$ **Positive**
* **Model Pipeline:** TF-IDF Vectorizer + Logistic Regression

### 5. Streamlit Application Pages
1. **📊 Dashboard:** Key performance indicators and sales metrics.
2. **🔮 Churn Prediction:** Input customer metrics to predict churn probability.
3. **💬 Sentiment Analysis:** Real-time review classification and customer feedback breakdown.

---

## 💡 Business Insights

* ⚡ **Top Category Focus:** Electronics generated the highest overall revenue and should be prioritized for inventory planning and targeted marketing.
* ⏳ **Churn Trigger:** Customer inactivity duration was the strongest retention indicator—longer recency directly correlated with higher churn likelihood.
* 📦 **Product Returns:** Specific categories exhibited significantly higher return rates, pointing to potential discrepancies in product descriptions or shipping quality.

---

## ⚙️ Installation & Local Setup

### 1. Clone the Repository
```
git clone [https://github.com/Muhammad-Shafiq-Ur-Rehman/E-Commerce-Analysis-ML-NLP.git](https://github.com/Muhammad-Shafiq-Ur-Rehman/E-Commerce-Analysis-ML-NLP.git)
cd E-Commerce-Analysis-ML-NLP

2. Create and Activate Virtual Environment

# Create environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS / Linux
source venv/bin/activate
3. Install Dependencies

pip install -r requirements.txt
4. Run the Streamlit Application

streamlit run main.py
5. Open in Browser
Navigate to http://localhost:8501 in your browser.

🧰 Tools & Technologies
Language: Python 3.10

Database: SQLite

Data Processing & Analytics: Pandas, NumPy

Machine Learning & Deep Learning: Scikit-Learn, TensorFlow, NLTK

Visualization & Web App: Plotly, Streamlit

👤 Author
Muhammad Shafiq Ur Rehman

Bachelor's in Computer Engineering, Bahria University

Data Science Final Hackathon Submission