# 📊 Kenya Debt Dashboard: Visualizing Public Borrowing with Power BI

### 🇰🇪 A Comprehensive Analysis of Kenya’s Public Debt (2000–2023)

This project uses official debt data from Kenya's National Treasury to create an interactive Power BI dashboard. It helps users explore how Kenya's public debt has evolved over time, how it's structured (domestic vs external), who the major creditors are, and what risks exist in terms of currency exposure and repayment timelines.

---

## 📁 Folder Structure

Debt_Project:
  Kenya's Debt.pbix: "Power BI Dashboard file"
  Kenya’s_Fiscal_Landscape_(2000–2023)...ipynb: "Jupyter notebook (Python version)"
  Data:
    Debt answers.xlsx: 
    kenya_debt_analysis.csv: 
  Images:
    Overview.png: "Overview dashboard screenshot"
    Domestic Debt.png: "Domestic debt dashboard screenshot"
    External Debt.png: "External debt dashboard screenshot"
    Data.png: "Data structure or sample screenshot"


---

## 🔍 Project Goals

- Understand the structure of Kenya's public debt  
- Visualize changes in debt composition over time  
- Identify key lenders, instruments, currencies, and repayment risks  
- Make public finance data more accessible and interactive

---

## 📊 Dashboard Sections

### 1. Overview Page
- Total public debt by year
- Debt-to-GDP ratio
- Debt service as % of revenue
- Domestic vs external debt composition

![Overview](Image/Overview.png)

---

### 2. Domestic Debt
- By instrument (bills, bonds, pre-1997)
- By holder (banks, non-banks, non-residents)
- By tenor (short, mid, long-term)

![Domestic Debt](Images/Domestic%20Debt.png)

---

### 3. External Debt
- By creditor category (bilateral, multilateral, commercial banks)
- By major creditors (e.g., China, IDA, Japan)
- By currency (USD, EUR, Yen, Yuan)
- By maturity (short-, medium-, long-term)

![External Debt](Images/External%20Debt.png)

---

### 4. Interactive Filters
- Year slicer (defaults to latest year)
- Dynamic cards and responsive charts
- Drill-downs and tooltips for better data navigation

---

## 📊 Data Files

These cleaned datasets power the dashboard and can be reused for other analysis:

- `Data/DebtAnswers.xlsx` – Unpivoted public debt composition by year, including categories like creditor, currency, maturity, and instrument.
- `Data/kenya_debt_analysis.csv` – A reference table used for DAX-based year filtering and dynamic defaults in the dashboard.

---

## 🧰 Tools & Technologies

| Tool        | Use Case                             |
|-------------|--------------------------------------|
| **Power BI** | Dashboard building & DAX calculations |
| **Excel**    | Data extraction & initial cleaning    |
| **Python**   | Jupyter notebook version of the analysis *(optional)* |
| **GitHub**   | Version control and project sharing   |

---

## 📈 Key Insights

- Debt-to-GDP ratio has increased sharply post-2013  
- Domestic debt is mostly held by banks and issued as bonds  
- External debt is concentrated among a few major creditors  
- Foreign currency exposure introduces FX risk  
- Debt servicing consumes a growing share of ordinary revenue

---

## 📂 Data Source

Data was extracted from Kenya’s official **Annual Public Debt Reports**, published by the National Treasury.  
*Note: Raw data was cleaned, restructured, and unpivoted for use in the dashboard.*

---

## 💬 How to Explore

- Clone or download this repository  
- Open the `.pbix` file in Power BI Desktop  
- Use the year slicer and explore each tab  
- Review the `Data/` folder for datasets  
- Check the `Images/` folder for dashboard screenshots

---

## 📣 Author

**Kiruru Kamau**  
📧 kamaukiruru@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/timothy-kamau-379133234)  
📝 [Substack](#) *(https://open.substack.com/pub/kedatalab/)
---


## ✅ To Do (Optional Enhancements)

- Automate data scraping from PDFs  
- Add a county-level breakdown  
- Add forecasting for debt servicing needs  
- Publish public web version via Power BI Service
)*

---
