# World Bank Development Indicators — Power BI

> Interactive **Power BI dashboard** visualising World Bank development indicators (2000–2021) across countries and regions.

---

## 🎯 Goal

Turn the World Bank's global development dataset into a browsable, comparative view — so a user can pick a country, a region, or an indicator and immediately see the trend.

## 🖼️ Preview

![World Bank dashboard page 1](img/wb-1.jpg)
![World Bank dashboard page 2](img/wb-2.jpg)

## 🧩 What's Inside

- **Country & region** selectors
- **Multi-indicator** trend charts (GDP, life expectancy, inflation, population, etc.)
- **2000–2021 time window** with year slicer
- Comparison views across regions

## 🧪 Methodology

1. Ingested World Bank indicators CSV via Power Query
2. Unpivoted year columns into a long-format fact table
3. Built `dim_country`, `dim_indicator`, `dim_date` dimensions
4. Wrote DAX measures for indexed comparisons and CAGR
5. Designed report pages by theme (macro, social, demographic)

## 🧰 Tech Stack

`Power BI Desktop` · `Power Query (M)` · `DAX` · Public World Bank open data

## 📁 Repo Structure

```text
.
├── dashboard/
│   └── World_Bank_Indicators_2000-21.pdf
├── pbix/
│   └── world_bank_indicators.pbix
├── img/
└── README.md
