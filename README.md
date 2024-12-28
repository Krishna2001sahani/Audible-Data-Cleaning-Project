# Audible Data Cleaning Project

## Project Overview
This project focuses on cleaning and standardizing an Audible dataset using Power Query Editor in Microsoft Excel. The goal is to prepare the dataset for analysis by ensuring data consistency, standardizing formats, and resolving any data-quality issues. 

---

## Dataset Link
[Download the Dataset](https://drive.google.com/file/d/1yjyozaSrwShoaROq-TDuSgC5HNLLmrTE/view?usp=sharing)

---

## Objectives

1. **Standardize the `Name` column**: Ensure all entries are in title case.
2. **Split the `Author` column**: Separate combined first and last names into two columns.
3. **Format the `Releasedate` column**: Ensure all entries follow the format `DD-MM-YYYY`.
4. **Convert the `Time` column**: Change from text format to a duration format recognized by Excel.
5. **Clean the `Price` column**: Convert to numeric format, handle non-numeric values, and ensure two decimal places.
6. **Transform the `Stars` column**: Convert text-based ratings to numeric values.
7. **Split the `Narratedby` column**: Separate multiple narrators into individual columns.
8. **Create a `Releaseinfo` column**: Merge `Releasedate` and `Language` columns with the format `DD-MM-YYYY, Language`.

---

## Steps to Clean the Dataset

### 1. Open Power Query Editor
- Import the dataset into Excel.
- Navigate to **Data > Get & Transform Data > Launch Power Query Editor**.

### 2. Data Cleaning Tasks

#### **2.1 Standardize Name Column**
- Apply title casing to the `Name` column using **Transform > Format > Capitalize Each Word**.

#### **2.2 Split Author Column**
- Split the `Author` column by delimiter (space) into `First Name` and `Last Name`.

#### **2.3 Format Releasedate Column**
- Convert the `Releasedate` column to date format and ensure consistency in `DD-MM-YYYY`.

#### **2.4 Convert Time Column**
- Change the `Time` column from text to duration format, splitting hours, minutes, and seconds if necessary.

#### **2.5 Clean Price Column**
- Convert the `Price` column to numeric format and handle any non-numeric values.
- Ensure all values are displayed with two decimal places.

#### **2.6 Transform Stars Column**
- Replace text-based ratings (e.g., "Five") with numeric equivalents.
- Convert the column to numeric format.

#### **2.7 Split Narratedby Column**
- Split the `Narratedby` column by delimiter (comma) into separate columns for each narrator.

#### **2.8 Create Releaseinfo Column**
- Merge `Releasedate` and `Language` columns with a delimiter to create the new column `Releaseinfo` (e.g., `DD-MM-YYYY, Language`).

### 3. Save Cleaned Dataset
- After completing all transformations, load the cleaned data back into Excel and save the file.

---

## Deliverables

1. **Cleaned Dataset**
   - The cleaned dataset is saved in Excel format and shared via a downloadable link.

2. **PowerPoint Presentation**
   - A detailed presentation with screenshots and explanations of each cleaning step.

---

## Tools and Technologies Used
- Microsoft Excel
- Power Query Editor

---

## Instructions for Submission
1. Upload the cleaned dataset to a cloud drive and provide the link.
2. Attach the PowerPoint presentation with all screenshots and descriptions of the cleaning process.

---

## Contact
If you have any questions or need further assistance, feel free to reach out!

Happy analyzing!
