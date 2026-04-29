# 🚦 Road Accident Data Analysis — UK 2021 & 2022
### End-to-End Analytics Project | Microsoft Excel

> *"2,855 deaths in a single year. Every single one was preventable.  
> Data won't fix roads on its own — but it tells us exactly where to start."*

---

## 📌 Project Overview

This is a **full end-to-end data analysis project** built entirely in **Microsoft Excel**, analyzing **307,975 road accident records** from the United Kingdom covering the years **2021 and 2022**.

The goal was not just to build a dashboard — but to go through the complete data analysis lifecycle:
data cleaning → exploration → pivot analysis → insight generation → recommendations → interactive dashboard.

---

## ⚠️ The Problem

UK roads recorded **417,883 casualties** over just two years.

| Severity | Count | % of Total |
|---|---|---|
| ☠️ Fatal | 7,135 | 1.7% |
| 🔴 Serious | 59,312 | 14.2% |
| 🟡 Slight | 351,436 | 84.1% |
| **Total** | **417,883** | **100%** |

**Cars** were involved in **79.8%** of all casualties — making them the dominant vehicle type by a wide margin.

The numbers alone are alarming. But the real work was understanding what's **behind** them.

---

## 📁 Dataset

| Property | Detail |
|---|---|
| Source | UK Road Accident Data |
| File Format | `.xlsx` |
| Number of Records | 307,975 rows |
| Number of Fields | 21 columns |
| Time Period | 2021 – 2022 |
| Geography | England & Wales |

---

## 🔄 Project Workflow

```
Raw Data (.xlsx)
      ↓
Data Cleaning & Preparation
      ↓
Exploratory Data Analysis
      ↓
Pivot Table Analysis (6 Dimensions)
      ↓
Insight Generation & Recommendations
      ↓
Interactive Dashboard (9 Dynamic Views)
      ↓
Structured Report
```

---

## 🔍 The Analysis — 6 Dimensions

Each dimension was analyzed with a structured approach:  
**Question → Finding → Insight → Recommendation**

---

### 1️⃣ Casualty Severity & Vehicle Type

**Finding:**
- Fatal casualties represent only 1.7% of total — but that's **7,135 lives lost**
- Cars account for **79.8%** of all casualties
- Vans/Trucks: 33,472 | Buses: 12,798 | Bicycles: 33,672

**Insight:**  
The casualty profile is dominated by slight injuries and car involvement.  
But the fatal rate, though small in percentage, translates to thousands of lives lost every year.

**Recommendations:**
- Launch targeted car-driver awareness and enforcement campaigns
- Invest in advanced emergency response to convert potentially fatal accidents into serious/slight outcomes
- Track the fatal-to-serious casualty ratio as a key annual KPI

---

### 2️⃣ Road Type Analysis

| Road Type | Casualties |
|---|---|
| Single Carriageway | 309,700 (74%) |
| Dual Carriageway | 67,400 |
| Roundabout | 26,800 |
| One Way Street | 7,400 |
| Slip Road | 4,700 |

**Finding:**  
Single Carriageway roads account for **74% of ALL casualties** — consistently, across every year and every location filter.

**Insight:**  
This is not a coincidence. It's a **structural problem hiding in plain sight.**  
One road type. Nearly three-quarters of all harm.

**Recommendations:**
- Conduct a national audit of Single Carriageway roads with highest casualty concentration
- Advocate for infrastructure upgrades: barriers, lighting, speed cameras
- Prioritize dual carriageway expansion in high-traffic corridors

---

### 3️⃣ Road Surface Analysis

| Surface Condition | Casualties |
|---|---|
| 🌞 Dry | 279,445 (66.8%) |
| 🌧️ Wet | 135,261 (32.3%) |
| ❄️ Ice/Snow | ~3,177 (0.9%) |

**Finding:**  
The **majority of casualties happen on DRY surfaces** — not in rain, not in ice.

**Insight:**  
Clear conditions create overconfidence → higher speed → less focus.  
The risk is **behavioral — not environmental.**

**Recommendations:**
- Run speed enforcement year-round, not just in winter
- Public messaging: *"Clear roads don't mean safe roads"*
- Focus behavioral safety campaigns on normal, familiar driving conditions

---

### 4️⃣ Urban vs Rural Risk Profiles

| Metric | Rural | Urban |
|---|---|---|
| Total Casualties | 162,019 (38%) | 255,864 (62%) |
| Fatal Rate | **3.0%** | **0.9%** |
| Fatal Casualties | 4,816 | 2,319 |
| Serious Rate | 17.8% | 11.9% |
| Top Road Type | Single Carriageway | Single Carriageway |

**Finding:**  
Rural areas account for 38% of casualties — but their **fatal rate is 3× higher** than urban areas.  
Fewer cars. But when accidents happen there, they are far more likely to kill.

**Insight:**  
Rural roads are **under-resourced relative to their actual risk level.**  
The problem is infrastructure and emergency response distance — not accident frequency.

**Year-by-Year Rural:**
| Year | Total | Fatal | Fatal Rate |
|---|---|---|---|
| 2021 | 87,533 | 2,767 | 3.2% |
| 2022 | 74,486 | 2,049 | 2.8% |

**Year-by-Year Urban:**
| Year | Total | Fatal | Fatal Rate |
|---|---|---|---|
| 2021 | 134,613 | 1,513 | 1.1% |
| 2022 | 121,251 | 806 | 0.7% |

