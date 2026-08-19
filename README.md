# Credit Risk Analytics Platform

## 📌 Overview

The Credit Risk Analytics Platform is an end-to-end data analytics and machine learning project that analyzes customer loan applications to assess default risk. The project covers the complete analytics pipeline, from data understanding and cleaning to predictive modeling, risk scoring, expected loss estimation, and interactive dashboard development.

The primary objective is to help financial institutions make data-driven lending decisions by identifying high-risk applicants and estimating the probability of loan default.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- SQL
- Scikit-learn
- Matplotlib
- Seaborn
- Power BI
- Git & GitHub

---

## 📂 Credit-Risk-Analytics-Platform/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── reports/
├── images/
├── dashboard/
├── sql/
├── src/
├── docs/
├── README.md
└── LICENSE
---

## 🚀 Project Roadmap

- ✅ Phase 1 – Data Understanding & Modeling
- ✅ Phase 2 – Data Quality Assessment
- ✅ Phase 3 – Data Cleaning & Feature Engineering
- ✅ Phase 4 – Exploratory Data Analysis
- ⬜ Phase 5 – Advanced Feature Engineering
- ⬜ Phase 6 – Machine Learning
- ⬜ Phase 7 – Credit Risk Scoring
- ⬜ Phase 8 – Expected Loss Analysis
- ⬜ Phase 9 – Power BI Dashboard

---

## 📊 Completed Work

### Phase 1 – Data Understanding & Modeling

- Dataset structure and schema analysis
- Fact and Dimension identification
- Data dictionary development
- ER diagram and relationship analysis

### Phase 2 – Data Quality Assessment

- Missing value analysis
- Duplicate detection
- Data type analysis
- Unique-value analysis
- Descriptive statistics
- Target distribution analysis
- Class imbalance assessment
- Outlier identification
- Correlation analysis
- Data quality reporting and visualizations

### Phase 3 – Data Cleaning & Feature Engineering

- Missing value treatment
- Duplicate validation
- Data type corrections
- Special value treatment
- Outlier handling
- Time-based feature transformations
- Financial feature creation
- Customer-level risk indicators
- Cleaned dataset generation

Key engineered features:

- AGE
- YEARS_EMPLOYED
- INCOME_PER_FAMILY_MEMBER
- CREDIT_INCOME_RATIO
- ANNUITY_INCOME_RATIO
- GOODS_CREDIT_RATIO
- CREDIT_TERM
- CREDIT_PER_FAMILY_MEMBER
- EXT_SOURCE_AVG

### Phase 4 – Exploratory Data Analysis

- Default-rate analysis
- Age-group risk analysis
- Income-type analysis
- Education-level analysis
- Housing-type analysis
- Gender-based analysis
- Financial ratio analysis
- External credit-score analysis
- Correlation analysis
- Risk-segment analysis
- EDA visualizations and analytical reporting

### Key EDA Findings

- 307,511 loan applications analyzed.
- Overall observed default rate: 8.07%.
- Applicants aged 18–25 had an observed default rate of 12.27%, compared with 3.65% for applicants aged 65+.
- EXT_SOURCE_AVG showed the strongest negative correlation with TARGET, at approximately -0.221.
- Average external score:
  - Non-default: 0.519
  - Default: 0.431
- Defaulting applicants showed a slightly higher average annuity-to-income ratio.
- External credit scores, age, employment duration, and financial characteristics showed meaningful associations with default status.
- The target variable is imbalanced, with 91.93% non-default and 8.07% default applications.

> Correlation and observed differences represent relationships within the dataset and should not be interpreted as causal relationships.

---

## 🎯 Upcoming Work

### Phase 5 – Advanced Feature Engineering

- Develop additional credit-risk indicators
- Create risk buckets
- Transform categorical variables
- Feature selection
- Feature importance analysis
- Prepare modeling dataset

### Phase 6 – Machine Learning

- Train-test split
- Baseline model
- Logistic Regression
- Tree-based models
- Gradient Boosting / XGBoost
- Model evaluation
- Cross-validation
- Hyperparameter tuning

### Phase 7 – Credit Risk Scoring

- Probability of Default (PD)
- Risk-score development
- Risk segmentation
- Low / Medium / High-risk classification
- Model interpretation

### Phase 8 – Expected Loss Analysis

- Probability of Default (PD)
- Loss Given Default (LGD)
- Exposure at Default (EAD)
- Expected Loss calculation
- Portfolio-level risk analysis

### Phase 9 – Power BI Dashboard

- Portfolio overview
- Default-rate analysis
- Customer risk segmentation
- Financial risk indicators
- Credit-score analysis
- Model predictions
- Interactive risk monitoring

---

## 📄 Dataset

Home Credit Default Risk Dataset

The dataset contains loan application information including:

- Applicant demographics
- Financial information
- Employment information
- Loan characteristics
- External credit scores
- Previous credit-related information

Raw datasets are excluded from Git version control because of their large file sizes.

---

## 👨‍💻 Author

Gaurav

Mechanical Engineering, NIT Kurukshetra

Aspiring Data Analyst | Credit Risk Analytics | Machine Learning
