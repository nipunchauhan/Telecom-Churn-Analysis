# Customer Churn Prediction (KNIME Workflow)

## 🔍 Overview
This project predicts customer churn using the Telco Customer Churn dataset and a KNIME-based data science workflow. It was built as part of a graduate Business Analytics course at The University of Texas at Dallas.

## 🎯 Objectives
- Build an end-to-end churn prediction workflow using KNIME
- Perform data preprocessing, feature engineering, and model training
- Evaluate Logistic Regression, Random Forest, and XGBoost models
- Generate insights and actionable business recommendations

- ## 📁 Project Structure
- data/ - Dataset description and download instructions
- workflow/ - KNIME workflow (.knwf file)
- reports/ - Project report (PDF presentation)
- images/ - Screenshots and visualizations

## 📊 Dataset
- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Size**: ~7,043 rows
- **Features**: Demographics, services, billing, contract info
- **Target**: `Churn` (Yes/No)

*Dataset not included due to licensing. Please download it manually from Kaggle.*

## 🛠 Tools Used
- KNIME Analytics Platform
- PowerPoint (for reporting)
- Python (for exploratory comparison)

## 🔄 Workflow Summary
1. **Data Ingestion** – File Reader, Data Explorer
2. **Preprocessing** – One-hot encoding, null handling, Min-Max normalization
3. **Feature Engineering** – `tenure_to_total_charges_ratio`
4. **EDA** – Bar Charts, Box Plots, Correlation Matrix
5. **Modeling** – Logistic Regression, Random Forest, XGBoost
6. **Evaluation** – Accuracy, F1 Score, ROC Curve
7. **Insights** – Feature importance and churn trends

## 🔢 Model Results
| Model              | F1 Score | Accuracy |
|-------------------|----------|----------|
| Logistic Regression | 0.61     | ~74%     |
| Random Forest       | 0.60    | ~72%     |
| XGBoost             | 0.59    | ~73%     |

✅ **Logistic Regression** had the best F1 Score, balancing recall and precision.

## 🧠 Key Insights
- Churn is highest among **month-to-month** contract users
- **Fiber optic** customers churn more than DSL users
- **Higher monthly charges** lead to more churn
- Users without **Tech Support** or **Online Security** are at greater risk

## 📘 Final Report
📝 A detailed report is available:
[📥 Download Report (PDF)](reports/customer_churn_presentation.pdf)

## 📸 Visualizations
- ![Workflow Snapshot](images/workflow_snapshot.png)
- ![Churn by Contract](images/churn_by_contract.png)

## 👤 Author
Nipun Chauhan  
📍 Dallas, TX  
📧 nipunct@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/nipun-chauhan/)

## 📝 License
This project is open-sourced under the MIT License.
