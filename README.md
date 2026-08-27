# Excel Data Analysis & Processing Portfolio

## Project Overview
This repository contains a comprehensive set of Excel projects focused on data exploration, cleaning, transformation, and conditional logic. The goal of this portfolio is to process raw product data into structured, standardized datasets ready for analysis using native Excel formulas and built-in features.

---

## Repository File Structure

* `Excel Assignment 1 - Data Exploration.xlsx` — Excel workbook containing exploratory statistics, logical conditions, and text extractions.
* `Assignment 2 - Data Cleaning and Transformation.xlsx` — Master Excel workbook containing cleaned datasets and advanced transformation tasks.
* `assignment-docs/` — Directory storing the original task PDF instructions.

---

## Task Documentation Links (Assignment 2)

* [Task 1 - Missing Value Imputation](assignment-docs/Task%201%20-%20Missing%20Value.pdf)
* [Task 2 - Text Standardization](assignment-docs/Task%202%20-%20Text%20Standardization.pdf)
* [Task 3 - Text to Columns Delimiter Setup](assignment-docs/Task%203%20-%20Text%20to%20Columns%20Delimiter%20Setup.pdf)
* [Task 4 - Date Parsing & Currency Formatting](assignment-docs/Task%204%20-%20Date%20Parsing%20%26%20Currency%20Formatting.pdf)
* [Task 5 - Final Dataset with Conditional Formatting](assignment-docs/Task%205%20-%20Final%20Dataset%20with%20Conditional%20Formatting.pdf)

---

## Key Tasks & Summaries

### Module 1: Data Exploration (Assignment 1)
* **Descriptive Statistics:** Summarized key pricing metrics using `SUM`, `COUNTA`, `AVERAGE`, `MIN`, and `MAX`.
* **Logical & Conditional Analysis:** Categorized items priced at $500+ as 'High Price' using `IF`, aggregated category totals using `SUMIF`, and counted items under $100 using `COUNTIF`.
* **Text Extraction:** Parsed custom `Product ID` strings into discrete attributes (`Day`, `Month`, `Country Code`) using `LEFT`, `MID`, and `RIGHT`.

### Module 2: Data Cleaning & Transformation (Assignment 2)
* **Missing Value Imputation:** Filled absent price records using category-level averages (`AVERAGEIF`)[cite: 3].
* **Text Standardization:** Resolved incomplete string labels (e.g., standardizing `Electroni` to `Electronics`)[cite: 7].
* **Delimiter Setup:** Separated concatenated values into standard columns using *Text to Columns* with hyphen delimiters[cite: 6].
* **Date & Currency Formatting:** Parsed text values into `DD-MM-YYYY` format using `DATEVALUE` and applied currency formatting (`$`)[cite: 4, 5].
* **Conditional Formatting:** Applied custom rules to highlight target categories dynamically[cite: 4].
