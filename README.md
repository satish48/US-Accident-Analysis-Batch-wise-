# US Accident Analysis 🚗💥

An in-depth, end-to-end data analysis project exploring accident trends across the United States.  
This project dives into how weather, road conditions, time of day, and other factors contribute to accident severity — turning raw data into actionable insights.

---

## 🔍 Project Overview
The goal of this project is to analyze U.S. accident data to:
- Identify accident-prone regions and seasons.
- Understand how weather and road conditions affect accident severity.
- Provide visual insights to support better safety planning.

---

## 🧠 Key Highlights
- Cleaned and processed **large-scale accident data** using Python and Pandas.  
- Visualized geographical and network-based patterns with **Matplotlib, Seaborn, Folium, and NetworkX**.  
- Explored time-based trends (rush hours, weekdays vs weekends).  
- Applied clustering with **KMeans** to group similar accident zones.  
- Built multiple classification models to analyze contributing factors using:
  - **Logistic Regression**  
  - **Random Forest**  
  - **Gradient Boosting**  
  - **SGD Classifier**  
  - **XGBoost**
- Evaluated models using comprehensive metrics like **Accuracy, F1-Score, ROC-AUC, Precision-Recall, and Confusion Matrix**.  
- Employed preprocessing pipelines with **Scikit-learn**, including **StandardScaler, OneHotEncoder, ColumnTransformer, and Pipelines** for clean and repeatable workflows.

---

## 🧰 Tech Stack & Libraries
- **Data Analysis & Cleaning:** pandas, numpy, category_encoders  
- **Visualization:** matplotlib, seaborn, folium, networkx  
- **Preprocessing & Pipelines:** scikit-learn (train_test_split, StandardScaler, OneHotEncoder, ColumnTransformer, Pipeline)  
- **Clustering & Modeling:** KMeans, LogisticRegression, RandomForestClassifier, GradientBoostingClassifier, SGDClassifier, XGBClassifier  
- **Model Evaluation & Metrics:** accuracy_score, f1_score, classification_report, confusion_matrix, roc_auc_score, precision_recall_curve, average_precision_score, balanced_accuracy_score, auc  
- **Warnings Control:** warnings (to ignore irrelevant warnings during analysis)

---

## 📈 Insights Snapshot
This analysis explored the US Accidents dataset with a focus on understanding and predicting accident severity. After rigorous data cleaning and feature engineering, including temporal (Hour, DayOfWeek, Rush_Hour), environmental (Weather_Condition, Visibility_Precip), and location-based features, we trained multiple machine learning models. Random Forest and XGBoost consistently outperformed others, achieving the highest accuracy and F1-scores. Feature importance analysis highlighted that peak hours, adverse weather conditions, and low visibility are the strongest predictors of accident severity, confirming domain insights..

---

## 📂 Repository Structure
