# 🚀 Indian Startup Funding Analysis (2015–2017)

An exploratory data analysis (EDA) project on startup funding deals in India, digging into where the money went, who gave it, and how the ecosystem evolved between 2015 and 2017.

---

## 📌 Overview

Between 2015 and 2017, thousands of Indian startups raised funding across multiple sectors, cities, and investor groups. This project cleans a real-world, messy funding dataset and answers 25+ business questions using pandas — covering top cities, top sectors, top investors, and deep-dive case studies on individual companies and investors.

## 📊 Key Insights

- **Funding follows a power law.** A handful of mega-rounds (Paytm, Flipkart, Ola) dominate total capital, while the median deal is only ~₹2.5 Cr.
- **The ecosystem was metro-centric.** Bangalore, Mumbai, and New Delhi captured the majority of both deal count and capital — tier-2/3 cities barely registered.
- **E-Commerce and Consumer Internet were the dominant sectors** by total capital raised.
- **2016 was the peak year** for funding activity (987 events), ahead of 2015 (753) and 2017 (441, partial-year data).
- **~37% of records have undisclosed funding amounts** — every total-capital figure in this analysis is a lower bound, not the true total raised.

*(Full write-up with all 25+ questions and answers is in the notebook.)*

## ❓ Questions This Analysis Raises

- Which of these funded startups are still operating today — does early funding predict long-term survival?
- Do investors like Sequoia or Accel specialize by sector, or diversify broadly?
- Does Bangalore's funding volume also translate to a higher success rate per startup, or just more activity?
- Are undisclosed-amount deals systematically smaller/larger or clustered in specific sectors?
- How much would rankings shift with rigorous entity resolution on startup/investor names?

## 🗂️ Dataset

| | |
|---|---|
| **File** | `startup_funding.csv` |
| **Rows** | 2,372 raw → 2,181 after cleaning |
| **Time period** | 2015 – 2017 |
| **Columns** | Date, Startup Name, Industry Vertical, Sub-Vertical, City, Investors, Investment Type (round), Amount (USD) |


## 🛠️ Tools & Libraries

- Python 3
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

## 📁 Project Structure

```
Indian-Startup-Funding-Analysis/
├── README.md
├── requirements.txt
├── Dataset/
│   └── startup_funding.csv
└── Startupfunding_Analysis.ipynb
```

## ▶️ How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/sahudkrum783-sketch/Indian-Startup-Funding-Analysis.git
   cd Indian-Startup-Funding-Analysis
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook
   ```bash
   jupyter notebook Startupfunding_Analysis.ipynb
   ```

## 🧭 Notebook Structure

1. **Data Cleaning** — handling nulls, renaming columns, currency conversion, date parsing
2. **Exploratory Data Analysis** — 25 business questions on startups, cities, sectors, rounds, and investors
3. **Investor-Column Analysis** — equal-split funding attribution per investor
4. **Single Investor Deep Dive** — case study on IDG Ventures
5. **Overall Analysis** — total capital deployed, funding trends over time
6. **Startup-Specific Analysis** — case study on Lenskart
7. **Key Insights & Conclusions** — summary of findings and open questions for further research


## 👤 Author

**Anushka Sahu**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/anushkasahu783/)
