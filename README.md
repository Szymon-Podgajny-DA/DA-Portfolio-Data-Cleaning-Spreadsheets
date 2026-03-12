# DA-Portfolio-Data-Cleaning-Spreadsheets

# 🧹 Cleaning Spreadsheet Data for Analysis

This mini project shows how I cleaned a small spreadsheet so it is easier to read, understand, and analyze in tools like Google Sheets or Excel.
I focused on removing noise (blank rows, extra spaces), unifying formatting, and adjusting the layout for analysis. ✨

---

## 🎯 Goal

Turn a messy spreadsheet into a clean, consistent table that is ready for basic analysis and reporting.  
The steps are simple on purpose so a recruiter can quickly see my practical spreadsheet skills.

---

## 📂 Files in this repo

- `data_cleaned.csv` – final cleaned version of the dataset, exported from the spreadsheet.
- `data_dirty.csv` – dirty version of the dataset, imported to the spreadsheet.
- `screenshot_data_errors.png` – examples of errors like blank rows/cells, whitespace highlighted.
  ![screenshot_data_errors](https://github.com/Szymon-Podgajny-DA/DA-Portfolio-Data-Cleaning-Spreadsheets/blob/main/screenshot_data_errors.png)
- `screenshot_data_cleaned.png` – screenshot of spreadsheet after removing errors.
  ![screenshot_data_cleaned](https://github.com/Szymon-Podgajny-DA/DA-Portfolio-Data-Cleaning-Spreadsheets/blob/main/screenshot_data_cleaned.png)
- `screenshot_transpose.png` – example of transposed data layout.
  ![screenshot_transpose](https://github.com/Szymon-Podgajny-DA/DA-Portfolio-Data-Cleaning-Spreadsheets/blob/main/screenshot_transpose.png)

---

## 🛠️ Tools

- Google Sheets.
- Built‑in features: filters, Data cleanup → Trim whitespace, Format → Clear formatting, Paste Special → Transpose, basic number formatting.

---

## 📌 Cleaning steps I took

1. **Import the data**
   - Opened the original file in a spreadsheet tool and checked the structure (columns, rows, headers).

2. **Remove rows with blank spaces using filters**
   - Applied a filter to the main data range.  
   - Filtered for blank rows and deleted them so the table is continuous and easier to work with.
3. **Remove extra spaces (Trim whitespace)**
   - Selected the range with messy text.  
   - Used: **Data → Data cleanup → Trim whitespace** to remove leading, trailing, and extra spaces inside the cells. 

4. **Add currency formatting to cost columns**
   - Selected the `UNIT COST` and `TOTAL` columns.  
   - Applied currency formatting with the `$` symbol so money values are clear and consistent.

5. **Unify formatting (Clear formatting)**
   - Selected the main data area.  
   - Used **Format → Clear formatting** to remove inconsistent styles, then re‑applied simple, clean formatting (font, size, alignment).

6. **Transpose part of the data**
   - Copied a selected range of cells (e.g., A1:H45).  
   - Right‑clicked a new cell (e.g., I1) and used **Paste special → Transposed** to switch rows and columns, creating an alternative layout for analysis.

7. **Basic visual formatting**
   - Adjusted column widths, added simple borders, and used bold headers so the table is easy to read at a glance.  
   - Kept the styling minimal and clean to highlight the data, not the decoration.

---

## 🔍 What this project demonstrates

- Practical use of spreadsheet features (filters, trim whitespace, clear formatting, transpose, number formatting) to clean real‑world data. 
- Attention to detail in formatting and layout so future analysis (filters, pivot tables, charts) is more reliable and easier to set up.  
- Ability to document a straightforward, reproducible cleaning workflow that other people can follow step by step. ✅


## 🔍 Key takeaways

- Removing blank rows and unnecessary spaces improves the consistency of IDs and names and reduces the risk of incorrect grouping in pivot tables and reports.
- Standardizing text (case, spaces, obvious typos) ensures that the same logical category is not accidentally split into multiple values during analysis.
- Even simple spreadsheet functions like `TRIM`, basic text functions, filters, and TRANSPOSE can significantly increase data quality before any advanced analysis or modeling begins.  
