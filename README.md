# AI-Powered Credit Card Fraud Detection

This repository contains the complete code and analysis for an AI-powered credit card fraud detection model. The project demonstrates a full machine learning pipeline, from data exploration and preprocessing to model training and evaluation, with a focus on solving real-world challenges like class imbalance.

---

## 🚀 Project Overview

The goal of this project is to tackle the critical challenge of detecting credit card fraud. Given the highly imbalanced nature of fraud datasets, the model is specifically engineered and optimized for **high Recall**, ensuring that the maximum number of fraudulent transactions are identified. This repository serves as a comprehensive case study in building an effective and responsible AI solution for financial security.

## ✨ Key Features

-   **High-Recall Prediction Model:** A Random Forest model carefully tuned to identify all potential instances of fraud.
-   **Advanced Data Handling:** Implements **SMOTE** (Synthetic Minority Over-sampling Technique) to effectively address severe class imbalance.
-   **Robust Preprocessing:** Utilizes `StandardScaler` for feature normalization to improve model performance and convergence.
-   **Ready for Deployment:** The entire prediction logic, including the data scaler and the trained model, is serialized into `.pkl` files, making the system easily deployable.
-   **In-Depth Analysis:** The accompanying Jupyter Notebook provides detailed exploratory data analysis (EDA) and step-by-step model evaluation.

---

## 🛠️ Tech Stack & Libraries

-   **Language:** Python
-   **Libraries:** Scikit-learn, Pandas, NumPy, imbalanced-learn, Matplotlib, Seaborn
-   **Core Algorithms:** Random Forest Classifier, SMOTE
-   **Analysis Environment:** Jupyter Notebook
-   **Evaluation Metrics:** ROC Curve, Precision-Recall Curve, Confusion Matrix

---

## 🔬 How to Explore This Project

The core of this project is the Jupyter Notebook, which contains the full analysis and model development process.

1.  **Clone the repository** to your local machine.
2.  **Open and run the `notebooks/Real Time Credit card Fraud Detection(** in a Jupyter environment.

Inside the notebook, you will find a detailed walkthrough of:
-   Exploratory Data Analysis (EDA).
-   Data preprocessing and feature scaling.
-   Handling class imbalance with SMOTE.
-   Training the Random Forest model.
-   In-depth model evaluation with visualizations.

---

## 📊 Model Performance

The final model was evaluated with a primary focus on maximizing **Recall**, as missing a case of fraud is more costly than flagging a legitimate transaction for review.

| Metric          | Score              |
|-----------------|--------------------|
| ✅ **Accuracy**   | 99.91%             |
| 🎯 **Precision**  | 0.6578             |
| 🚨 **Recall**     | **1.0000 (Perfect)** |
| 🔄 **F1-Score**  | 0.7936             |

The perfect Recall score demonstrates the model's success in its primary mission: identifying every potential instance of fraud within the dataset.

---

## 💡 Future Improvements

-   Deploy the serialized model using a web framework like Flask or FastAPI to create a REST API.
-   Experiment with other advanced models like XGBoost and LightGBM to potentially improve Precision without sacrificing Recall.
-   Integrate the model into a larger simulated system with a database to log predictions and monitor performance over time.

---

## 📬 Contact

Sahanashree Subhas Talagade
-   **LinkedIn:** [linkedin.com/in/sahanashreetalagade](https://www.linkedin.com/in/sahanashreetalagade/)
-   **Email:** sahanatalagade@gmail.com
