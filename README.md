# Netflix_dataset

# Task 1: Data Cleaning and Preprocessing (Excel)

## 📋 Objective:
Clean and preprocess a raw dataset with missing values, duplicates, and inconsistent formats using **Microsoft Excel**.

## 🔧 Tools Used:
- Microsoft Excel

---

## 📁 Dataset:
- **Name:** Netflix Movies and TV Shows
- **Total Rows:** 8,807
- **Source:** Kaggle

---

## 🧹 Cleaning Steps Performed:

### 1. ✅ **Handled Missing Values**
- **Director** column had 2,634 missing values → Filled with `"Unknown Director"`
- **Cast** column had 825 missing values → Filled with `"Unknown Actor"`
- **Country** column had 831 missing values → Filled with `"Unknown Country"`
- **Date Added**, **Rating**, **Duration** had very few missing values → Replaced with `0` or `"Unknown"`

### 2. ❌ **Removed Duplicates**
- Used Excel’s **“Remove Duplicates”** feature to eliminate any repeated rows based on all columns.

### 3. 🔄 **Standardized Data Format**
- Made sure columns like **rating**, **duration**, and **release_year** had consistent formatting.
- Cleaned column names to make them more uniform (e.g., lowercased, no special characters).
- Dates were formatted to `DD-MM-YYYY`.

---

## 📌 Result:
A cleaned version of the Netflix dataset ready for basic data analysis. All missing values were handled, duplicate rows removed, and key columns standardized for consistency.

---

## 📁 Files Submitted:
- `original_dataset.xlsx` — Raw data
- `cleaned_dataset.xlsx` — Final cleaned dataset
- `README.md` — Summary of the steps performed
