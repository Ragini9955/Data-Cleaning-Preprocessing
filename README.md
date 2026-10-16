# Data Ingestion, Cleaning & Preprocessing with Pandas

## 📌 Project Overview

This project focuses on cleaning and preprocessing a messy retail dataset using Python and Pandas. The objective is to identify data quality issues, standardise inconsistent values, handle missing data and duplicate records, and prepare a clean dataset for further analysis.

## 🎯 Objectives

- Load and inspect raw business data using Pandas.
- Identify missing values and duplicate records.
- Handle inconsistent data types and invalid values.
- Standardise dates and categorical fields.
- Perform feature engineering to create useful analytical columns.
- Export the cleaned dataset as `clean_dataset.csv`.
- Compare data quality before and after cleaning.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- CSV

## 🧹 Data Cleaning & Preprocessing Steps

### 1. Data Ingestion
Load the raw retail dataset into Pandas and inspect its structure, columns, data types, and dimensions.

### 2. Data Quality Assessment
Examine missing values, duplicate records, inconsistent formats, and invalid data entries.

### 3. Missing Value Handling
Identify missing values and apply appropriate handling methods based on the relevant columns and business requirements.

### 4. Duplicate Handling
Detect duplicate records and remove them where appropriate to improve data reliability.

### 5. Data Type Standardisation
Convert date and numerical columns into appropriate data types and standardise inconsistent categorical values.

### 6. Feature Engineering
Derive useful features such as month and year from dates, along with revenue, profit, and profit margin where the required source columns are available.

### 7. Export Clean Dataset
Save the processed output as `clean_dataset.csv` for further analysis and reporting.

## 📁 Project Structure

```text
Data-Cleaning-Preprocessing/
│
├── README.md
├── data-cleaning-preprocessing.ipynb
└── clean_dataset.csv
```

## 📊 Dataset & Output

- **Cleaned dataset:** `clean_dataset.csv`
- **Rows in cleaned output:** 11,989
- **Columns in cleaned output:** 33
- **Notebook:** `data-cleaning-preprocessing.ipynb`

The cleaned CSV is the output artifact of the preprocessing workflow. Exact before-and-after cleaning statistics should be taken from the executed notebook.

## ▶️ How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

3. Open the notebook in Jupyter Notebook or VS Code.
4. Ensure the required input dataset and any supporting files referenced by the notebook are available in the expected paths.
5. Run the notebook cells in order.
6. Review the cleaning results and generated CSV file.

## 💡 Learning Outcomes

- Practical experience with Pandas data manipulation.
- Understanding missing-value and duplicate handling.
- Data type conversion and standardisation.
- Feature engineering for business analysis.
- Exporting clean, analysis-ready datasets.

## ⚠️ Note

This project is intended for learning and demonstration purposes. The final cleaning statistics and transformations should be verified by running the notebook with its required input files.

## 👨‍💻 Author

Ragini Shrivastava

Aspiring Data Analyst | Python | Pandas | Data Preprocessing
