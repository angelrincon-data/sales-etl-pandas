# Sales ETL Pipeline with Python & Pandas

## 📌 Project Overview
This project implements an end-to-end ETL (Extract, Transform, Load) pipeline using Python and Pandas.

The pipeline processes raw sales data, cleans and transforms it, and produces an analytical dataset ready for reporting or BI tools.

---

## 📂 Project Structure

sales-etl-pandas/
├── etl-project/
│   ├── etl_sales_pipeline.ipynb
│   ├── requirements.txt
│   └── data/
│       ├── raw/
│       │   ├── customers.csv
│       │   ├── products.csv
│       │   └── sales.csv
│       └── processed/
│           └── sales_analytics.csv
└── README.md

---

## ⚙️ ETL Steps

### Extract
- Load CSV files (customers, products, sales)

### Transform
- Data type normalization  
- Date parsing  
- Handling missing values  
- Merging datasets  
- Revenue calculation  

### Load
- Export clean analytical dataset to CSV

---

## 🛠️ Technologies Used
- Python
- Pandas
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies:
```bash
pip install -r etl-project/requirements.txt