**Recommendations:**
- Invest in rural road infrastructure proportional to **actual risk** — not traffic volume
- Improve rural emergency response time and coverage
- Install better lighting and signage on rural Single Carriageway roads

---

### 5️⃣ Day vs Night Analysis

| Condition | Casualties |
|---|---|
| ☀️ Daylight | 305,000 (73%) |
| 🌙 Darkness | 112,900 (27%) |

**Finding:**  
**73% of all casualties occur in daylight.**

**Insight:**  
The danger isn't darkness — it's overconfidence in familiar, "safe" conditions.

**Recommendations:**
- Do not over-allocate resources to nighttime safety at the expense of daytime behavioral interventions
- Analyze severity-per-incident for day vs night separately
- Improve street lighting in high-darkness-casualty zones

---

### 6️⃣ Year-over-Year Trend (2021 vs 2022)

| Metric | 2021 | 2022 | Change |
|---|---|---|---|
| Total Casualties | 222,146 | 195,737 | ↓ 11.9% |
| Fatal | 4,280 | 2,855 | ↓ **33.3%** |
| Serious | 32,267 | 27,045 | ↓ 16.2% |
| Slight | 185,599 | 165,837 | ↓ 10.6% |

**Finding:**  
Every severity category improved from 2021 to 2022.  
The monthly trend confirmed this improvement is **sustained across all 12 months** — not driven by a single outlier.

**Insight:**  
Something worked. The next step is understanding exactly what — and scaling it.

**Recommendations:**
- Document and institutionalize what drove the 2022 improvements
- Use 2021–2022 as training data to build predictive models for 2023 risk hotspots
- Publish monthly performance dashboards for stakeholder accountability

---

## 📊 Interactive Dashboard

The dashboard was built entirely in Excel with **2 interactive slicers** producing **9 dynamic views.**

### 📸 Dashboard Preview

![Road Accident Dashboard](<img width="1280" height="610" alt="photo_2026-04-28_17-36-05" src="https://github.com/user-attachments/assets/2ecb6ace-3e16-4cab-82ce-b5597cafb6d9" />
)

### 🎛️ Filters
| Filter | Options |
|---|---|
| Accident Year | All Periods / 2021 / 2022 |
| Area Type | All / Rural / Urban |

> The 2 slicers combined produce **9 dynamic views** — covering every year and location combination.

### 📐 Dashboard Components
- **KPI Cards** — Total, Fatal, Serious, Slight Casualties + Casualties by Cars
- **Monthly Trend Line** — 2021 vs 2022 side by side
- **Casualties by Vehicle Type** — breakdown with icons
- **Casualties by Road Type** — horizontal bar chart
- **Casualties by Road Surface** — stacked bar chart
- **Casualties by Area/Location** — donut chart (Urban vs Rural)
- **Casualties by Day/Night** — donut chart

---

## 📂 Project Files

| File | Description |
|---|---|
| 📊 [Road_Accident_Data.xlsx]([data/Road_Accident_Data.xlsx](https://docs.google.com/spreadsheets/d/1R_uaoZL18nRbqC_MULVne90h3SdRbAyn/edit?usp=sharing&ouid=100705334051082984991&rtpof=true&sd=true)) | Raw dataset — 307,975 records, 21 fields |
| 📄 [Road_Accident_Analysis_Report.pdf](https://github.com/Tawfiq-Ayman/Road-Accident-Analysis-UK-Excel/blob/main/Road%20Accident%20Dashboard%20%E2%80%94%20Data%20Analysis%20Report.pdf) | Full structured analysis report |
| 📋 [REQUIREMENT_Road_Accident.pdf]([requirements/REQUIREMENT_Road_Accident.pdf](https://github.com/Tawfiq-Ayman/Road-Accident-Analysis-UK-Excel/blob/main/REQUIREMENT%20Road%20Accident%20.pdf)) | Original project requirements document |
| 🖼️ [dashboard_overview.png]([screenshots/dashboard_overview.png](https://github.com/Tawfiq-Ayman/Road-Accident-Analysis-UK-Excel/blob/main/photo_2026-04-28_17-36-05.jpg)) | Dashboard preview image |

---

## 🛠️ Tools & Skills Used

| Tool | Usage |
|---|---|
| **Microsoft Excel** | 100% of the project |
| Pivot Tables | Data aggregation & multi-dimension analysis |
| Pivot Charts | All visual components |
| Slicers | Interactive filtering |
| Conditional Formatting | KPI card design & visual emphasis |
| Dashboard Design | Layout, color scheme, typography |

> ⚡ No Python. No Power BI. No Tableau. Pure Excel.

---

## 👥 Stakeholders

This analysis is relevant to:

`Ministry of Transport` · `Road Transport Department` · `Police Force` · `Emergency Services` · `Road Safety Corps` · `Transport Operators` · `Traffic Management Agencies` · `Public` · `Media`

---

## 💡 Key Takeaway

Real data analysis isn't reporting what happened.  
It's understanding **why** — dimension by dimension —  
and turning each finding into an **actionable recommendation.**

> Not: *"Accidents happen more in rural areas."*  
> But: *"Rural fatality rates are 3× higher because of infrastructure gaps  
> and emergency response distance — not accident frequency."*

That's the difference between **describing data** and **actually analyzing it.**

---

## 📽️ Demo

> 🎬 *[Add your LinkedIn/YouTube video link here]*

---

## 📬 Contact

**[Your Name]**  
📧 [Your Email]  
🔗 [Your LinkedIn Profile]

---

*Built with Microsoft Excel | Data Analysis Portfolio Project*
