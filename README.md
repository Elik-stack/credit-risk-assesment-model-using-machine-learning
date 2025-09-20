# credit-risk-assesment-model-using-machine-learning
a Credit Card Risk Assessment pipeline focused on predicting customer default and modelling credit scores. The codebase contains data ingestion, preprocessing, feature engineering, model training, evaluation, and inference utilities — tailored to the dataset
a machine learning or statistical model used to predict the likelihood that a customer will default on their financial obligations (e.g., loans, credit card payments). It analyzes customer information such as income, savings, debt levels, spending patterns, and demographic factors to assign a risk score or classification (low-risk vs. high-risk).

The model helps financial institutions make data-driven decisions on whether to approve credit, set borrowing limits, or adjust interest rates. By identifying high-risk customers early, it reduces losses from defaults while ensuring that low-risk customers can access credit more easily.
Dataset 

Size: 1,000 customers

Features: 84 engineered features derived from transactional and financial metadata

Primary purpose: Credit risk assessment and default prediction

Target variables

DEFAULT — Binary (1 = defaulted, 0 = not defaulted). Primary classification target.

CREDIT_SCORE — Numerical integer. Useful as a regression target or auxiliary feature.

Key financial features

INCOME — Total income over the past 12 months

SAVINGS — Total savings over the past 12 months

DEBT — Total outstanding debt

R_SAVINGS_INCOME — Savings-to-income ratio

R_DEBT_INCOME — Debt-to-income ratio

R_DEBT_SAVINGS — Debt-to-savings ratio
