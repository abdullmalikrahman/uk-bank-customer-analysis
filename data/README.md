# Dataset Documentation

## Dataset Overview

This project uses the **UK Bank Customers** dataset, which contains customer demographic information and account balance data.

The dataset is used to explore customer distribution, regional characteristics, job classifications, and average customer balance patterns.

## Dataset Source

The dataset was obtained from Kaggle:

[UK Bank Customers – Kaggle](https://www.kaggle.com/datasets/ukveteran/uk-bank-customers)

## Dataset Information

The original dataset contains:

- **Total Records:** 4,014 customers
- **Total Columns:** 9

The original columns include:

- Customer ID
- Name
- Surname
- Gender
- Age
- Region
- Job Classification
- Date Joined
- Balance

## How to Obtain the Dataset

1. Visit the Kaggle dataset page linked above.
2. Download the dataset from its original source.
3. Extract the downloaded file if necessary.
4. Use the CSV file as the data source in Microsoft Power BI.

## Data Availability

The raw CSV file is not included in this repository. Users should obtain the dataset directly from its original Kaggle source.

Please refer to the original dataset page for its license and usage conditions.

## Notes

The dataset was prepared and transformed using Power Query before being used in the Power BI dashboard.

The `Name` and `Surname` columns were combined into a single `Name` column, and an additional `Age range` column was created for customer segmentation.
