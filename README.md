
---

## 📑 Dataset Overview

- **Uncleaned file**: `Uncleaned_DS_jobs.csv`  
  - 672 rows, 15 columns  
  - Contains raw job postings with inconsistent formatting, missing values, and combined fields.  

- **Cleaned file**: `Cleaned_DS_Jobs.csv`  
  - 660 rows, 27 columns  
  - Duplicates removed, missing values handled, and additional structured fields added (e.g., `min_salary`, `max_salary`, `city`, `skills`, `seniority`).  

---

## 🧹 Data Cleaning Steps

1. **Removed duplicates** → 672 → 660 rows.  
2. **Normalized text fields** (company names, job titles, locations).  
3. **Split salary field** into `min_salary`, `max_salary`, `salary_currency`, `salary_period`.  
4. **Extracted structured fields**: `city`, `state`, `country`, `seniority`, `skills`.  
5. **Converted datatypes** (dates → datetime, salaries → numeric, categories → categorical).  
6. **Handled missing values**: filled, standardized, or flagged as `NA`.  

---

## 📘 Usage

Clone this repository:

```bash
git clone https://github.com/<username>/DS-Jobs.git
cd DS-Jobs
