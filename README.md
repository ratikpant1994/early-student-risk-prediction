# early-student-risk-prediction
# Early Prediction of At-Risk Students Using Machine Learning

This project builds a machine learning pipeline to identify university students at risk of poor academic performance — enabling timely and targeted academic interventions.

Using data from 989 students across 29 academic, behavioral, and socio-economic features, we engineered insightful metrics (like study efficiency and distraction ratios) and evaluated five classification models. Our XGBoost model emerged as the top performer, achieving:
- **97% recall** and **96% precision** for identifying poor-performing students (Class 3)
- A significant uplift (+10%) over the logistic regression baseline

## Key Highlights
- 📊 Feature engineering based on academic behavior, wellness, and socioeconomics
- 🤖 Models used: Logistic Regression, Decision Tree, Random Forest, XGBoost, and SVM
- 🎯 Business goal: Maximize recall to ensure at-risk students are not overlooked
- 📈 Outcome: Supports proactive academic advising and institutional resource optimization

## Technologies
- Python (scikit-learn, XGBoost, pandas, matplotlib)
- Statistical tests (Kruskal-Wallis) for hypothesis validation

## Impact
Early identification empowers universities to improve student retention, optimize resources, and support students more effectively.
