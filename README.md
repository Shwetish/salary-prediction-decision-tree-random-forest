# salary-prediction-decision-tree-random-forest
Analyzing professional compensation determinants and predicting salary levels using Decision Tree and Random Forest algorithms.

# Professional Salary Prediction & Feature Analysis

## 1. Business Problem
### 1.1. What is the business objective?
To build an analytical model that predicts professional salaries based on key career attributes (such as experience, education, rank, and discipline), helping organizations establish competitive compensation structures.
### 1.2. Are there any constraints?
* Variance in compensation across different academic or professional specializations.

---

## 2. Data Dictionary
| Feature Name | Data Type | Relevance to Model Building | Description & Reason for Inclusion/Exclusion |
| :--- | :--- | :--- | :--- |
| `Rank` | Categorical | Relevant | Professional rank or seniority level. |
| `Discipline` | Categorical | Relevant | Field of specialization or department. |
| `yrs.since.phd` | Numerical (Int) | Relevant | Years elapsed since obtaining terminal degree / PhD. |
| `yrs.service` | Numerical (Int) | Relevant | Total years of professional service. |
| `Sex` | Categorical (Binary) | Analytical / Optional | Demographic indicator (included for parity analysis). |
| `Salary` | Numerical (Float) | **Target Variable** | Annual or monthly compensation package. |

---

## 3. Exploratory Data Analysis (EDA)
* **3.1 Summary:** Summary statistics of service years, experience post-degree, and compensation spreads.
* **3.2 Univariate Analysis:** Distribution curves of salaries and years of service.
* **3.3 Bivariate Analysis:** Box plots comparing salaries across ranks and disciplines.

---

## 4. Data Pre-processing
* **4.1 Data Cleaning:** Handled missing data points and encoded categorical variables (Rank, Discipline, Sex).

---
