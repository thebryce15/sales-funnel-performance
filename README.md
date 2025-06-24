# Sales Funnel Leak-Point & Efficiency Analysis  
*Excel-cleaned, Power BI-visualized deep-dive into where deals stall and which channels win* :contentReference[oaicite:0]{index=0}  

## 1. Why This Project Matters  
Leadership asked for a rapid, numbers-first diagnosis of funnel attrition, channel effectiveness, and sales-cycle efficiency to guide coaching, budget shifts, and process fixes. :contentReference[oaicite:1]{index=1}  

> **Bottom-line:** 63 % of proposals never close—raising the close-rate just 10 points adds ~60 wins per quarter. :contentReference[oaicite:2]{index=2}  

## 2. Key Highlights  
| Insight | What We Found | So What? |
|---------|---------------|----------|
| **Biggest leak** | Proposal → Won drops -63 % (92 lost deals) :contentReference[oaicite:3]{index=3} | Late-stage enablement is the #1 revenue lever |
| **Top channel** | Website traffic converts ≈10 %—2× Partners & 3× Telesales :contentReference[oaicite:4]{index=4} | Shift budget toward Website & partner programs |
| **Deal ageing** | Deals > 60 days almost never win :contentReference[oaicite:5]{index=5} | Add ageing alerts & 60-day “kill” rule |

## 3. Data Snapshot  
* **Source:** CRM export `Leads_Deals_2025Q2.csv` (internal)  
* **Window:** Q2 2024 – Q1 2025  
* **Size:** 980 deals × 24 columns (one row = one deal) :contentReference[oaicite:6]{index=6}  

## 4. Methodology  
1. **ETL:** Power Query cleans & pivots stage history.  
2. **Model:** DAX measures compute stage drop-offs, win-rate, cycle days.  
3. **Viz:** Interactive Power BI dashboard (bar, column, scatter) with slicers.  
4. **Validation:** KPIs cross-checked against CRM reports, peer-reviewed. :contentReference[oaicite:7]{index=7}  

## 5. Recommendations (Roadmap Excerpts)  
1. **Late-Stage Enablement** – proposal QA checklist, pricing guard-rails, exec-sponsor outreach (July 2025).  
2. **Channel Re-allocation** – +30 % Website spend, nurture Partners, pause low-ROI Telesales (Aug 2025).  
3. **Ageing Alerts** – Power BI flags deals inactive > 60 days (Sept 2025). :contentReference[oaicite:8]{index=8}  

## 6. How to Explore  
| Artifact | Location |
|----------|----------|
| Slide deck (PDF) | `docs/SALES_Funnel_Performance_Review.pdf` |
| Cleaned Excel workbook | `data/clean/Deals_2024-2025.xlsx` |
| Power BI report (`.pbix`) | `dashboard/sales-funnel.pbix` |

![Funnel_Dashboard](https://github.com/user-attachments/assets/c02a3dc6-24a9-45aa-a276-338b5fb70c20)

---

### Contact  
Bryce Smith · brycesmithx@gmail.com · [GitHub @thebryce15](https://github.com/thebryce15)

