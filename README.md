# 📱 TikTok Virality Analytics: EDA & Interactive Dashboard

## 🎯 Project Objective
To analyze social media performance metrics to discover actionable strategies for content creators. This project identifies the optimal "Golden Hour" for posting and quantifies the exact impact of using trending audio on overall reach and engagement.

## 🛠️ Tools & Technologies
* **Python (Pandas):** Data ingestion, missing value imputation, and feature engineering (calculating custom Engagement Rates).
* **Python (Matplotlib):** Statistical data visualization and exploratory data analysis (EDA).
* **Power BI:** Data modeling, DAX measure creation, and interactive dashboard design.

## 🔍 Key Business Insights Discovered
1. **The Golden Hour:** Exploratory data analysis revealed a massive spike in average views for videos posted between **6:00 PM and 10:00 PM**.
2. **The Audio Multiplier:** Videos utilizing trending sounds generated significantly higher average views compared to original audio, making it a non-negotiable strategy for viral reach.
3. **Engagement Benchmarking:** Engineered a custom `Engagement_Rate` metric `((Likes + Comments + Shares) / Views)`, identifying top-performing outlier videos achieving an 18%+ engagement rate.

## 📊 Interactive Power BI Dashboard
*(The dashboard allows users to slice the data by video duration and dynamically cross-filter metrics based on sound usage and upload times.)*

![TikTok Analytics Dashboard](PowerBipreview.png)

## 📁 Repository Contents
* `TikTok_EDA_and_Cleaning.ipynb`: The Jupyter Notebook containing all Python data cleaning and Matplotlib visual analysis.
* `tiktok_analytics.csv`: The raw dataset used for analysis.
* `TikTok_Dashboard.pbix`: The fully interactive Power BI project file.
