# 📊 Task 14: ETL Mini Pipeline — Customer Conversion Dataset

## 👨‍💻 Project Overview
This project demonstrates a complete ETL (Extract → Transform → Load) pipeline using Python and pandas.  
The dataset used is a Customer Conversion Testing Dataset.

The objective was to clean raw data, create meaningful transformations, and load structured outputs for analytics and reporting.

---

## 🔹 Tools Used
- Python
- pandas
- SQLite
- CSV Storage

---

## 📂 Project Structure

```
project_folder/
│
├── raw/
│   └── customer_conversion_testing_dataset.csv
│
├── processed/
│   ├── customers.csv
│   ├── interactions.csv
│   └── conversion.csv
│
├── output/
│   └── database.sqlite
│
└── task14_etl.ipynb
```

---

## 🔄 ETL Process

### 1️⃣ Extract
- Loaded raw CSV dataset
- Checked dataset shape and missing values

### 2️⃣ Transform
- Removed duplicates
- Handled missing values
- Standardized column names
- Converted datatypes
- Created derived columns:
  - `engagement_score`
  - `high_intent_flag`
  - `age_group`

### 3️⃣ Load
- Exported cleaned datasets into:
  - Separate CSV files
  - SQLite database tables
- Validated row counts before and after transformation

---

## 📊 Derived Features Created

- **Engagement Score**
  - Based on time spent, pages viewed, and social media engagement

- **High Intent Flag**
  - Identifies users with form submissions or downloads

- **Age Group Segmentation**
  - Categorized customers into age bands

---

## ✅ Validation Performed
- Row count verification
- Duplicate removal check
- Data type validation
- Null value check

---

## 🎯 Final Outcome
- Built a structured ETL workflow
- Practiced data cleaning and transformation
- Created normalized outputs for analytics
- Loaded data into SQLite for database-based querying

---

## 📌 Key Learnings
- Importance of clean and structured data
- Data validation techniques
- Database loading using SQLite
- Feature engineering in ETL pipelines

---

## 🚀 Author
Adarsh Mishra  
B.Tech Electronics & Computer Engineering  
AI/ML Intern – Elevate Lab
