# 📊 Facebook Ads Campaign Performance Dashboard (2017)

**Project by Poornima | Task 2 – Data Science & Analytics Internship @ Future Interns**

---

## 📄 Project Overview
This project analyzes a **Facebook Ads Campaign dataset** to measure ad performance and marketing effectiveness using **Power BI**.  
The dashboard provides key insights into campaign spend, engagement, and return on investment — helping marketers optimize ad strategy based on data-driven evidence.

The dataset captures ad performance data such as impressions, clicks, conversions, spend, and demographic details (age, gender).

---

## 🎯 Objectives
- Clean and transform raw CSV ad data in Power BI.  
- Analyze key digital marketing metrics:
  - Click-Through Rate (CTR)
  - Cost per Click (CPC)
  - Total Spend & ROI (%)
  - Conversion Analysis
- Build an interactive Power BI dashboard for campaign performance tracking.
- Present insights and recommendations for ad optimization.

---

## 🧩 Dataset Description
**Dataset Name:** Facebook Ads Performance Dataset  
**Source:** [Kaggle – Facebook Ad Campaign Dataset](https://www.kaggle.com/)  
**File Format:** `.csv`

**Columns used:**

| Column Name | Description |
|--------------|-------------|
| ad_id | Unique identifier for each ad |
| campaign_id | Internal campaign reference |
| fb_campaign_id | Facebook campaign reference |
| age | Age group targeted |
| gender | Gender targeted |
| interest1, interest2, interest3 | Audience interests (numeric codes) |
| impressions | Number of ad impressions |
| clicks | Total number of clicks |
| spent | Total ad spend (₹) |
| total_conversion | Total conversions |
| approved_conversion | Approved conversions |

---

## 🧹 Step 1: Data Cleaning & Preparation (in Power BI)
- Removed null and duplicate rows.  
- Ensured correct data types (`Date`, `Number`, `Text`).  
- Created calculated measures for:
  - **CTR (%)** = `Clicks / Impressions`
  - **CPC (₹)** = `Spend / Clicks`
  - **ROI (%)** = `(Approved Conversions * 1000 - Spend) / Spend`
  - **Total Spend**, **Total Clicks**, **Approved Conversions**

---

## 📊 Step 2: Data Analysis
Analyzed:
- **Campaign-Level Performance** (Spend, ROI, CTR)
- **CTR Trend Over Time**
- **Spend Distribution Across Campaigns**
- **Clicks vs Conversions Correlation**
- **Audience Engagement by Age & Gender**

---

## 🖥️ Step 3: Dashboard Development (Power BI)
The dashboard includes the following key visuals:

| Visualization | Description |
|----------------|-------------|
| **KPI Cards** | Total Spend, Total Clicks, CTR (%), CPC (₹), ROI (%) |
| **Line Chart** | CTR (%) Trend Over Time |
| **Pie Chart** | Spend Distribution by Campaign |
| **Combo Chart** | Campaign Spend vs ROI (%) |
| **Scatter Plot** | Clicks vs Approved Conversions |
| **Clustered Bar Chart** | CTR (%) by Age & Gender |
| **Filters** | Campaign ID selection (916, 936, 1178) |

---

## 💡 Step 4: Key Insights & Recommendations

### 🔍 **Insights**
- Campaign **1178** contributes ~85% of total spend but shows declining CTR.  
- CTR (%) trend gradually decreases over time, indicating ad fatigue.  
- **Female audiences** show slightly higher CTR than males across all age groups.  
- Highest ROI observed for campaigns with moderate spend and balanced conversion rates.

### 💬 **Recommendations**
- Refresh ad creatives for high-spend campaigns to avoid audience fatigue.  
- Reallocate budget to better-performing age & gender segments.  
- Experiment with A/B testing on lower CTR campaigns.  
- Prioritize audience segments (35–49 years) showing consistent engagement.

---

## 🧠 Skills Gained
- Data Cleaning & Transformation in Power BI  
- Marketing Analytics (CTR, CPC, ROI, Conversion Rate)  
- Visual Analytics & KPI Design  
- Business Storytelling with Dashboards  
- Campaign Performance Evaluation  

---

Facebook-Ads-Performance-Dashboard/
├── README.md
├── data/
│ └── facebook_ads.csv
├── analysis/
│ └── cleaned_data.xlsx
├── reports/
│ └── Facebook_Ads_Dashboard.pbix
└── screenshots/
└── dashboard_preview.png


---

## 📸 Dashboard Preview
![Dashboard Preview](https://github.com/Poornima044/FUTURE_DS_02/blob/main/screenshots/dashboard_preview.png)

---

## 📬 Contact / Author
**Poornima**  
🌐 [LinkedIn](linkedin.com/in/contact-poornima) | 🧠 Aspiring Data Analyst | 📊 Power BI Enthusiast  
📍 *Task 2 – Data Science & Analytics Internship @ Future Interns*  




## 📂 Project Structure
