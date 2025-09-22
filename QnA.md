# Interview Questions & Answers (Task 1: Data Cleaning)

### 1. What are missing values and how do you handle them?
- Missing values occur when no data is stored for a cell.
- Methods to handle:
  - Drop missing values (`dropna()`).
  - Fill with mean/median/mode (for numeric).
  - Fill with "Unknown" or most frequent category (for categorical).

---

### 2. How do you treat duplicate records?
- Remove them using `.drop_duplicates()`.
- Duplicates can bias results and inflate counts.

---

### 3. Difference between dropna() and fillna() in Pandas?
- `dropna()` removes rows/columns with nulls.
- `fillna()` replaces nulls with a specified value.

---

### 4. What is outlier treatment and why is it important?
- Outliers are extreme values outside normal range.
- They can skew averages and affect ML models.
- Methods: capping, transformation, or removal.

---

### 5. Explain the process of standardizing data.
- Converting inconsistent values into a uniform format.
  - Same case (lower/upper).
  - Standard date format (e.g., yyyy-mm-dd).
  - Unified categories (e.g., `male`, `female`).

---

### 6. How do you handle inconsistent data formats (e.g., date/time)?
- Use Pandas `pd.to_datetime()` to convert to uniform datetime format.

---

### 7. What are common data cleaning challenges?
- Missing values  
- Duplicates  
- Inconsistent formats  
- Outliers  
- Wrong data types  

---

### 8. How can you check data quality?
- By validating:
  - **Completeness** (no missing values),
  - **Consistency** (uniform format),
  - **Accuracy** (matches real-world),
  - **Uniqueness** (no duplicates),
  - **Validity** (correct data types).
