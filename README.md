# Consumer Behavior and Shopping Habits Analysis

## Project Overview
This project is all about understanding how people shop and what they buy, using some smart machine learning techniques. By diving into the Consumer Behavior and Shopping Habits Dataset, we can find out what customers like, their shopping habits, and patterns during their shopping experiences. We'll use tools like Python Pandas, Python Matplotlib, Scikit-learn, and more to clean, analyze, and visualize the data, and ultimately build a machine learning model to make predictions based on what we find.

## Project
We were hired by an online retailer in the US to help improve their marketing campaigns and boost their sales. Our job is to analyze consumer behavior, predict what items and categories they might buy, and see if we can forecast high-value purchases.

We'll start by looking at a dataset from the retailer, which includes personal information and purchase history. We'll check out how things like age and gender relate to what people buy, the category of the item, and how much they spend. We’ll also look at how factors like location, size, color, season, and review ratings affect buying behavior. Plus, we'll see how subscription status, shipping type, discounts, promo codes, previous purchases, payment methods, and how often they shop play into their purchasing decisions. This analysis will help us uncover patterns and trends to better understand consumer behavior.

## Problem Statement
The main goal is to use machine learning (ML) to solve, analyze, or visualize a problem with the provided dataset.

## Technologies and Tools Used
- Python Pandas
- Python Matplotlib
- Scikit-learn
- SQL Database
- Jupyter Notebook

## Dataset Description
The Consumer Behavior and Shopping Habits Dataset gives us a deep look into what customers like, their shopping tendencies, and patterns during their shopping experiences. It includes various features like demographic information, purchase history, product preferences, shopping frequency, and more.

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
2. **Data Fetching**: Collect the dataset and ensure it's ready for analysis.
3. **Data Analysis**: Explore and clean the dataset.
4. **Building the ML Model**: Train a machine learning model to make predictions.
5. **Testing**: Evaluate the model's performance.
6. **Creating Documentation**: Document the process and findings.
7. **Creating the Presentation**: Prepare a presentation to showcase the project.

### Exploration and Cleanup
- Explore the dataset to understand its structure and contents.
- Handle missing values, if any.
- Encode categorical variables and normalize numerical features.

### Analysis
- Perform various analyses like aggregation, correlation, comparison, and summary statistics.
- Visualize the data using plots to reveal insights and trends.

## Understanding the Problem

### Customer Segmentation
**How can we group customers based on their shopping behavior, demographics, and preferences to tailor marketing campaigns?**

- **Machine Learning Approach**: Clustering
  - Clustering is an unsupervised learning technique that groups similar data points together. In this case, customers are the data points, and their attributes (age, gender, purchase history, etc.) are the features.
    
  - **Preprocessing Steps**:
    - **Numerical Features**: Convert categorical features like gender and location into numerical representations (e.g., one-hot encoding).
    - **Feature Scaling**: Normalize numerical features to ensure they have a similar scale (e.g., standardization or min-max scaling).
    - **Feature Extraction**: Create new features that capture meaningful patterns (e.g., purchase frequency, average order value, purchase recency).

### Purchase Frequency and Amount Analysis
**How does purchase frequency and amount vary across different customer segments?**

## Model Training and Evaluation
- **Data Preparation**
- **Model Training**
- **Model Evaluation**

## Conclusions

### Customer Segmentation
- We used the K-Means algorithm to identify four distinct customer groups based on specific shopping behaviors. For instance, men and women around 43 years old with different purchase patterns and geographical locations. This allows for more effective marketing by targeting specific groups with common traits.

### High-Spending Predictive Models
- We developed a Random Forest model to predict if a customer will spend more than $85 in a purchase, achieving an 80% accuracy rate. Key factors were age and previous purchases, followed by gender and purchase frequency. This helps identify high-value customers for special offers and promotions.

### Neural Networks for Predicting Purchase Categories
- We tried predicting product categories customers would buy using a neural network. Initially, it showed 100% accuracy in 10 epochs, indicating overfitting. By excluding the purchased item and increasing the number of epochs, we achieved more realistic predictions for categories like accessories, footwear, and outerwear. This helps design more precise marketing campaigns.

### Neural Networks for Predicting Specific Items
- Another neural network model predicted specific items, like jewelry, without including the category. It showed high accuracy in a few epochs, suggesting possible overfitting. With more data, the model should maintain its accuracy over more epochs, helping personalize offers better.

### Email Marketing Optimization
- We used a RandomForestClassifier to identify customers likely to use promo codes. By refining variables (removing location, season, and review ratings), we improved the model's balance between precision and recall, maximizing the impact of promotions.

### Application of Results to Marketing Strategies
- The models and analyses provide a solid foundation for improving marketing strategies. Customer segmentation and purchase behavior prediction enable effective personalization, increasing campaign relevance and conversion rates. Identifying high-value customers and optimizing promo codes are key strategies derived from these analyses.

### Relevance of Additional Data
- To improve accuracy and avoid overfitting, more data and additional features are crucial. This helps train robust models that better reflect real customer behaviors, further optimizing marketing strategies.
