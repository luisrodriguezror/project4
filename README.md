# README Report for Consumer Behavior in E-Commerce - Dataset Analysis

## Introduction
This report dives into the world of consumer behavior in e-commerce. By using a variety of machine learning models, we've analyzed customer data to uncover patterns and predict future behaviors.

## Project Scenario
We've been hired by an online retailer in the US to help them ramp up their marketing campaigns and boost sales.

We started by diving into a dataset from the retailer, which includes personal info and purchase history. We'll look at how age, gender, and other demographics relate to what people buy, the category, and how much they spend. Plus, we'll explore how past purchases, payment methods, and shopping frequency play into the mix. This will help us spot patterns and trends to get a better grip on consumer behavior.

## Objective
The main objective of our analysis is to help the retailer make smarter marketing decisions. By analyzing current client patterns, we aim to optimize advertising spend and create personalized marketing strategies.

## Technologies and Tools Used
- Python Pandas
- Python Matplotlib
- Scikit-learn
- SQL Database
- Jupyter Notebook

## About the Dataset
Our Dataset with 3900 entries gives us a deep dive into customer preferences, tendencies, and patterns during their shopping experiences. It includes features like demographic info, purchase history, product preferences, shopping frequency, and more.

### Dataset Glossary
- **Customer ID**: Unique identifier for each customer.
- **Age**: Customer's age.
- **Gender**: Customer's gender.
- **Item Purchased**: Name of the item bought.
- **Category**: Category of the purchased item.
- **Purchase Amount (USD)**: Amount spent in USD.
- **Location**: Where the customer is located.
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
- **Frequency of Purchases**: How often the customer shops.

## Project Milestones
1. **Project Ideation**: Define the problem and objectives.
2. **Data Fetching**: Collect the dataset and preparation for analysis.
3. **Data Analysis**: Explore and clean the dataset.
4. **Building the ML Model**: Train a machine learning model to make predictions.
5. **Testing**: Evaluate the model's performance.
6. **Creating Documentation**: Document the process and findings.
7. **Creating the Presentation**: Prepare a presentation to showcase the project.

## Descriptive Machine Learning Model: K-Means Clustering
### Selected Features
To understand customer segments, we focused on:
- **Categorical**: Gender, Category, Location, Payment Method.
- **Numerical**: Age, Previous Purchases, Purchase Amount (USD).

### Cluster Analysis
We used K-means clustering to identify distinct customer segments. We defined a total of 4 clusters with distinctive customer preferences.

### Gender and Payment Method Distribution
We also examined how gender and payment methods were distributed across these clusters.

## Predictive Machine Learning Models
### 1. Random Forest Classifier: High-Spending Prediction Model
- **Goal**: Predict if a customer's purchase amount will exceed $85.
- **Accuracy**: 80%
- **Top Features**:
  1. Age (25%)
  2. Previous Purchases (23%)
  3. Gender (2%)
  4. Purchase Frequency (2%)
  5. Location (1%)

### 2. Neural Network Model: Purchased Category Prediction Model
- **Goal**: Predict the categories of products customers are likely to purchase.
- **First Attempt**: Achieved 100% accuracy, indicating possible overfitting.
- **Second Attempt**: Achieved more realistic results with varied accuracy across categories.

### 3. Neural Network Model: Purchased Item Prediction Model
- **Goal**: Predict specific items (e.g., Jewelry) customers are likely to purchase.
- **Result**: High accuracy with potential overfitting noted. More data needed for robust results.

### 4. Random Forest Classifier Model: Email Marketing Optimization
- **Goal**: Identify customers likely to use promo codes.
- **First Attempt**: Included features like age, gender, category, purchase amount, location, season, review rating, subscription status, previous purchases, and promo code usage.
- **Second Attempt**: Removed less important features (location, season, review rating), resulting in better recall (0.71) with slightly lower precision (0.85).

## Conclusions
- **Effectiveness of Models**: K-means clustering, neural networks, and random forest models provided valuable insights into customer behavior.
- **Marketing Optimization**: These models help optimize advertising spending, personalize customer experiences, and drive sales by predicting purchase preferences and promo code usage.
- **Importance of Data**: More data and additional features are crucial to improve model accuracy and avoid overfitting, better reflecting real customer behaviors.

## Recommendations
- **Expand Data**: Gather more customer data to enhance model training.
- **Evaluate Features**: Continuously evaluate and update features to improve model relevance and accuracy.
- **Regular Testing**: Regularly test and refine models to ensure they accurately predict customer behavior and support marketing strategy optimization.