# AI-Powered E-Commerce Customer Intelligence System

## Live Demo

🚀 Try the deployed application here:

**Streamlit App:** https://muhammad-shafiq-ur-rehman-e-commerce-analysis-ml-nl-main-syohfp.streamlit.app/

---
```
https://img.shields.io/badge/Python-3.10-blue
https://img.shields.io/badge/Streamlit-Deployed-red
https://img.shields.io/badge/Machine%20Learning-Project-success

## Project Overview

This project was developed for the Data Science Final Hackathon.

The solution combines:

- SQL Business Analytics
- Exploratory Data Analysis
- Customer Churn Prediction
- Deep Learning
- NLP Sentiment Analysis
- Streamlit Deployment

The application enables business users to analyze sales performance, predict customer churn, and classify customer reviews using machine learning.

---

## Project Components

### Database Cleaning

The SQLite database was inspected and cleaned by:

- Handling missing values
- Correcting invalid values
- Removing inconsistencies
- Standardizing text fields

---

### Business Analytics

SQL queries were used to calculate:

- Total Revenue
- Top Customers
- Category Revenue
- Monthly Revenue Trends
- Top Products

---

### Customer Churn Prediction

#### Models Trained

- Logistic Regression
- Random Forest
- Neural Network

#### Best Model

- Logistic Regression

#### Features Used

- Total Orders
- Total Spending
- Average Order Value
- Days Since Last Order
- Return Rate
- Average Delivery Days
- Age
- Membership Type

---

### NLP Sentiment Analysis

#### Review Sentiment Labels

- Rating 1-2 → Negative
- Rating 3 → Neutral
- Rating 4-5 → Positive

#### Model Used

- TF-IDF
- Logistic Regression

---

### Streamlit Application

#### Pages

1. Dashboard
2. Churn Prediction
3. Sentiment Analysis

---

## Business Insights

### Insight 1

Electronics generated the highest revenue and should be prioritized for inventory planning and marketing campaigns.

### Insight 2

Customers with longer inactivity periods were significantly more likely to churn, making purchase recency one of the strongest retention indicators.

### Insight 3

Some categories showed higher return rates than others, suggesting opportunities to improve product descriptions, product quality, or shipping processes.

---

## Installation & Local Setup

### 1. Clone the Repository

```
git clone https://github.com/Muhammad-Shafiq-Ur-Rehman/E-Commerce-Analysis-ML-NLP
cd YOUR_REPOSITORY

2. Create a Virtual Environment
 
python -m venv venv

3. Activate the Environment

Windows
venv\Scripts\activate

macOS/Linux
 
source venv/bin/activate

4. Install Dependencies

pip install -r requirements.txt

5. Run the Streamlit Application

streamlit run main.py

6. Open in Browser

http://localhost:8501

Tools & Technologies
Python
SQLite
Pandas
Scikit-Learn
TensorFlow
NLTK
Plotly
Streamlit


###Author

Muhammad Shafiq Ur Rehman

Bachelor's in Computer Engineering, Bahria University

Data Science Final Hackathon Submission

