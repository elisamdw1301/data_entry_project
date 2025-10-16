# 📚 Data Entry Project — Superstore Dataset

---

## 📄 Project Overview
This project simulates a **real data entry task**, where data from a PDF file is **typed manually into Google Sheets**, cleaned, validated, and prepared for use by analysts or clients. The dataset is a **dummy version of a retail dataset (100 rows)** created for training and portfolio purposes.


The goal is to demonstrate:
-  Accurate manual data entry from a non-editable source (PDF)  
-  Consistent data formatting and cleaning using Google Sheets  
-  Systematic validation and quality assurance process  
-  Clear and professional documentation for portfolio presentation

---

## 🧠 Tools & Skills Used
| Tools                 | Used                                                          |
|---------------------- | --------------------------------------------------------------|
| **Google Sheets**     | Manual entry, formatting, cleaning, and validation            |  
| **PDF**               | Source file for data entry                                    |
| **Excel (.xlsx)**     | Final cleaned dataset                                          |
| **Formulas**          | `PROPER`, `ISNUMBER`, `IF`, `FILTER`, `EXACT`, `LEN`, `UPPER` |
| **Markdown (README)** | Documentation on GitHub                                       |

---

## 🪄 Project Workflow

### 1. Manual Data Entry
- Entered **100 rows** of dummy retail data manually from PDF into Google Sheets (`raw_data` tab).  
- Followed the original structure from the PDF.
- Ensured all data was entered consistently, including dates, currency, and text capitalization.

---

### 2. Data Formatting
- Reformatted **dates** to `MM/DD/YYYY` across the dataset.  
- Converted numeric fields (`sales`, `quantity`, `discount`, and `profit`) from text to number formats.  
- Applied `PROPER()` to standardize text capitalization (`product_name`, `customer_name`, `city`, and `state`).  
- Used `UPPER()` to convert all text characters in a specified cell to uppercase (capital) letters.
- Used `LEN()` to count all text characters in a specified cell. 
- Verified each column to ensure correct data types.

---

### 3. Data Validation & Cleaning
After formatting, several validation checks were performed to ensure data consistency:

| Check Type            | Description                                   | Result                                         |
|-----------------------|-----------------------------------------------|------------------------------------------------|
| Duplicate Check       | Identify exact duplicate rows                 | 6 duplicates found                             |
| Empty Cell Check      | Ensure no critical fields were blank          | 5 cells with empty values detected             |
| Date Consistency      | Ship Date must be ≥ Order Date                | No error detected                              |
| Numeric Validation    | Quantity > 0                                  | No error detected                              |
| Text Formatting       | Check for inconsistent casing                 | Cleaned using PROPER                           |

Detailed findings and actions are documented in the **Validation_Notes** tab inside the Google Sheets file.

---

### 4. Quality Assurance (QA)
To ensure high data accuracy:
- Selected **10 random rows** from the cleaned dataset.  
- Manually compared each field (Order ID, dates, numbers, text) with the original PDF source.  
- **100% match** between PDF and cleaned data during the QA check.

---

### 5. Finalization
- Saved cleaned dataset as `cleaned_data_final.xlsx`.  
- Uploaded to GitHub as part of my data entry portfolio.

---

## 📂 File Descriptions

| File                            | Description                                       | Link |
|---------------------------------|---------------------------------------------------|---------------- |
| `raw_data.pdf`                  | Dummy dataset source (PDF, 100 rows)              | [See the table](https://drive.google.com/file/d/1wLiC-IoMwC90UdaTBnef-A58EaZrZym3/view?usp=sharing) |
| `manual_data_entry.csv`         | The result of manual data entry, before cleaning  | [See the table](data/02_manual_data_entry.csv) | 
| `cleaned_data_final.xlsx`       | Final cleaned dataset, ready for use              | [See the table](https://docs.google.com/spreadsheets/d/13atDfoFfYOcI8OQu4fWFTuT6p3n7v5zo/edit?usp=sharing&ouid=101185424288016451803&rtpof=true&sd=true) or [Download file](data/03_cleaned_data_final.xlsx) |
| `superstore_data_entry_project` | Sheet 1 : raw_data                                | [See the table](https://docs.google.com/spreadsheets/d/10G_UGdhbpiiDNO0kkxiHV3qmrgS8DRpXKDiTo1uFcIQ/edit?usp=sharing) |
|                                 | Sheet 2 : cleaned_data                            | |
|                                 | Sheet 3 : validation_notes                        | |
| `README.md`                     | Project overview and summary                      | |

---

## 📝 Key Skills Demonstrated
-  Manual data entry from PDF to Google Sheets with accuracy  
-  Data formatting, standardization, and cleaning  
-  Duplicate detection and logical validation  
-  Use of formulas for data quality checks  
-  Professional documentation for portfolio presentation

---

## 📌 Author
🧾 **Elisa Martiana Dewi**     |      Data Entry Enthusiast          
📧 Email     : elisa.martiana.dewi1301@gmail.com  
🔗 LinkedIn  : [linkedin.com/in/elisa-martiana-dewi1301](https://www.linkedin.com/in/elisa-martiana-dewi1301/)   
💻 GitHub    : [github.com/elisamdw1301](https://github.com/elisamdw1301)

---

## ⚠️ Disclaimer
This dataset is **dummy data created for training and portfolio purposes only**.  
No real customer information is included in this project.



