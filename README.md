# **Support Vector Regression (SVR) for Startup Profit Prediction**  
This project demonstrates the use of **Support Vector Regression (SVR)** to predict the profit of startups based on various features such as R&D Spend, Administration, Marketing Spend, and State. SVR, a powerful machine learning algorithm, is used to model non-linear relationships between independent variables and the dependent variable (profit).

## **🛠 Technologies Used**  
**Programming Language:** Python  
**Libraries:**  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

## **📊 Project Overview**  
- **Goal:** Predict startup profits using Support Vector Regression.  
- **Dataset:** Contains data for 50 startups with features:  
  - R&D Spend  
  - Administration  
  - Marketing Spend  
  - State (categorical)  
  - Profit (dependent variable)  

## **🔑 Key Learnings**  
- **Understanding Support Vector Regression:**  
  - SVR uses a hyperplane to model the relationship between independent variables and the dependent variable, while attempting to minimize the error margin.  
  - SVR is particularly useful for non-linear data, unlike traditional linear regression.

- **Data Preprocessing:**  
  - Encoded the categorical variable **State** using **OneHotEncoder**.  
  - Scaled the features using **StandardScaler** for better performance in SVR.

- **Model Training:**  
  - Built and trained the SVR model using **Scikit-learn**'s SVR class.  
  - Optimized the model with kernel selection (linear, polynomial, or RBF) and adjusted hyperparameters to reduce overfitting.

- **Visualization:**  
  - Created plots using **Matplotlib** to visualize the regression line and assess model accuracy.  
  - Compared SVR performance with other models, such as Multiple Linear Regression.

---

## **🚀 Results**  
- Successfully developed a Support Vector Regression model that predicts startup profits with high accuracy.  
- Gained insights into the flexibility of SVR for non-linear relationships and its ability to generalize well with appropriate tuning.  
- Demonstrated the importance of feature scaling in improving the performance of SVR models.
