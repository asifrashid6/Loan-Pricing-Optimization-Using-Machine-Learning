# Loan Pricing Optimization Using Machine Learning

This project tackles a real-world case study from Nomis Solutions, where we optimized auto loan pricing (APR) for a digital lender (e-Car) using machine learning.

##  Problem Statement
E-Car needed to balance revenue per loan against the risk of loan rejection. The goal was to predict loan acceptance probability based on offered APR and customer features, and recommend an APR that maximizes expected revenue.

##  Solution
- Trained and evaluated multiple ML models (Logistic Regression, Random Forest, Gradient Boosting, SVM, KNN) on customer and competitor features.
- Identified optimal flat APR and implemented customer-level APR optimization.
- Engineered a new feature `RateDiff` to capture pricing competitiveness.
- Achieved 38.6% uplift in test-set revenue using personalized APRs.

##  Tools & Techniques
- Python (Pandas, Sklearn, Matplotlib, Seaborn)
- Logistic Regression, Random Forest, Gradient Boosting, AUC evaluation
- Feature engineering, hyperparameter tuning, and pipeline modeling
- Exploratory data analysis & business simulation

##  Results
- Optimal flat APR: 5.1% → 24% revenue increase
- Personalized APRs → 38.6% revenue uplift
- Model AUC up to 0.91 with Random Forest

##  Contents
- `notebooks/`: Main notebook with full analysis and modeling


##  Author
Asif Rashid | [LinkedIn](https://www.linkedin.com/in/asif-rashid-0636781a5/)
