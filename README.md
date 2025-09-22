# Task 1: Data Cleaning and Preprocessing

## 📌 Objective
To clean and preprocess a raw dataset (with missing values, duplicates, and inconsistent formats) using Python (Pandas).
**Please find the Task1.pdf for more clarity**
Dataset Used: **Netflix Movies and TV Shows (Kaggle)**

---

## 🔧 Steps Performed
1. **Loaded dataset** into Pandas.
2. **Checked missing values** using `.isnull().sum()`.
3. **Handled missing values**:
   - Filled missing `director` and `country` with `"unknown"`.
4. **Removed duplicates** using `.drop_duplicates()`.
5. **Standardized text values** (e.g., all lowercase, trimmed spaces).
6. **Converted date formats** (`date_added` → `datetime`).
7. **Renamed columns** to be lowercase with underscores.
8. **Validated data types** (ensured `date_added` is datetime).
9. **Saved final dataset** as `netflix_titles_cleaned.csv`.

---

## 📊 Summary of Changes
- Removed **245 duplicate records**.
- Filled **4,929 missing director values** with `"unknown"`.
- Filled **831 missing country values** with `"unknown"`.
- Converted `date_added` into proper `datetime`.
- Renamed columns like `Date Added → date_added`.
- Standardized all categorical fields (e.g., `country`, `type`) to lowercase.

Final dataset contains **8,807 records**.

---

## 📂 Files Included
- `raw_netflix.csv` → Original dataset.
- `task1-data-cleaning.ipynb` → Databricks Notebook with cleaning code.
- `netflix_titles_cleaned.csv` → Cleaned dataset.
- `task1-data-cleaning.html` → Output of the Notebook with code.
- `README.md` → Summary of work.
- `QnA.md` → Interview questions & answers.

---



