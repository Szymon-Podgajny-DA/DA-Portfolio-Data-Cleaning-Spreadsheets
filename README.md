# DA-Portfolio-Data-Cleaning-Spreadsheets
Preparing data for analysis in spreadsheets.

# 🧹 Data Cleaning in Spreadsheets

Small portfolio project showing how I turn **messy survey/operational data** into clean, analysis‑ready data using Google Sheets. 

---

## 🎯 Business problem

A stakeholder shared raw survey / operational data stored in a spreadsheet.  
In its original form, the dataset contained empty rows, inconsistent text formatting, extra spaces, and a layout that was not convenient for analysis.[web:4][web:23]  
My goal was to clean and restructure the data so it is consistent, reliable, and ready for filtering, pivot tables, and basic reporting.[web:17][web:22]  

---

## 📂 Repository contents

- `data_cleaned.csv` – final cleaned dataset exported from the spreadsheet.  
- `screenshot_blank_rows_before_after.png` – removing blank rows (before vs. after).  
- `screenshot_trim_before_after.png` – cleaning extra spaces and text formatting (TRIM, case) before vs. after.[web:7][web:21]  
- *(optional)* `screenshot_transpose_before_after.png` – example of changing the layout of a small data snippet using TRANSPOSE.[web:4]  

---

## 🛠️ Tools and functions

- Google Sheets as the main tools for manual data cleaning.
- Spreadsheet functions such as `TRIM`, basic text case adjustments, filtering, sorting, and simple formulas to standardize values. 

---

## 📌 Cleaning steps 

1. **Remove structural noise (blank rows, obvious issues)**
   - Identified blank rows that appeared within the main data range.  
   - Removed those rows so the dataset became continuous and easier to select, filter, and analyze.[web:4][web:22]  

2. **Clean text values (spaces, case, minor typos)**
   - Applied the `TRIM` function to remove leading, trailing, and repeated spaces in key text fields such as names or locations. 
   - Standardized text case (for example, turning variations like `warszawa`, `Warszawa `, `WARSZAWA` into a single, consistent format).  

3. **Adjust layout with TRANSPOSE (when useful)**
   - For a small portion of the data, used TRANSPOSE to switch from a row‑based layout to a column‑based layout (or the other way around) to make the table easier to read and summarize.  

5. **Export cleaned data**
   - Saved the final, cleaned worksheet as a CSV file so it can be easily reused in other tools (SQL, Python, BI tools, or future spreadsheet analysis).

---

## 📊 Screenshots (before / after)

- **Blank rows – before / after**  
  A zoomed‑in view of a section of the dataset showing blank rows inside the data range, and the same section after removing them (no gaps in row numbers).
- **TRIM and text cleaning – before / after**  
  Two columns side by side:  
  - left column with raw values containing extra spaces and inconsistent capitalization,  
  - right column with cleaned values produced using `TRIM` and text case adjustments.[web:7][web:21]  

- *(optional)* **Transpose – before / after**  
  A small snippet of data in its original layout and the same snippet after applying TRANSPOSE to change the orientation for easier analysis.[web:4]  

---

## 🔍 Key takeaways

- Removing blank rows and unnecessary spaces improves the consistency of IDs and names and reduces the risk of incorrect grouping in pivot tables and reports.[web:4][web:22]  
- Standardizing text (case, spaces, obvious typos) ensures that the same logical category is not accidentally split into multiple values during analysis.[web:7][web:21][web:25]  
- Even simple spreadsheet functions like `TRIM`, basic text functions, filters, and TRANSPOSE can significantly increase data quality before any advanced analysis or modeling begins.[web:7][web:21][web:24]  

---

## ✅ What this project shows

This project demonstrates my **practical data‑cleaning workflow in spreadsheets**: importing raw data, fixing structural issues, cleaning text, adjusting layout, and exporting a clean CSV file ready for analysis.[web:4][web:23]  
It focuses on the “before analysis” step that often takes a large portion of a data analyst’s time but is crucial for trustworthy insights 😊
