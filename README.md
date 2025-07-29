# 🕵‍♂ Dark Web Threat Intelligence Dashboard – Power BI Project

A cybersecurity-focused dashboard built in Power BI to simulate real-time monitoring of Dark Web activities, keyword alerts, and risk patterns across industries and regions.

## 📊 Features

- Alert Frequency & Trends (by region, keyword, industry)
- AI-based clustering of risk vs frequency (scatter chart)
- Most Triggered Keywords and Categories
- Source platform analysis (Telegram, Onion forums, etc.)

## 📁 Dataset

A synthetic dataset simulating dark web alerts, generated using Python and Faker:
- Fields: incident_id, region, industry, keyword_detected, risk_score, date, category, mentions_count, etc.

## 🧠 Smart Analytics

- RFM-style segmentation (Recency/Frequency/Risk)
- Risk Score KPI Cards
- Time Series with Moving Average

## 🛠 Tools Used

- Power BI Desktop
- Python (for data generation)
- DAX Measures
- GitHub (for version control)

## 🧩 Sample Insights

- Ransomware & Credential Dump are top threats in Banking
- High-risk alerts peak from Telegram sources in North America
- Asia shows rising frequency with low risk (volume-driven noise)
