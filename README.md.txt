# British Airways Customer Purchase Prediction

## 📌 Project Overview
This project was completed as part of the **British Airways Data Science Job Simulation on Forage**.  
The goal of this project is to build a machine learning model that predicts whether a passenger will purchase a holiday package based on customer and booking-related features. The project also focuses on identifying the most important factors influencing customer purchase decisions.

---

## 🎯 Problem Statement
British Airways wants to better understand customer behavior in order to improve targeted marketing and holiday package offerings.  
Given historical passenger booking data, the task is to:

- Predict whether a customer will purchase a holiday
- Identify key features that influence purchase decisions

This is formulated as a **binary classification problem**.

---

## 📂 Dataset
The dataset was provided as part of the Forage job simulation and contains passenger and booking-related information, including:

- Customer travel details
- Booking preferences
- Flight and trip-related attributes

**Target Variable:**
- `purchase`
  - `1` → Customer purchased a holiday
  - `0` → Customer did not purchase a holiday

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔄 Workflow
1. Data loading and exploration  
2. Data preprocessing and feature encoding  
3. Train-test split  
4. Model training using **XGBoost Classifier**  
5. Model evaluation  
6. Feature importance analysis  

---

## 🤖 Model Used
**XGBoost Classifier** was selected because:
- It performs exceptionally well on structured/tabular data
- It captures complex non-linear relationships
- It is robust against overfitting
- It provides feature importance for interpretability

---

## 📊 Results & Insights
- The model demonstrates good predictive performance on unseen data.
- Feature importance analysis shows that **booking and travel-related features** play a major role in predicting customer purchases.
- These insights can help British Airways improve personalized marketing strategies and identify high-intent customers early.

---

## 📁 Repository Structure
├── british_airways_purchase_prediction.ipynb
├── british_airways_passenger_data.xlsx
├── README.md
├── requirements.txt
├── .gitignore


## 🚀 How to Run
1. Install dependencies: pip install -r requirements.txt
2. Open the notebook: notebook/british_airways_purchase_prediction.ipynb




## 🚀 Conclusion
This project demonstrates the application of machine learning to a real-world business problem in the airline industry. By combining predictive modeling with feature importance analysis, the solution provides both accurate predictions and actionable business insights.

---

## 📎 Acknowledgment
This project was completed as part of the **British Airways Data Science Job Simulation on Forage**.



## 👤 Author
Tarun Kumar Rai
---
