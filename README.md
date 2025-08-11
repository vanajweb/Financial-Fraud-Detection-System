### Fraud Detection in Mobile Financial Transactions
## 📌 Overview
This project focuses on detecting fraudulent mobile financial transactions using machine learning techniques. The dataset was preprocessed, explored, and modeled using various algorithms to find the most effective approach. The workflow emphasizes business relevance, realistic performance, and actionable insights.
## 📂 Repository Contents
| File Name                                       | Description                                                                                                                 |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| `Fraud_Analysis_Dataset.csv`                    | Original dataset containing transaction records.                                                                            |
| `Fraud_Detection_Vanaj_Kumar_Yadav.ipynb`       | Jupyter Notebook with complete workflow: data cleaning, EDA, feature engineering, model training, evaluation, and insights. |
| `Fraud_Detection_Vanaj_Kumar_Yadav_Report.docx` | Detailed project report with visualizations, methodology, and business takeaways.                                           |
| `xgb_model_trained.pkl`                         | Saved trained XGBoost model for deployment purposes.                                                                        |
| `XGBoost_Tuned_Results.csv`                     | Evaluation and tuning results for XGBoost model.                                                                            |
| `README.md`                                     | Repository guide and documentation.                                                                                         |

## 🛠️ Workflow
1. Problem Definition – Fraud detection in mobile transactions.

2. Data Collection – Loading dataset and understanding structure.

3. Exploratory Data Analysis (EDA) – Statistical summaries, distributions, correlations, and fraud trends.

4. Data Cleaning – Handling missing values, removing duplicates, and outlier analysis.

5. Feature Engineering – Encoding categorical variables, creating date features, scaling numerical features.

6. Train-Test Split & Preprocessing Pipeline – Ensuring no data leakage and preparing for model training.

7. Model Training – Logistic Regression, Random Forest, and XGBoost.

8. Model Evaluation – Precision, recall, F1-score, confusion matrix, ROC-AUC score.

9. Model Comparison – Selecting the best-performing model based on balanced performance metrics.

10. Business Insights & Recommendations – Translating results into practical fraud prevention strategies.

## 📊 Key Insights
Fraudulent transactions are significantly skewed compared to normal transactions.

Transaction type and amount patterns play a major role in detecting fraud.

Random Forest provided a strong balance between precision and recall without unrealistic 100% performance.

Feature engineering, such as creating time-based features, improved model interpretability.
## Business Impact
Helps banks and payment platforms reduce financial losses from fraudulent transactions.

Improves customer trust by proactively flagging suspicious activity.

Allows real-time monitoring when deployed into production systems.

## Author & Acknowledgments
Author : Vanaj Kumar Yadav
Special thanks to the evaluation feedback that guided model improvements and made the project more business-aligned.
Email : yadavvanaj3@gmail.com
Linkedin : https://www.linkedin.com/in/vanaj-kumar-yadav-86bb261b9/

