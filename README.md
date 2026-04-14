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
