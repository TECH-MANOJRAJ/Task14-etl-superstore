# ETL Mini Pipeline — Task 14

## 📌 Project Overview

This project implements a mini ETL (Extract → Transform → Load) pipeline using Python.
The goal is to simulate a real-world data analytics workflow by cleaning raw data, transforming it, and storing structured outputs.

---

## 🛠 Tools & Technologies

* Python
* Pandas
* SQLite
* Google Colab / Jupyter Notebook
* CSV files

---

## 📂 Project Folder Structure

```
task14_etl/
│
├── raw/
│   └── raw_data.csv
│
├── processed/
│   └── processed_data.csv
│
├── output/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
│
├── database.sqlite
└── task14_etl.ipynb
```

---

## 🔄 ETL Workflow Steps

### 1. Extract

* Loaded dataset from CSV source
* Saved raw copy in `raw/` folder

### 2. Transform

* Removed duplicates
* Cleaned missing values
* Standardized column names
* Created derived columns:

  * Profit margin
  * High value customer flag

### 3. Load

* Split dataset into:

  * Customers table
  * Orders table
  * Products table
* Exported processed CSV files
* Stored structured tables in SQLite database

---

## ✅ Validation

* Verified row counts before and after transformation
* Ensured clean and structured outputs

---

## 🎯 Final Outcome

This project demonstrates how ETL pipelines are built in analytics workflows.
It improves data cleaning, transformation, and database handling skills.

---

## 🚀 How to Run

1. Open `task14_etl.ipynb` in Google Colab or Jupyter
2. Run all cells step-by-step
3. Generated files will appear in project folders
4. Upload project to GitHub

---

## 📎 Dataset Source

Superstore retail dataset (CSV)

---

## 👨‍💻 Author
MANOJRAJ G

Data Analyst Internship — Task 14
