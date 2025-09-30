**Dataset**

Source: Kaggle - Customer Personality Analysis
Cleaned file: marketing_campaign_clean.csv

**Key Features:**

**Demographics**: Age, Education, Marital Status, Income, Kids, Teens
**Spending**: Amount spent on Wines, Fruits, Meat, Fish, Sweets, Gold
**Campaign Response**: Response (Target variable: 1 = Accepted, 0 = Not Accepted)
**Other Behavior**: Recency (days since last purchase), Web Purchases, Store Purchases, etc.

** Project Workflow**
**Data Cleaning**
 Handle missing values in Income
 Create Age and TotalSpend features
 Drop irrelevant columns
**Exploratory Data Analysis (EDA)**
 Distributions of income, age, and spending
 Correlation between features and campaign response
**Feature Engineering**
 Standardize numeric features
 One-hot encode categorical features
**Modeling**
 Logistic Regression (baseline)
 Random Forest Classifier (improved performance)
**Evaluation**
 Classification Report (Precision, Recall, F1-score)
 ROC-AUC Score
 ROC Curve & Precision-Recall Curve
 Confusion Matrix
 Feature Importance (Random Forest)

**  Results**

**Logistic Regression:** Provides a baseline with interpretability.
**Random Forest:** Delivers higher accuracy & ROC-AUC.
**Top Predictors:**
 Income
 Age
 TotalSpend (especially Wines & Gold)
 Web Purchases
