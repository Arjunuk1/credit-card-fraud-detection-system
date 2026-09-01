# Credit Card Fraud Detection System

A machine learning project designed to detect risky credit card behavior and predict whether a customer is likely to default on their payments. This project uses historical credit card data, applies data preprocessing and feature engineering, trains a predictive model, and exposes the result through an interactive web application.

The system is built to support financial decision-making by identifying customers with higher credit risk based on patterns in repayment history, spending behavior, balances, and demographic information.

---

## Overview

Credit card risk detection is a crucial problem in the financial industry. Banks and financial institutions need to evaluate whether a customer is likely to pay on time or whether they may default on future payments. Detecting such patterns early helps reduce financial losses, improve credit assessment, and support smarter lending decisions.

This project focuses on building an AI-based classification system that analyzes customer financial information and predicts the likelihood of default. The model learns from historical payment patterns and financial indicators to classify customers into risk categories.

The application uses a supervised machine learning approach, where the model is trained on labeled historical credit data and then used to predict outcomes for new customer profiles.

---

## What this project does

This project does the following:

- Analyzes customer credit data
- Identifies risky payment behavior
- Predicts whether a customer may default on payment
- Uses machine learning to classify credit risk
- Provides a simple interactive interface for real-time predictions
- Helps users understand how financial decisions can be supported with AI

In practical terms, the system helps answer questions such as:

- Will this customer likely default on their credit card payment?
- Does the customer’s payment history indicate financial stress?
- Is the customer’s credit usage within a safe range?
- What are the major indicators of risk in their profile?

---

## How it works

The project follows a standard machine learning pipeline:

### 1. Data Collection
The project uses a credit card dataset containing customer information such as:

- Credit limit
- Gender
- Education level
- Marital status
- Age
- Repayment status over recent months
- Bill amounts
- Payment amounts

These features provide important signals about a customer’s financial behavior and repayment capability.

### 2. Data Preprocessing
Before training the model, the data is cleaned and transformed:

- Missing or inconsistent values are handled
- Data types are checked and normalized
- Numeric columns are prepared for model input
- Categorical variables such as education and marital status are encoded
- Feature engineering is applied to improve model quality

This step ensures the dataset is suitable for machine learning algorithms.

### 3. Feature Selection
The model uses the most relevant financial and behavioral variables to make predictions. Important features include:

- Credit limit
- Payment status across previous months
- Bill statement amounts
- Previous payment amounts
- Customer profile attributes such as age, gender, and education

These variables help the model understand patterns associated with repayment risk.

### 4. Model Training
A classification algorithm is trained to learn the relationship between customer features and repayment outcomes. The model learns from historical examples where default behavior is known and uses that knowledge to classify new cases.

The main objective is to distinguish between:

- Low-risk customers
- High-risk customers likely to default

### 5. Model Evaluation
The trained model is evaluated using relevant classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

These metrics help determine how reliable the model is and how well it generalizes to unseen data.

### 6. Prediction
Once the model is trained and validated, it can be used to predict whether a new customer profile is likely to default.

The prediction process includes:

- Accepting user-entered financial information
- Formatting the data to match the model input
- Running the trained model
- Returning the prediction result

---

## Why this is useful

This type of system is valuable for:

- Banks and lending institutions
- Credit assessment teams
- Fintech applications
- Risk management departments
- Financial analytics and decision support

By identifying risky payment behavior early, institutions can make better-informed decisions about credit limits, loan approval, account monitoring, and customer outreach.

This reduces the risk of non-payment while supporting more efficient and data-driven financial operations.

---

## Tech Stack

This project is built using:

- Python
- Pandas
- Scikit-learn
- Pickle for model serialization
- Streamlit for the web interface

These technologies allow the project to be both easy to use and practical for real-world demonstration.

---

## Web Application

The project includes a Streamlit-based web app that gives users an interactive interface to enter customer data and receive a prediction.

The app allows users to provide inputs such as:

- Credit limit
- Gender
- Education
- Marital status
- Age
- Payment status for recent months
- Bill amounts
- Previous payment amounts

After entering the values, the app passes the data through the trained model and displays whether the customer is predicted to default or not.

This makes the project easy to demonstrate and understand, even for users who are not familiar with machine learning.

---

## Project Goals

The main goal of this project is to build a reliable AI-based credit risk prediction system that demonstrates how machine learning can be used in financial analytics.

The project aims to:

- Predict default risk using past customer behavior
- Show how AI supports financial decision-making
- Offer an end-to-end ML workflow from data to deployment
- Provide a practical deployment example using a Streamlit web app

---

## Real-World Impact

Credit risk prediction is one of the most important areas of applied machine learning in finance. Accurate prediction helps reduce bad debt, improve customer screening, and support stronger financial planning.

This project demonstrates a real-world application of AI in the banking and credit sector, showing how data science can influence decisions that affect both institutions and customers.

---

## Expected Outcome

After training, the system can classify a customer as:

- Likely to default
- Unlikely to default

This allows businesses and financial analysts to identify high-risk accounts and take action sooner.

---

## Conclusion

This project is a complete AI-powered credit card risk detection system that combines data analysis, machine learning, and a user-friendly interface to predict whether a customer may default on their credit payments.

It is a strong example of how machine learning can be used to solve real financial problems by analyzing historical behavior and identifying risk patterns. The project combines practical data science skills with a usable application that can be demonstrated in a business or academic setting.

---

## License

This project is available for educational and personal use. Please check the repository license for specific terms and conditions.