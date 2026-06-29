#  Food Product Feature Engineering and Exploratory Modeling

##  Project Overview

This project focuses on **Feature Engineering** and **Exploratory Modeling** using an Instant Noodles Reviews dataset. The objective is to clean the dataset, create meaningful features, analyze relationships between variables, visualize insights, and apply basic machine learning models for prediction and clustering.

The project was completed using **Python** in **Google Colab** as part of a Data Science learning project.

---

## Dataset

**Dataset:** Processed Food Reviews Dataset

The dataset contains information about instant noodle products, including:

- Review Number
- Brand
- Style
- Country
- Star Rating
- Top Ten Ranking

---

# Objectives

- Perform data cleaning
- Handle missing values
- Create new meaningful features
- Encode categorical variables
- Perform exploratory data analysis (EDA)
- Visualize relationships between variables
- Build simple machine learning models
- Save the engineered dataset

---

# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Feature Engineering

The following new features were created:

- **Brand Popularity** – Number of reviews available for each brand.
- **Country Popularity** – Number of products reviewed from each country.
- **Premium Brand** – Identifies brands with an average rating of 4 stars or higher.
- **Style Code** – Numerical representation of product packaging style.
- **Rating Category** – Categorizes ratings into Low, Medium, and High.
- **Top Product** – Indicates whether the product appeared in the Top Ten rankings.

---

# Exploratory Data Analysis

The project includes:

- Dataset overview
- Missing value analysis
- Statistical summary
- Correlation heatmap
- Rating distribution
- Brand-wise rating analysis
- Country-wise rating analysis
- Feature importance visualization

---

# Machine Learning Models

The following models were implemented:

### Linear Regression

- Predicts product star ratings.

### Decision Tree Regressor

- Learns patterns in the dataset.
- Identifies the most important features.

### K-Means Clustering

- Groups similar food products based on engineered features.

---

# Project Structure

```
Food-Product-Feature-Engineering/
│
├── Feature_Engineering_and_Exploratory_Modeling.ipynb
├── processed_food_dataset.csv
├── food_feature_engineered.csv
├── README.md
```

---

#Output

The project generates:

- Cleaned dataset
- Feature engineered dataset
- Correlation heatmap
- Feature importance graph
- Brand popularity analysis
- Country popularity analysis
- Rating distribution plots
- Machine learning model results

---

# How to Run

1. Open Google Colab.
2. Upload the notebook.
3. Upload the dataset (`processed_food_dataset.csv`).
4. Run all notebook cells sequentially.
5. The final engineered dataset will be saved as:

```
food_feature_engineered.csv
```

---

# Learning Outcomes

Through this project, I learned:

- Data preprocessing
- Feature engineering techniques
- Exploratory data analysis (EDA)
- Data visualization
- Label Encoding
- One-Hot Encoding
- Correlation analysis
- Linear Regression
- Decision Tree Regression
- K-Means Clustering
- Feature importance analysis

---

# Author

**Fateen Malik**

Bachelor of Engineering (Artificial Intelligence & Data Science)

Mumbai University

---

