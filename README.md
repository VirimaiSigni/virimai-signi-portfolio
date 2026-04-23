# 🐍 Virimai Signi | Python Data Automation Portfolio

> **15 years in sales & finance + Python automation = Business intelligence that actually saves time**

[![Live Demo](https://img.shields.io/badge/Live-Demo-green)](https://your-username.github.io/your-repo-name)
[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-red)](https://pandas.pydata.org)
[![Power BI](https://img.shields.io/badge/Power%20BI-Expert-yellow)](https://powerbi.microsoft.com)

## 📊 What I Do

I turn messy business data into **clean, automated reporting systems**. With 15 years of hands-on experience in sales and finance, I don't just write code—I understand what numbers actually matter to business leaders.

### My Toolkit

| Category | Technologies |
|----------|--------------|
| **Data Extraction** | `tabula-py`, `pdfplumber`, `PyPDF2`, `camelot` |
| **Data Manipulation** | `pandas`, `numpy`, `SQL`, `ETL pipelines` |
| **Excel Automation** | `openpyxl`, `xlsxwriter`, `xlwings` |
| **Visualization** | `Power BI`, `matplotlib`, `seaborn` |
| **Web Development** | `HTML5`, `CSS3`, `JavaScript`, `React` |

## 🚀 Featured Python Projects

### 1. PDF to Excel Converter (Live Demo)
**Problem**: Manual data entry from PDF invoices took 10+ hours weekly.

**Solution**: Python script using `tabula-py` and `pandas` that extracts tables from any PDF and exports to clean Excel.

```python
import tabula
import pandas as pd

# Extract tables from PDF
tables = tabula.read_pdf("invoice.pdf", pages="all")
df = pd.concat(tables)
df.to_excel("extracted_data.xlsx", index=False)
