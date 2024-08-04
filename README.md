# Consumer Behavior and Shopping Habits Analysis

## Project Overview
This project aims to analyze consumer behavior and shopping habits using machine learning techniques. By leveraging the Consumer Behavior and Shopping Habits Dataset, we will uncover insights into consumer preferences, tendencies, and patterns during their shopping experiences. The project will utilize various technologies, including Python Pandas, Python Matplotlib, Scikit-learn, and more, to clean, analyze, and visualize the data, ultimately building a machine learning model to make predictions based on the dataset.

## Project
An online retailer company that operates in the US hired us, a marketing company, to help them develop a strategy to improve their marketing campaigns and ultimately increase their sales.

The aim of our project is to predict whether a consumer will make a purchase or not. To perform the analysis, we’ll start by reviewing a dataset provided by the retailer company that includes customer personal information and purchase history.

We will examine relationships between customer demographics (such as age and gender) and purchase details (such as item purchased, category, and purchase amount). Additionally, we will analyze how location, size, color, season, and review rating influence purchase behavior. We will also explore the impact of subscription status, shipping type, discount applied, promo code usage, previous purchases, payment method, and frequency of purchases on the likelihood of making a purchase. This analysis will help us uncover patterns and trends to better understand consumer behavior.

## Problem Statement
The main objective is to solve, analyze, or visualize a problem using machine learning (ML) with the dataset provided. We aim to predict whether a customer will apply a discount code based on their shopping behavior.

## Technologies and Tools Used
- Python Pandas
- Python Matplotlib
- Scikit-learn
- SQL Database
- Jupyter Notebook

## Dataset Description
The Consumer Behavior and Shopping Habits Dataset provides comprehensive insights into consumers' preferences, tendencies, and patterns during their shopping experiences. It includes various features such as demographic information, purchase history, product preferences, shopping frequency, and more.

### Dataset Glossary
- **Customer ID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Gender**: Gender of the customer.
- **Item Purchased**: Name of the item purchased.
- **Category**: Category of the purchased item.
- **Purchase Amount (USD)**: Amount spent in USD.
- **Location**: Customer’s location.
- **Size**: Size of the purchased item.
- **Color**: Color of the purchased item.
- **Season**: Season during which the purchase was made.
- **Review Rating**: Rating given by the customer.
- **Subscription Status**: Whether the customer has a subscription.
- **Shipping Type**: Type of shipping selected.
- **Discount Applied**: Whether a discount was applied.
- **Promo Code Used**: Whether a promo code was used.
- **Previous Purchases**: Number of previous purchases by the customer.
- **Payment Method**: Payment method used.
- **Frequency of Purchases**: How often the customer makes purchases.

## Project Milestones
1. **Project Ideation**: Define the problem and objectives.
2. **Data Fetching/API Integration**: Collect the dataset and ensure it's ready for analysis.
3. **Data Analysis**: Explore and clean the dataset.
4. **Building the ML Model**: Train a machine learning model to make predictions.
5. **Testing**: Evaluate the model's performance.
6. **Creating Documentation**: Document the process and findings.
7. **Creating the Presentation**: Prepare a presentation to showcase the project.

## Data Cleanup and Analysis
The analysis process is divided into two broad phases: exploration and cleanup, and analysis.

### Exploration and Cleanup
- Explore the dataset to understand its structure and contents.
- Handle missing values, if any.
- Encode categorical variables and normalize numerical features.

### Analysis
- Perform various analyses such as aggregation, correlation, comparison, and summary statistics.
- Visualize the data using plots to reveal insights and trends.
- Build a logistic regression model to predict whether a customer will apply a discount code.

## Understanding the Problem

### Customer Segmentation
**How can we segment customers based on their purchasing behavior, demographics, and preferences to tailor marketing campaigns?**

- **Objective**: Group customers into distinct segments based on their purchasing behavior, demographics, and preferences. This segmentation will allow for tailored marketing campaigns that resonate with specific customer groups.
- **Machine Learning Approach**: Clustering
  - Clustering is an unsupervised learning technique that groups similar data points together. In this case, customers are the data points, and their attributes (age, gender, purchase history, etc.) are the features.
  - **Preprocessing Steps**:
    - **Numerical Features**: Convert categorical features like gender and location into numerical representations (e.g., one-hot encoding).
    - **Feature Scaling**: Normalize numerical features to ensure they have a similar scale (e.g., standardization or min-max scaling).
    - **Feature Extraction**: Create new features that capture meaningful patterns (e.g., purchase frequency, average order value, purchase recency).

### Customer Churn Prediction
**What factors influence customer churn? Can we predict which customers are likely to stop purchasing?**

### Product Popularity Analysis
**Which products are most popular in different regions or demographics?**

### Purchase Frequency and Amount Analysis
**How does purchase frequency and amount vary across different customer segments?**

## Model Training and Evaluation
- **Data Preparation**: Encode categorical variables and standardize numerical features.
- **Model Training**: Train a logistic regression model using Scikit-learn.
- **Model Evaluation**: Evaluate the model's performance using accuracy score and classification report.
