# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DONTHIREDDY MAHIMA REDDY

*INTERN ID*:CT08DF57

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH

*TASK-4*

# DESCRIPTION
# Retail Product Recommendation System

This project builds a **Recommendation System** using **item-based Collaborative Filtering** to suggest products to retail customers based on their past purchases. The system uses transactional data and calculates similarities between products to personalize recommendations.

# Project Objectives

- Build a recommendation model using **Collaborative Filtering**
- Generate top-N product suggestions for users
- Evaluate the performance using **RMSE** metric
- Deliver results in a **Jupyter Notebook** format

# Dataset

The dataset contains purchase history from an online retail store with the following key fields:

- `CustomerID` → Treated as `UserID`
- `StockCode` → Treated as `ProductID`
- `Quantity` and `UnitPrice` → Used to derive a **synthetic rating**

# Techniques Used

- **Item-Based Collaborative Filtering** using **Cosine Similarity**
- **User-Item Matrix** creation
- Evaluation using **Root Mean Squared Error (RMSE)**

# Recommendation Process

1. Cleaned and preprocessed the data
2. Calculated a synthetic rating: `Rating = Quantity × UnitPrice`
3. Built a user-item rating matrix
4. Computed item-item similarity
5. Recommended products for each user based on similarity scores
6. Evaluated performance using RMSE



# SAMPLE OUTPUT 

![Image](https://github.com/user-attachments/assets/d054ac4b-6150-4a0c-b325-def2b1e34c43)


