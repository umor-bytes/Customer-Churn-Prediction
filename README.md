# Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to churn based on their demographic information, account details, and service-related characteristics.

## 📌 Project Overview

Customer churn is a major challenge for businesses because retaining existing customers is often more valuable than acquiring new ones.

This project uses Machine Learning to analyze customer information and predict whether a customer is likely to leave a service.

The project includes data preprocessing, exploratory data analysis, model training, evaluation, and prediction on new customer data.

## 🎯 Objectives

* Analyze customer data to identify churn-related patterns.
* Preprocess categorical and numerical features.
* Train a Machine Learning classification model.
* Evaluate the performance of the trained model.
* Predict churn probability for individual customers.
* Save and reload the trained Machine Learning model.
* Demonstrate the model using a sample customer.

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Joblib**
* **Machine Learning**

## 📂 Project Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
└── requirements.txt
```

## 🔄 Machine Learning Workflow

```text
Customer Dataset
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Preprocessing
       ↓
Train/Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Model Saving
       ↓
New Customer Prediction
```

## 🧹 Data Preprocessing

The dataset contains a combination of numerical and categorical customer features.

The preprocessing stage includes:

* Handling missing or inconsistent values.
* Converting categorical variables into numerical representations.
* Preparing features for Machine Learning.
* Separating input features and the target variable.
* Splitting the dataset into training and testing sets.

## 🤖 Model

A supervised Machine Learning classification approach is used to predict customer churn.

The model learns patterns from historical customer data and produces:

* **Churn Prediction**
* **Churn Probability**

The trained model is also saved so that it can be loaded later without retraining.

## 💾 Model Saving

The trained model is saved as:

```text
customer_churn_model.pkl
```

This allows the trained model to be reused for future predictions.

## 🧪 Sample Prediction

The project includes a test customer to demonstrate how the trained model performs on new customer information.

Example output:

```text
========== SAVED MODEL TEST ==========

Prediction       : LIKELY TO CHURN
Churn Probability: 79.20%
```

This demonstrates that the model can provide both a classification result and an estimated probability of churn.

## 📊 Model Evaluation

The notebook contains the model evaluation results and visualizations used to understand its performance.

The evaluation process helps determine how effectively the model distinguishes between customers who are likely to churn and customers who are likely to remain.

## ▶️ How to Run

### Google Colab

Open the notebook directly in Google Colab:

https://colab.research.google.com/drive/1ecc78_Nv5kNyzRgCyIEzFIaQ7vyh-e8D

Run the notebook cells sequentially.

### Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/customer-churn-prediction.git
```

Navigate to the project:

```bash
cd customer-churn-prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Customer_Churn_Prediction.ipynb
```

## 📦 Requirements

All required Python libraries are listed in:

```text
requirements.txt
```

## 🚀 Future Improvements

* Compare multiple classification algorithms.
* Perform hyperparameter tuning.
* Improve model performance using feature engineering.
* Build an interactive customer churn prediction interface.
* Deploy the model as a web application.
* Add real-time customer prediction.
* Monitor model performance after deployment.

## 👨‍💻 Author

**Umor**

Machine Learning Project — Customer Churn Prediction

---

⭐ If you find this project useful, consider giving the repository a star.
