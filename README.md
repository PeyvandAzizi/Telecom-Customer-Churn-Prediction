# Telecom-Customer-Churn-Prediction

# Customer Churn Prediction in Telecom Industry

## 📌 Project Overview
This project aims to predict which customers are likely to leave a telecommunications company. By identifying these customers in advance, the company can take proactive measures to retain them.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Imbalanced-Learn (SMOTE), Matplotlib, Seaborn
- **Model:** Random Forest Classifier

## 🚀 Key Features
- **Data Cleaning:** Handled missing values and converted data types.
- **EDA:** Visualized key factors like Contract Type and Monthly Charges affecting churn.
- **Handling Imbalance:** Used **SMOTE** to balance the dataset, improving the model's ability to detect churners (Recall).
- **Model Deployment Ready:** Exported the final model as a `.pkl` file.

## 📊 Results
The model achieved a significant improvement in identifying churners after balancing the data.
- **Accuracy:** [عدد دقت مدل خود را اینجا بنویس]
- **Recall for Churners:** [عدد ریکال کلاس ۱ را اینجا بنویس]

## 📂 How to Use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Load the model using `joblib.load('churn_model_final.pkl')`.
