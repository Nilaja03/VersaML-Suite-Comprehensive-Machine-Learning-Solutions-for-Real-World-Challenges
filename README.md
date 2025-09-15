# VersaML Suite
VersaML Suite is a curated collection of machine learning projects that demonstrate the application of advanced data science techniques to solve diverse, real-world challenges. This repository encompasses four distinct projects that collectively showcase end-to-end workflows from data acquisition and preprocessing to model development, evaluation, and actionable insights.

The projects in this suite cover multiple domains: environmental sustainability, financial security, online safety, and intelligent media organization, providing a holistic view of machine learning capabilities in practice.

1. **Air Quality Index (AQI) Forecasting:**
This project utilizes multi-year AQI data sourced from the Central Pollution Control Board (CPCB) and public repositories to monitor and forecast urban air pollution across Indian cities. Data preprocessing tackles missing values through forward-fill and mean imputation, followed by time-series standardization. Two forecasting models, ARIMA and Facebook Prophet, are applied to capture linear trends and seasonal patterns. Performance is evaluated using Mean Absolute Error (MAE), enabling identification of pollution hotspots and critical time periods for targeted interventions.
    * Dataset: Multi-year Indian AQI data from CPCB and public sources.
    * Preprocessing: Missing value imputation (forward-fill, mean), time-series formatting.
    * Models: ARIMA and Facebook Prophet for forecasting city-wise AQI.
    * Evaluation: Mean Absolute Error (MAE) comparison.

2. **Credit Card Fraud Detection:**
Addressing one of the most challenging problems in financial security, this project leverages anonymized transaction data with significant class imbalance. The Synthetic Minority Oversampling Technique (SMOTE) is applied to balance the dataset. Multiple models—Logistic Regression, Random Forest, and XGBoost—are trained and compared using precision, recall, F1-score, and ROC AUC metrics. Dimensionality reduction (PCA and t-SNE) techniques offer further interpretability of fraud patterns.
    * Dataset: Kaggle credit card transaction data with severe class imbalance.
    * Preprocessing: StandardScaler, SMOTE for oversampling minority class.
    * Models: Logistic Regression, Random Forest, XGBoost.
    * Evaluation: Precision, recall, F1-score, ROC-AUC, PCA and t-SNE visualizations.

3. **Hate Speech Detection:**
A natural language processing pipeline classifies Twitter content to distinguish hate speech from non-hate speech. Text preprocessing involves cleaning, tokenization, and TF-IDF vectorization. SMOTE addresses class imbalance to improve detection fairness. Logistic Regression is used for classification, with evaluation through accuracy, confusion matrices, and classification reports.
    * Dataset: Twitter tweets labeled for hate speech and offensive language.
    * Preprocessing: Text cleaning, TF-IDF vectorization, SMOTE balancing.
    * Model: Logistic Regression.
    * Evaluation: Accuracy, confusion matrix, classification report.

4. **News Article Classification:**
Using the BBC News dataset, this project demonstrates multi-class text classification. Text is preprocessed with lemmatization and stopword removal, followed by TF-IDF feature extraction. Models including Naive Bayes, Logistic Regression, and Support Vector Machine (SVM) are trained and evaluated with metrics covering accuracy, precision, recall, and F1-score.
    * Dataset: BBC News articles with category labels.
    * Preprocessing: Text normalization, lemmatization, stopword removal, TF-IDF.
    * Models: Naive Bayes, Logistic Regression, SVM.
    * Evaluation: Accuracy, precision, recall, F1-score, confusion matrix.

VersaML Suite is designed as a comprehensive resource for data scientists, engineers, and students seeking practical insights into building scalable and interpretable machine learning solutions. The repository emphasizes reproducibility, clear documentation, and best practices in handling imbalanced datasets and diverse data types.

---

## 📜 License
This project is licensed under the GNU Affero General Public License. This means you are free to use, modify, and distribute this software, but any modified version that is used over a network (such as a web app or cloud service) must also make its source code available under the same license.

---

## 👩‍💻 Author
Nilanjana Jamindar

AI-ML Engineer, Data Analyst & AI Research Enthusiast

LinkedIn: www.linkedin.com/in/nilanjana-jamindar-7b1b86200
