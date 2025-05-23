# Task3-Dashboard-Development
COMPANY : CODTECH IT SOLUTIONS

NAME : SUHANI PANCHOLI

INTERN ID : CT04DL1068

DOMAIN : DATA ANALYTICS

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

---

# 🌍 Global Terrorism Dashboard – Power BI Project

## 📊 Project Overview

This project presents an interactive dashboard built using **Power BI Desktop** and the **Global Terrorism Database (GTD)**, a public dataset maintained by the University of Maryland’s START program and available via Kaggle. The dataset includes global terrorism incidents from 1970 to 2017, documenting thousands of attacks, their types, locations, casualties, and targets.

The main goal of this project is to extract meaningful trends from historical terrorism data and present them in a clear, visual format that supports **data storytelling** and **actionable decision-making**. Through this dashboard, users can explore how terrorism evolved over decades, which countries and regions were most affected, what attack methods were most common, and how many people were killed or wounded.

This project serves as a portfolio piece and an example of effective **data modeling**, **visualization**, and **insight generation** using Power BI.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** for data visualization and dashboard creation
- **DAX (Data Analysis Expressions)** for calculated columns and measures
- **Global Terrorism Database (CSV format)** sourced from Kaggle
- Visual features such as KPI cards, slicers, maps, and bar/donut charts
- Interactive **page navigation buttons**

---

## 📁 Dataset

- **Source**: [Global Terrorism Database – Kaggle](https://www.kaggle.com/datasets/START-UMD/gtd)
- **Time Span**: 1970–2017
- **Columns Used**:
  - `iyear` (Year)
  - `country_txt` (Country)
  - `region_txt` (Region)
  - `attacktype1_txt` (Attack Type)
  - `targtype1_txt` (Target Type)
  - `nkill`, `nwound` (Casualties)
  - Calculated column: `Total_Casualties = nkill + nwound`

---

## 📊 Dashboard Structure

### 🔹 Page 1 – Global Overview

The first page acts as the interactive entry point. It contains high-level KPIs showing:
- **Total Attacks**: 182,000+
- **Total Killed**: 412,000+
- **Total Wounded**: 524,000+

The following visualizations help analyze these numbers:
- **Line Chart**: Attacks per year (1970–2017), highlighting peaks in terrorism activity.
- **Bubble Map**: Displays global attacks by country with relative bubble size.
- **Bar Charts**: 
  - Attacks by region (Middle East & South Asia most affected).
  - Distribution of attacks by type (bombing, armed assault, assassination, etc.).
- **Donut Chart**: Most common target types — civilians, military, police, and government.

Users can slice the data by **Region**, **Country**, and **Year** using slicers.

   ![Image](https://github.com/user-attachments/assets/31b9242b-2e66-4dd6-8a27-995126f208fe)

---

### 🔹 Page 2 – Key Insights & Strategic Focus

This page summarizes findings and provides a strategic viewpoint. It includes:

#### 📌 Insights:
1. Terrorism attacks peaked in **2014**, with nearly 17,000 incidents in one year.
2. **Middle East & North Africa** and **South Asia** are the hardest-hit regions.
3. The most frequent attack methods are **bombings/explosions** and **armed assaults**.
4. **Private citizens and public property** are the primary targets.
5. **Iraq, Pakistan, and Afghanistan** recorded the highest numbers of casualties.

#### 🎯 Strategic Focus:
- Strengthen counterterrorism in high-risk regions.
- Improve security around civilian and soft targets.
- Study trends leading to attack peaks for predictive analysis.

#### 📈 Supporting Visuals:
- Bar chart showing **Top 5 countries by death toll**.
- Stacked column chart for **casualties over time** (killed vs. wounded).
- Bar chart of **total casualties by country**.

     ![Image](https://github.com/user-attachments/assets/62fce5b7-f157-4d56-9391-2d3fe7ca2a04)

---

## ✅ Features

- Responsive KPI indicators
- Dynamic charts connected to slicers
- Multi-page layout for better organization
- Navigation buttons for seamless transitions

> 📝 Note: Tooltip and drillthrough pages are not included in this version.

---

## 📦 Deliverables

- 📄 Dashboard PDF Export: [`global_terrorism_dashboard.pdf`](./global_terrorism_dashboard.pdf)
- 📽️ PowerPoint Summary: [`Global_Terrorism_Dashboard_Presentation.pptx`](./Global_Terrorism_Dashboard_Presentation.pptx)
- 🗂️ Power BI File (`.pbix`) – *Available upon request*

---

## 📌 License & Usage

This project is intended for educational and portfolio purposes only. Data is publicly available via the Global Terrorism Database on Kaggle.

---

