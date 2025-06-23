# TASK -1-Data-Cleaning-and-Preprocessing

#  Netflix Data Cleaning and Preprocessing

This project demonstrates how to clean and preprocess a raw dataset using **Python and Pandas** on **Google Colab**. The dataset contains metadata about Netflix titles. After cleaning, a refined CSV file is saved and ready for analysis.

---
#THE DATASET USED FOR THIS TASK IS NETFLIX MOVIES AND TV SHOWS FROM KAGGLE

## 🧾 Dataset Overview

- **Source File**: `netflix_titles.csv.xlsx`
- **Cleaned Output**: `netflix_cleaned.csv` (included in this repo)
- **Platform Used**: [Google Colab](https://colab.research.google.com)

### 📦 Dataset Size Comparison

| Version           | Rows  | Columns |
|-------------------|-------|---------|
| Original Dataset  | 8,807 | 12      |
| Cleaned Dataset   | 8,797 | 12      |

---

## 🧼 Cleaning Steps Performed

- ✅ Renamed column headers to lowercase and replaced spaces with underscores
- ✅ Removed duplicate rows
- ✅ Converted `date_added` to `dd-mm-yyyy` format
- ✅ Handled missing values (`Unknown`, `Not Rated`, or row dropped)
- ✅ Standardized text fields (e.g., “tv show” → “Tv Show”)
- ✅ Ensured correct data types (`release_year` as integer)
- ✅ Saved final dataset as `netflix_cleaned.csv`




