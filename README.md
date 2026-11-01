# Task 23 — Duplicate Data Removal Using Pandas

## Project Overview

This project demonstrates how to identify and remove duplicate records from a dataset using Python and Pandas.

A sample student performance dataset is used to identify repeated records, remove duplicates, and compare the dataset size before and after cleaning.

## Objectives

- Identify duplicate records using `duplicated()`.
- Count the total number of duplicate entries.
- Display duplicate-related records.
- Remove duplicates using `drop_duplicates()`.
- Verify the cleaned dataset.
- Compare the number of records before and after cleaning.

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook

## Dataset Description

The project uses a manually created student dataset containing 11 records and six columns:

- student_id
- name
- department
- age
- marks
- attendance

Three exact duplicate entries are intentionally included for demonstration.

## Pandas Functions Used

- `df.duplicated()` — identifies repeated rows.
- `df.duplicated(keep=False)` — identifies every occurrence belonging to duplicate groups.
- `df.duplicated(subset=["student_id"])` — identifies repeated student IDs.
- `df.drop_duplicates()` — removes duplicate rows.
- `len(df)` — counts dataset records.
- `to_csv()` — exports the original and cleaned datasets.

## Results

| Description | Count |
|---|---:|
| Records before cleaning | 11 |
| Duplicate records removed | 3 |
| Records after cleaning | 8 |
| Remaining duplicate records | 0 |

## Project Files

- `Task_23_Duplicate_Data_Removal.ipynb` — Google Colab notebook.
- `student_records_with_duplicates.csv` — Original dataset.
- `duplicate_records.csv` — Duplicate-related records.
- `cleaned_student_records.csv` — Cleaned dataset.
- `duplicate_summary.csv` — Before-and-after comparison.
- `requirements.txt` — Required libraries.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `screenshots/` — Project execution evidence.

## Key Learnings

- Identifying duplicate records in Pandas.
- Understanding Boolean duplicate detection.
- Removing repeated observations.
- Comparing dataset sizes before and after cleaning.
- Verifying data quality after cleaning.

## Conclusion

This project demonstrates how Pandas can identify and remove duplicate records. It highlights the importance of eliminating unintended repetitions before performing statistical analysis or developing machine-learning models.
