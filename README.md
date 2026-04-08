# FreshMart Data Cleaning

A Python + Pandas practical case study focused on cleaning messy retail sales data for analysis.

This excercise is based on a data cleaning exercise where the goal is to clean a dirty dataset, handle missing values, standardize inconsistent entries, remove duplicates, fix invalid values, handle outliers, and recalculate totals correctly. :contentReference[oaicite:0]{index=0}

---

## Project Objective

FreshMart, a retail company operating in Namibia, collected sales data from multiple branches, but the dataset contains inconsistencies due to poor data entry practices.

The purpose of this project is to:

- Load and inspect the dataset
- Clean missing and invalid values
- Standardize text-based fields
- Remove duplicate records
- Handle outliers and data errors
- Recalculate the total amount
- Export a final clean dataset

The practical specifically requires use of `freshmart_dirty.csv` and submission of both the cleaned dataset and the Python code. :contentReference[oaicite:1]{index=1}

---

## Repository Structure

```bash
freshmart-data-cleaning/
│
├── data/
│   ├── raw/
│   │   └── freshmart_dirty.csv
│   └── processed/
│       └── clean_freshmart.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── src/
│   └── cleaning.py
│
├── outputs/
│   └── screenshots/
│
├── requirements.txt
├── .gitignore
└── README.md
