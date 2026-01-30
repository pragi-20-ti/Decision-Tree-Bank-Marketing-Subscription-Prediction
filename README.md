# Decision Tree – Bank Marketing Subscription Prediction

## 📌 Project Overview
This project uses a Decision Tree classification algorithm to predict whether a bank customer will subscribe to a term deposit based on demographic, financial, and campaign-related information.

The model is trained on the UCI Bank Marketing Dataset and focuses on understanding customer subscription behavior.

## 🎯 Objective
To build a machine learning model that predicts bank term deposit subscription using a Decision Tree classifier and evaluate its performance using standard classification metrics.

## 📂 Dataset
- **Source:** UCI Machine Learning Repository / Kaggle
- **Name:** Bank Marketing Dataset
- **Target Variable:** `y`  
  - 1 → Yes (Subscribed)  
  - 0 → No (Not Subscribed)

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

## 🔄 Project Workflow
1. Load and explore the dataset  
2. Handle missing and unknown values  
3. Encode categorical variables  
4. Split data into training and testing sets  
5. Train Decision Tree classifier  
6. Visualize the Decision Tree  
7. Evaluate model performance  

## 📊 Model Used
- **Algorithm:** Decision Tree Classifier  
- **Criterion:** Entropy  
- **Max Depth:** 5  

## 📈 Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score  

## 🧠 Results
The Decision Tree model successfully predicts customer subscription behavior with good accuracy. Limiting tree depth helps prevent overfitting and improves generalization.

## 📁 Files in Repository
- `Task_8_Decision_Tree_Bank_Marketing.ipynb` → Jupyter Notebook  
- `bank.csv` → Dataset  
- `README.md` → Project documentation  

## ✅ Conclusion
This project demonstrates how Decision Trees can be applied to real-world marketing data to extract meaningful insights and support decision-making in banking campaigns.

## 👩‍💻 Author
Pragati Rathod
