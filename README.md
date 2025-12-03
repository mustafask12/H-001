H-001 | The Automated Insight Engine

Track: Data Engineering & Analytics
GroundTruth Mini AI Hackathon 2025

📌 Problem Statement

In the AdTech ecosystem, Account Managers generate weekly client reports by manually downloading CSVs, taking screenshots, and copying data across tools. This process is slow, error-prone, and non-scalable.

💡 Solution Overview

The Automated Insight Engine is an end-to-end AI-powered reporting pipeline that ingests raw marketing and operational data from multiple sources and automatically produces executive-ready PowerPoint reports with:

Key performance metrics (KPIs)

Cross-source insights

AI-generated natural-language summaries

Actionable business recommendations

The system eliminates manual effort and turns raw data into decision-ready insights in one step.

🏗️ Architecture
Data Sources (CSV / Structured Data)
        ↓
Data Ingestion & Transformation (Pandas)
        ↓
Analytics Engine (KPIs, trends, joins)
        ↓
LLM Insight Generator (AI narrative)
        ↓
Automated Report Builder (PPTX)
        ↓
Downloadable Executive Deck

📊 Data Sources

For demonstration, the system uses synthetic but realistic datasets that closely mimic real AdTech environments:

Ad Performance Data (CSV)

Impressions, clicks, spend, conversions, revenue

Offline Foot-Traffic Data (CSV)

Daily store visits

Both datasets are merged to bridge digital performance with physical-world signals, aligning with GroundTruth’s vision.

🤖 AI Integration

A Large Language Model (LLM) is used to:

Generate an Executive Summary

Highlight Key Risks / Issues

Recommend Next-Week Actions

The AI operates only on aggregated metrics, ensuring privacy and safe data usage.

🗂️ Output

✅ Fully formatted PowerPoint (.pptx) report

✅ No manual intervention required

✅ Suitable for direct client delivery

Example sections in the report:

Executive Insights

KPI Snapshot

Campaign Performance Breakdown

Spend & Trend Visualization

Risks and Recommendations

🛠️ Tech Stack

Language: Python

Data Processing: Pandas, NumPy

AI / LLM: OpenAI GPT-4.x (optional fallback text supported)

Reporting: python-pptx

Environment: Google Colab (portable to local execution)

▶️ How to Run (Google Colab)

Open the provided Colab notebook

Run all cells from top to bottom

The system will:

Generate datasets

Analyze performance

Create AI insights

Export a PPT report

Download the generated file from the output/ directory

🚀 Key Highlights

Multi-source data ingestion

Automated analytics & insights

AI-driven narrative generation

Fully automated report export

Zero manual reporting effort

🔮 Future Enhancements

SQL / database ingestion

PDF export support

Brand-themed slide templates

Scheduled (cron-based) report generation

Anomaly detection & alerts

✅ Hackathon Track Alignment

✔ H-001 | The Automated Insight Engine
✔ Data Engineering & Analytics
✔ Meets all required judging criteria