# predictive-voting-nodes
Predictive analysis and voter segmentation using Python and geospatial statistics. Implementation of Pearson coefficients, linear regression, and interactive visualization to optimize resource deployment in high-volatility districts.
# Electoral Data Strategy: Predictive Node Analysis 🗳️

![Strategic Heatmap](visualizations/newplot%20(1).png)
*Figure 1: Geospatial distribution of the 156 high-priority battleground counties analyzed in this project.*
## 📌 Project Overview
This repository contains a comprehensive data science workflow designed to identify and segment **156 high-priority swing counties** in the United States. By leveraging Python-based statistical analysis, this project demonstrates a shift from traditional demographic targeting (race/ethnicity) to a **professional-socioeconomic model**.

The final output is a strategic roadmap that optimizes campaign resource deployment by focusing on the real drivers of voting behavior.

## 🚀 Key Technical Features
- **Correlation Engine:** Comparative analysis of Pearson coefficients showing a high correlation for professional profiles (0.75) vs. a neutral correlation for ethnic demographics (0.05).
- **Geospatial Mapping:** Interactive choropleth heatmaps developed with Plotly to visualize electoral margins and volatility.
- **Strategic Segmentation:** Algorithmic classification of counties into **Node A (Knowledge Economy)** and **Node B (Industrial Economy)** clusters.
- **Automated Reporting:** Bilingual executive summaries generated for cross-functional stakeholders.

## 📊 Core Findings
Based on the analysis of thousands of census and electoral records:
1. **Professional Identity > Ethnic Identity:** The professional/educational background of a voter is a 15x stronger predictor of voting margin than their ethnic background in these specific swing districts.
2. **Cluster Distribution:** - **Node A (105 counties):** High-density professional areas requiring aspirational, stability-focused messaging.
   - **Node B (51 counties):** Industrial/Technical areas requiring pragmatic, job-security-focused messaging.
3. **Critical Thresholds:** Identified key states like **New York, California, and Minnesota** as having the narrowest margins (under 0.2%), making them the highest priority for immediate deployment.

## 🛠️ Tech Stack
- **Language:** Python 3.x (Google Colab Environment)
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `plotly.express`, `seaborn`, `matplotlib`
- **Statistics:** `scipy.stats` (Pearson Correlation, Linear Regression)

## 📁 Repository Structure
- `/data`: Final consolidated datasets (CSV).
- `/notebooks`: Python notebooks with the full data cleaning and analysis pipeline.
- `/reports`: Strategic summaries and executive reports in English and Spanish.
- `/visualizations`: High-resolution PNGs of heatmaps and correlation matrices.

---
**Author:** Melissa Cabo Farramola  
**Context:** Day 5 Final Delivery - Electoral Data Strategy Project
