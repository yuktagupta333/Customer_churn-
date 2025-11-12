# Data Preparation Report

### Data Sources
Merged data from five sources:
- Customer_Demographics
- Transaction_History
- Customer_Service
- Online_Activity
- Churn_Status

### EDA Findings
- Checked missing values, distributions, and correlations.
- Visualized numeric and categorical variables.
- Verified target class balance (Churn).

### Data Cleaning
- Dropped columns with >50% missing data.
- Imputed numeric values with median and categorical with mode.
- Capped outliers using IQR.
- Removed duplicates.

### Preprocessing
- One-hot encoded categorical variables.
- Standardized numerical columns.
- Output file: cleaned_customer_churn.csv (ready for model training)
