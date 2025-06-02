Netflix Dataset Cleaning - Task 1 (Data Analyst Internship)

## 🧹 Objective:
Clean and preprocess the raw Netflix Movies and TV Shows dataset to make it ready for analysis.

## ✅ Steps Performed:

1. *Handled Missing Values*:
   - Checked all columns using .isnull()
   - No missing values found

2. *Removed Duplicates*:
   - Checked for duplicates using .duplicated()
   - No duplicate rows found

3. *Standardized Text Columns*:
   - Stripped leading/trailing whitespace from all string columns

4. *Date Formatting*:
   - Converted date_added column to consistent datetime format with dayfirst=True

5. *Column Renaming*:
   - Renamed all column headers to lowercase and snake_case

6. *Verified Data Types*:
   - Confirmed all columns have appropriate data types (e.g., date_added as datetime, release_year as integer)

## 📁 Output:
Cleaned dataset with 5348 rows and 12 columns



## 🗃 Dataset Source:
- [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

Prepared for *Task 1* of the *Data Analyst Internship*.
