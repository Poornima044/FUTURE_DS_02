# 📈 Social Media Campaign Performance Tracker – Power BI Project
**Task 02 – Data Science & Analytics Internship by Future Interns**

---

## 📄 Project Overview
This project focuses on analyzing **Facebook Ads campaign performance** to measure marketing effectiveness and identify opportunities for improvement.  

The goal is to help marketing teams and decision-makers understand:
- Which campaigns are driving the highest engagement 📊  
- How ad spend translates into performance metrics 💰  
- Which demographics or ad types deliver the best ROI 🚀  

The final output is an **interactive Power BI dashboard** that visualizes key KPIs such as CTR, CPC, and ROI.

---

## 🎯 Objectives
- Analyze Facebook ad campaign data to evaluate performance  
- Track metrics like Impressions, Clicks, CTR, CPC, and ROI  
- Identify high-performing campaigns, audiences, and ad creatives  
- Present actionable insights and recommendations through Power BI  

---

## 🧩 Dataset Description
**Dataset Name:** Facebook Ads Performance Dataset  
**Source:** Kaggle  
**File Format:** `.csv`  

**About the Data:**  
The dataset contains detailed information on ad performance metrics such as impressions, reach, clicks, conversions, and ad spend across multiple campaigns.

| Column Name | Description |
|-------------:|-------------|
| Campaign_Name | Name of the ad campaign |
| Ad_ID | Unique identifier for each ad |
| Ad_Set | Ad grouping or targeting strategy |
| Impressions | Number of times an ad was displayed |
| Reach | Number of unique users reached |
| Clicks | Total number of clicks received |
| Spend | Total ad spend (in INR ₹) |
| Conversions | Number of actions taken after clicking the ad |
| CTR (%) | Click-Through Rate |
| CPC (₹) | Cost Per Click |
| ROI (%) | Return on Investment |

---

## 🧹 Step 1: Data Cleaning (Excel / Power BI)
- Removed duplicate and blank records  
- Checked for missing values in key metrics (`Clicks`, `Spend`, `Impressions`)  
- Ensured date fields are formatted correctly  
- Created calculated columns:
  - `CTR = (Clicks / Impressions) * 100`
  - `CPC = Spend / Clicks`
  - `ROI = (Revenue - Spend) / Spend * 100`
- Filtered out zero or invalid spend entries  

---

## 📊 Step 2: Data Analysis
Analyzed:
- **Top Campaigns by ROI and Engagement**  
- **CTR Trends across Campaigns and Time Periods**  
- **Spend vs Conversions Correlation**  
- **Performance by Audience Segment or Ad Set**  
- **Click Distribution by Device or Region (if available)**  

---

## 🖥️ Step 3: Dashboard Development (Power BI)
Included:
- **KPI Cards:** Total Spend, Total Clicks, CTR (%), CPC, ROI (%)  
- **Bar Chart:** Campaigns by Spend and ROI  
- **Line Chart:** CTR Trend Over Time  
- **Pie Chart:** Spend Distribution by Campaign  
- **Scatter Plot:** Clicks vs Conversions  
- **Filters/Slicers:** Campaign Name, Date, Device, or Ad Set  

---

## 💡 Step 4: Insights & Recommendations
**Insights:**
- Campaigns with moderate spend and creative visuals achieved higher CTRs.  
- ROI was strongest in campaigns targeting younger demographics (18–25).  
- Some ads with high impressions had low CTR, indicating creative fatigue.  

**Recommendations:**
- Increase budget for campaigns with high ROI.  
- Test new creatives for ads with low CTR.  
- Reallocate spend toward high-engagement age groups and regions.  
- Optimize posting times based on engagement trends.  

---

## 🧰 Tools Used
- **Microsoft Power BI** – Dashboard creation & visualization  
- **Excel** – Data cleaning & calculations  
- **Power Query** – Data transformation  
- **Canva (Optional)** – For ad creative mockups  

---

## 🧠 Skills Gained
- Marketing Data Analysis  
- Campaign Performance Tracking  
- DAX Calculations for Marketing KPIs  
- Data Visualization & Storytelling  
- Power BI Dashboard Development  

---

## 🗂️ Project Structure
```text
SocialMediaCampaignPerformance/
├── README.md
├── data/
│   └── facebook_ads_performance.csv
├── analysis/
│   └── cleaned_data.xlsx
├── reports/
│   └── PowerBI_Dashboard.pbix
└── screenshots/
    └── dashboard_preview.png
