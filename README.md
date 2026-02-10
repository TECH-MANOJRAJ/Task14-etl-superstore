# Task14-etl-superstore(Superstore Dataset)

## 📌 Project Overview

This project implements a mini **ETL (Extract → Transform → Load)** pipeline using the Superstore dataset. The goal is to simulate a real-world data engineering workflow by cleaning raw data, transforming it into structured tables, and exporting it as organized CSV files for analytics.

This task demonstrates practical ETL skills used in modern data analytics pipelines.

---

## 🧰 Tools & Technologies Used

* **Python**
* **Pandas**
* **Google Colab / Jupyter Notebook**
* **CSV file storage**
* **GitHub** for version control

---

## 🔄 ETL Workflow

### 1. Extract

* Loaded the raw Excel dataset (`superstore_dataset.xlsx`)
* Saved a raw backup copy into the `raw/` folder

### 2. Transform

* Cleaned missing values
* Removed duplicate rows
* Standardized column names
* Created derived column:

  * `profit_margin = profit / sales`

### 3. Load

* Saved cleaned dataset as `processed_data.csv`
* Split data into structured CSV tables:

  * `customers.csv`
  * `orders.csv`
  * `products.csv`

---

## 📂 Project Folder Structure

```
task14-etl/
│
│── superstore_raw.csv
│
├── processed/
│   └── processed_data.csv
│
├── output/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
│
├── task14_etl.ipynb
└── README.md
```

---

## 📊 Key Outcomes

* Built a working ETL pipeline from scratch
* Practiced data cleaning and transformation
* Structured data into normalized tables
* Exported organized CSV outputs
* Understood real-world analytics workflows

---

## 🎯 Learning Objectives Achieved

* Understanding ETL concepts
* Data preprocessing using Pandas
* Creating reproducible data pipelines
* Organizing datasets for analytics
* GitHub project structuring

---

## 🚀 How to Run the Project

1. Upload the dataset to Google Colab or Jupyter Notebook
2. Run all cells in `task14_etl.ipynb`
3. Processed files will be generated in the project folders

---

## 📌 Conclusion

This ETL pipeline shows how raw business data can be transformed into structured datasets ready for analysis. The workflow mirrors industry practices used in data analytics and engineering projects.

---

## 👨‍💻 Author
MANOJRAJ G – Data Analyst Internship
