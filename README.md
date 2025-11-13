# Customer Churn Prediction Analysis

##  Project Overview
This project analyzes customer data to understand and predict customer churn. Using machine learning techniques, we explore patterns in customer behavior that lead to churn and build predictive models to identify at-risk customers.

## 📊 Dataset
We use the **Telco Customer Churn Dataset** containing:
- **7,043 customers** with **21 features**
- Features include demographic info, service subscriptions, contract details, and billing information
- Target variable: **Churn** (whether a customer left the service)

##  Key Findings
- **Overall churn rate: 26.54%**
- Dataset is well-balanced with no missing values
- Contains both numerical (tenure, monthly charges) and categorical (contract type, payment method) features

##  Technical Implementation

### Libraries Used
- Data Analysis: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn, XGBoost
- Preprocessing: StandardScaler, LabelEncoder

### Models Implemented
1. **Random Forest Classifier**
2. **Gradient Boosting Classifier** 
3. **XGBoost Classifier**

### Evaluation Metrics
- Classification Report
- Confusion Matrix
- ROC-AUC Score
- Precision-Recall Curves
- F1-Score and Accuracy

##  Project Structure
1. **Data Loading & Exploration** - Understand dataset structure and basic statistics
2. **Data Visualization** - Explore churn distribution and patterns
3. **Data Preprocessing** - Handle categorical variables and feature scaling
4. **Model Training** - Implement multiple classification algorithms
5. **Model Evaluation** - Compare performance across different models
6. **Results Analysis** - Identify key factors influencing churn

##  Business Impact
This analysis helps businesses:
- Identify customers likely to churn
- Understand reasons behind customer attrition
- Develop targeted retention strategies
- Optimize customer service and product offerings

##  Key Insights
The project provides actionable insights into customer behavior patterns, helping companies reduce churn rates and improve customer satisfaction through data-driven decision making.

---
*Note: This is a proprietary analysis tool. Unauthorized copying or distribution is prohibited.*
