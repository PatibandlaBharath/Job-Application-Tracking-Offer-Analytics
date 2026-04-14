# 📊 Job Application Tracking & Offer Analytics Dashboard

An Excel-based dashboard for tracking job applications, monitoring recruitment pipeline stages, and analyzing offer trends across companies, roles, locations, and salary bands.

---
![Dashboard_page-0001](https://github.com/user-attachments/assets/dc0baaaa-c497-4cb6-bc6e-c0ce99f0b353)


## 🗂️ Sheet Overview

| Sheet | Description |
|---|---|
| **Job Data** | Raw dataset of 100 job applications with 16 fields per entry |
| **Dashboard** | Visual overview of application pipeline and key metrics |
| **Recruitment** | Recruiter-level breakdown and sourcing analysis |
| **Experience** | Analytics segmented by years of experience |
| **Salary** | Salary range and CTC comparison views |
| **Pivot Tables** | Pre-built pivot summaries by company, skills, and experience |

---

## 🔢 Dataset — `Job Data` Sheet

The core dataset contains **100 application records** across **16 columns**.

### Columns

| Column | Type | Description |
|---|---|---|
| `Company` | Text | Hiring company name |
| `Role` | Text | Job role applied for |
| `Status` | Text | Current application status |
| `Date Applied` | Date | Date the application was submitted |
| `Location` | Text | Job location / city |
| `Salary` | Number | Offered or expected salary (₹) |
| `Experience` | Number | Candidate's years of experience |
| `Education` | Text | Highest qualification |
| `Skills` | Text | Semicolon-separated skill tags |
| `Interview Score` | Number | Score from the interview round (0–100) |
| `Offer Accepted` | Text | Whether the offer was accepted (`Yes` / `No`) |
| `Notice Period` | Number | Notice period in days |
| `Current CTC` | Number | Candidate's current CTC (₹) |
| `Expected CTC` | Number | Candidate's expected CTC (₹) |
| `Recruiter Name` | Text | Name of the recruiter involved |
| `Application Source` | Text | Channel through which the application was made |

---

## 📌 Key Data Points

### Companies Covered (19)
Accenture, Amazon, Capgemini, Cognizant, Deloitte, Flipkart, Google, HCL, IBM, Infosys, Microsoft, Oracle, Paytm, Swiggy, TCS, Tech Mahindra, Wipro, Zoho, Zomato

### Roles
Analyst · Consultant · Developer · Engineer · Manager · Operations · SDE · Tester

### Application Statuses
| Status | Count |
|---|---|
| Offer | 28 |
| Interview | 28 |
| Rejected | 23 |
| Applied | 21 |

### Locations
Bangalore · Chennai · Hyderabad · Mumbai · Mysore · Noida · Pune

### Education Levels
B.Tech · MBA · BBA · B.Sc

### Application Sources
LinkedIn · Naukri · Referral

### Salary Range
₹3,58,017 — ₹27,46,588

### Experience Range
1 – 6 years

### Offer Acceptance Rate
**28%** (28 of 100 applications resulted in an accepted offer)

---

## 📊 Analytics & Dashboard Features

- **Pipeline Overview** — Track applications across all four stages (Applied → Interview → Offer → Accepted)
- **Company-wise Breakdown** — Application volume and conversion rates per company
- **Skills Analysis** — Frequency and experience distribution by skill tags
- **Salary Comparison** — Current CTC vs. Expected CTC vs. Offered Salary
- **Recruiter Performance** — Source and recruiter-level tracking
- **Experience Segmentation** — Offer rates and interview scores by years of experience
- **Location Heatmap** — Application and offer distribution across Indian cities

---
# 📊 Job Application Tracking & Offer Analytics Dashboard

> An Excel-based dashboard to track job applications, monitor recruitment pipelines, and analyze offer trends across companies, roles, locations, and salary bands — built for the Indian job market.

---

## 🚦 Pipeline at a Glance

| 🟢 Offers | 🟡 Interviews | 🔵 Applied | 🔴 Rejected | 📁 Total |
|:---------:|:-------------:|:----------:|:-----------:|:--------:|
| **28** | **28** | **21** | **23** | **100** |
| 28% rate | Active pipeline | Awaiting response | 23% rate | 19 companies |

---

## 📈 KPI Summary

```
┌─────────────────────────┬──────────────────────────┬─────────────────────────┐
│  🏆 Offer Rate          │  🎯 Avg Interview Score  │  👤 Avg Experience      │
│         28%             │        76.8 / 100        │       3.6 years         │
├─────────────────────────┼──────────────────────────┼─────────────────────────┤
│  💰 Avg Salary Offered  │  📈 Avg Expected CTC     │  📉 Avg Current CTC     │
│      ₹16,98,104         │      ₹18,72,545          │      ₹15,69,689         │
└─────────────────────────┴──────────────────────────┴─────────────────────────┘
```

---

## 💼 Salary Insights

| Metric | Amount (₹) |
|--------|-----------|
| 💹 Minimum Salary Offered | ₹3,58,017 |
| 📊 Average Salary Offered | ₹16,98,104 |
| 🚀 Maximum Salary Offered | ₹27,46,588 |
| 📌 Average Current CTC | ₹15,69,689 |
| 🎯 Average Expected CTC | ₹18,72,545 |
| 📐 Hike Gap (Expected vs Current) | ~₹3,02,856 (+19.3%) |

---

## 🏢 Top Companies by Volume

| # | Company | Applications | Share |
|---|---------|:-----------:|:-----:|
| 1 | 🟦 Capgemini | 10 | 10% |
| 2 | 🍅 Zomato | 9 | 9% |
| 3 | 🔵 TCS | 8 | 8% |
| 4 | 🌈 Google | 8 | 8% |
| 5 | 🟩 Deloitte | 8 | 8% |
| 6 | 🔷 HCL | 7 | 7% |
| 7 | 🟣 Zoho | 6 | 6% |
| 8 | 💚 Paytm | 5 | 5% |
| 9 | 🔴 Accenture | 5 | 5% |
| 10 | 🟠 Swiggy | 5 | 5% |

---

## 👔 Applications by Role

```
SDE          ████████████████  15 (15%)
Tester       ████████████████  15 (15%)
Engineer     ███████████████   14 (14%)
Manager      ██████████████    13 (13%)
Analyst      █████████████     12 (12%)
Operations   ████████████      11 (11%)
Consultant   ████████████      11 (11%)
Developer    ██████████         9  (9%)
```

---

## 📍 Applications by Location

```
Mysore       ████████████████████  20 (20%)
Hyderabad    █████████████████     17 (17%)
Chennai      ████████████████      16 (16%)
Mumbai       ████████████████      16 (16%)
Bangalore    ███████████████       15 (15%)
Noida        ████████               8  (8%)
Pune         ████████               8  (8%)
```

---

## 🎓 Education Breakdown

| Degree | Count | Share | Bar |
|--------|:-----:|:-----:|-----|
| MBA    |  35   |  35%  | `███████████████████████████████░░░░░░░░` |
| B.Sc   |  23   |  23%  | `█████████████████████░░░░░░░░░░░░░░░░░░` |
| B.Tech |  22   |  22%  | `████████████████████░░░░░░░░░░░░░░░░░░░` |
| BBA    |  20   |  20%  | `██████████████████░░░░░░░░░░░░░░░░░░░░░` |

---

## 🔗 Application Sources

| Source | Applications | Share |
|--------|:-----------:|:-----:|
| 👥 Referral | 37 | 37% |
| 🔍 Naukri   | 35 | 35% |
| 💼 LinkedIn | 28 | 28% |

---

## ⏱️ Notice Period Distribution

| Period  | Count | Share |
|---------|:-----:|:-----:|
| 30 days |  31   |  31%  |
| 45 days |  28   |  28%  |
| 90 days |  22   |  22%  |
| 60 days |  19   |  19%  |

---

## 🛠️ Top Skills in Demand

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![AI/ML](https://img.shields.io/badge/AI%2FML-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Cloud](https://img.shields.io/badge/Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Finance](https://img.shields.io/badge/Finance-00897B?style=flat-square&logo=stripe&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-2496ED?style=flat-square&logo=docker&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)

---

## 🗂️ File Structure

| Sheet | Description |
|-------|-------------|
| 📋 **Job Data** | Raw dataset — 100 records × 16 columns |
| 📊 **Dashboard** | Visual overview and pipeline metrics |
| 👩‍💼 **Recruitment** | Recruiter-level and sourcing analysis |
| 📐 **Experience** | Analytics segmented by years of experience |
| 💰 **Salary** | Salary range and CTC comparison views |
| 🔢 **Pivot Tables** | Pre-built summaries by company, skills, experience |

---

## 🧾 Dataset Columns

| Column | Type | Description |
|--------|------|-------------|
| `Company` | Text | Hiring company name |
| `Role` | Text | Job role applied for |
| `Status` | Text | `Applied` · `Interview` · `Offer` · `Rejected` |
| `Date Applied` | Date | Application submission date |
| `Location` | Text | Job city |
| `Salary` | Number | Offered salary (₹) |
| `Experience` | Number | Years of experience (1–6) |
| `Education` | Text | Highest qualification |
| `Skills` | Text | Semicolon-separated skill tags e.g. `Python;SQL` |
| `Interview Score` | Number | Score out of 100 |
| `Offer Accepted` | Text | `Yes` / `No` |
| `Notice Period` | Number | Notice period in days |
| `Current CTC` | Number | Candidate's current CTC (₹) |
| `Expected CTC` | Number | Candidate's expected CTC (₹) |
| `Recruiter Name` | Text | Name of recruiter |
| `Application Source` | Text | `LinkedIn` · `Naukri` · `Referral` |

---

## 🚀 Getting Started

1. **Download** the `.xlsx` file
2. Open in **Microsoft Excel 2016+** or **Google Sheets**
3. Go to the **Dashboard** sheet for a visual summary
4. Use **slicers** to filter by company, status, location, or source
5. Add new rows to **Job Data** — all pivots and charts refresh automatically

---

## ⚙️ Requirements

- Microsoft Excel 2016+ *(recommended — required for slicers & pivot charts)*
- Google Sheets *(basic data & pivot support)*
- No macros, add-ins, or external data connections required

---

## 📝 Notes

- All salary and CTC figures are in **Indian Rupees (₹)**
- `Skills` stores multiple values as semicolon-separated strings
- `Notice Period` is measured in **days**
- `Interview Score` is on a **0–100 scale**
- Dataset covers applications from **Feb–Apr 2025**

---

## 📄 License

This project is for personal / educational use. Data is synthetic and for demonstration purposes only.

## 🚀 Getting Started

1. **Open** the `.xlsx` file in Microsoft Excel (2016 or later recommended) or Google Sheets
2. Navigate to the **Dashboard** sheet for a visual summary
3. Use the **slicers** (if enabled) to filter by company, status, location, or source
4. The **Pivot Tables** sheet contains pre-built summaries for deeper analysis
5. To add new data, append rows to the **Job Data** sheet — all pivots and charts will refresh automatically

---

## ⚙️ Requirements

- Microsoft Excel 2016+ **or** Google Sheets
- Macros / slicers require Excel (not supported in Google Sheets)
- No external data connections or add-ins required

---

## 📝 Notes

- All salary and CTC values are in **Indian Rupees (₹)**
- The `Skills` column stores multiple skills as semicolon-separated values (e.g., `Python;AI`)
- `Notice Period` is in **days**
- Interview Score is on a **0–100 scale**
