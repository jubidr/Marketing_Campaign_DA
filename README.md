# Customer Spending Behavior Analysis

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a marketing dataset to uncover patterns in customer behavior. I used this project to practice data cleaning, feature engineering, and visualizing how demographic factors impact spending.

## 🛠️ Environment & Tools
* **Google Colab**: Primary environment for development and execution.
* **Pandas**: Used for data manipulation, cleaning, and handling TSV files.
* **Matplotlib**: Used to generate bar charts and visualize trends.
* **Logging**: Implemented a logging system to track data loading processes.

## 🧹 Key Data Operations
* **Column Standardization**: Converted all column names to **snake_case** (lowercase with underscores) to ensure consistent and clean code.
* **Feature Engineering**: Created a `Total_kids` column by combining child and teen household counts to better understand household dynamics.
* **Data Cleaning**: Standardized the `Education` column by grouping similar entries (e.g., merging "2n Cycle" into "Master") to create more accurate spending averages.

## 📊 Key Findings
I used **Groupby** operations to analyze the average spending on various products (Wine, Meat, Fruits, etc.) based on customer segments:
* **Education:** Higher education levels show distinct patterns in luxury spending, specifically in Wine and Gold products.
* **Family Size:** Analysis of the `Total_kids` feature reveals a shift in spending priorities; as the number of children increases, spending on certain food categories changes significantly.

## 🚀 How to Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `mrktng_cmpgn_da.ipynb` notebook.
3. Ensure `marketing_campaign.csv` is uploaded to the Colab session storage.
4. Run all cells to generate the logs and visualizations.
