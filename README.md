# 🎧 Music Tours Dataset — Data Cleaning Project

This repository contains a small but structured data cleaning project focused on a dataset of major music tours.  
The goal is to transform a raw, inconsistent dataset into a clean, analysis‑ready version using a transparent and reproducible workflow.

---

## 📁 Project Structure

The project is organized into three main components:

- **RAW_IMPORT**  
  The original dataset exactly as collected, including formatting issues, symbols, and inconsistencies.

- **CLEAN_TABLE**  
  A fully cleaned and standardized version of the dataset.  
  All columns are generated through formulas referencing *Raw_Data*, ensuring the possibility of updates when new rows are added.

- **NOTES**  
  A detailed log of the cleaning process, documenting:
  - issues found in each column  
  - cleaning actions performed  

This structure ensures clarity, reproducibility, and easy maintenance.

---

## 🧹 Data Cleaning Overview

The raw dataset contained several common issues:

- bracketed notes
- currency symbols and thousand separators
- inconsistent hyphens and spacing
- special characters not relevant to analysis
- numeric fields stored as text
- year ranges requiring extraction
- reference markers with no analytical value

To address these, a column‑by‑column cleaning strategy was applied.

---

## 📦 Final Output

The final cleaned dataset includes:

- normalized text fields  
- standardized numeric fields  
- derived fields (e.g., StartYear, EndYear)  
- no duplicates  
- no formatting artifacts  
- no non‑analytical columns  

This dataset is ready for use in analysis, visualization tools, or further transformation.

---
