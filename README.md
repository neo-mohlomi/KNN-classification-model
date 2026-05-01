##Customer Purchase Prediction using K-Nearest Neighbors (KNN)
##  Project Overview
This project applies the K-Nearest Neighbors algorithm to predict whether a customer is likely to purchase a car based on features such as age and salary.
The goal is to explore how instance-based learning methods like KNN can be used for customer segmentation and targeted marketing.
##  Problem Statement
Businesses want to identify customers who are more likely to purchase their products in order to improve marketing efficiency and increase sales.

In this project, I predict customer purchase behavior using demographic features.
##  Approach
The following steps were followed:

1. Data loading and exploration    
2. Feature scaling 
3. Splitting the dataset into training and testing sets  
4. Training a KNN classification model 
5. Evaluating model performance
6. Visualising the performance of the model 
---

##  Tools & Technologies
- Python  
- pandas  
- NumPy  
- scikit-learn  
- matplotlib 

---

##  Model Evaluation
The model was evaluated using:
- Accuracy score  
- Confusion matrix  

These metrics help assess how well the model predicts customer purchasing behavior.

---

## Key Insight
KNN relies heavily on distance between data points, making feature scaling an important step. Proper preprocessing significantly improves model performance.

---

## Business Impact
This model can help businesses:
- Identify potential customers  
- Improve targeted marketing campaigns  
- Increase conversion rates  
- Reduce unnecessary advertising spend  

---

##  Comparison with Logistic Regression
Unlike Logistic Regression, which assumes a linear relationship, KNN is a non-parametric method that can capture more complex patterns in the data.

This comparison helps in selecting the most suitable model for customer prediction tasks.And based on the accuracy score , the KNN proved to be more reliable than Logistic regression
