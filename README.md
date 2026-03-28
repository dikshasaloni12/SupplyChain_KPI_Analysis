## 🔑 Executive Summary
This project demonstrates end‑to‑end supply chain analytics, from raw data preparation in Python to KPI engineering and executive‑level visualization in Tableau. By quantifying lead times, delays, costs, defects, and supplier performance, the analysis identifies optimization opportunities such as shifting orders to reduce inspection failures and achieve cost savings. The workflow highlights both technical mastery and business impact, making it recruiter‑ready and manager‑friendly.

## 📑 Table of Contents
- [Overview](#-overview)
- [Workflow](#-workflow)
- [KPIs](#-kpis)
- [Results Timeline](#-results-timeline)
- [Dashboard](#-dashboard)
- [Insights](#-insights)
- [Files](#-files)


# SupplyChain_KPI_Analysis

## 📌 Overview
Supply chain analytics project using Python (Google Colab) for KPI calculations and Tableau Public for interactive dashboards.

## ⚙️ Workflow
1. Prepare dataset  
2. Engineer KPIs in Python  
3. Export enriched CSV  
4. Visualize in Tableau Public  

## 📊 KPIs
- Total Lead Time  
- Delay Flag  
- Cost per Unit  
- Defect Impact  
- Supplier Performance Index (SPI)
    
## 📸 Results Timeline

The following screenshots highlight the KPI outputs and final dashboard, showing the analysis pipeline without requiring code execution.

### Step 1: Total Lead Time
![Total Lead Time](images/step1_leadtime.png)  
*Captures the complete duration from production to delivery.*

### Step 2: Delay Flag
![Delay Flag](images/step2_delay.png)  
*Binary indicator of late shipments, aggregated into Delay %.*

### Step 3: Cost per Unit
![Cost per Unit](images/step3_cost.png)  
*Normalizes shipping costs against order quantities.*

### Step 4: Defect Impact
![Defect Impact](images/step4_defect.png)  
*Translates quality failures into monetary risk.*

### Step 5: Supplier Performance Index (SPI)
![SPI](images/step5_spi.png)  
*Composite KPI ranking suppliers by performance.*

### Step 6: Carrier & Route Efficiency
![Carrier & Route](images/step6_carrier_route.png)  
*Highlights carrier reliability and route risk.*

### Step 7: Exported Dataset
![Export CSV](images/step7_export.png)  
*Final enriched dataset exported as CSV.*

### Final Tableau Dashboard
![Dashboard](images/dashboard.png)  
*Interactive Tableau dashboard showcasing KPIs and insights.*

## 🎨 Dashboard
- KPI cards for quick snapshots  
- Supplier ranking tables  
- Carrier comparison charts  
- Route maps for delay hotspots  
- Trend charts for lead time & defects  

## 📈 Insights
- Supplier 3 has long lead times + defects  
- Carrier B is cost‑efficient, Carrier A more reliable  
- Route B is costly → optimization needed  

**Recommendation:** Shift 20% of orders from Supplier 3 to Supplier 2 → 12% fewer inspection failures + cost savings.

## 📂 Files

