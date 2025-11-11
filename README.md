# COVID-19 Clinical Trials Data Analysis

## 📘 Overview
This project performs an **exploratory data analysis (EDA)** of global COVID-19 clinical trials to uncover meaningful trends, patterns, and insights from public datasets.  
The analysis focuses on understanding how different types of studies were conducted worldwide — including vaccine and treatment trials — and how they evolved across study phases, regions, and intervention categories.

The goal is to provide **data-driven insights** into clinical research efforts during the COVID-19 pandemic.

---

## 🧩 Objectives
- Analyze the **geographical distribution** of COVID-19 clinical trials.
- Study the **trial phases** and **completion status**.
- Identify common **intervention types** and **study sponsors**.
- Visualize temporal trends in clinical trial registrations.
- Derive insights that reflect the global research response to COVID-19.

---

Each record generally includes:
- Trial ID / NCT Number  
- Study Title  
- Phase (I, II, III, IV)  
- Study Type (Interventional / Observational)  
- Location / Country  
- Start and Completion Dates  
- Intervention Name  
- Sponsor / Organization  
- Recruitment Status  

---

## ⚙️ Methodology
1. **Data Loading & Cleaning**
   - Handled missing values and inconsistent entries.
   - Standardized column names and formats.
   - Filtered out non-COVID-related or incomplete studies.

2. **Exploratory Data Analysis**
   - Distribution of trials by **country**, **phase**, and **status**.
   - Analysis of **study design** and **intervention types**.
   - Visualization of **temporal trends** (number of trials registered per month).
   - Comparison between **vaccine vs. non-vaccine** studies.

3. **Visualization**
   - Used `Matplotlib` and `Seaborn` for creating bar charts, histograms, and heatmaps.
   - Plotted world maps showing geographical spread (optional if geopandas/plotly used).

4. **Insights & Findings**
   - Countries with the most clinical trials.
   - Most common intervention types.
   - Trends in study phases and completion rates over time.

---

## 🧰 Tools & Technologies
- **Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly (optional)  
- **Environment:** Jupyter Notebook / Visual Studio Code  

---

## 📊 Results & Key Insights
- The majority of clinical trials were conducted in the **United States, India, and China**.  
- A significant proportion of studies were **interventional**, focusing on drug and vaccine testing.  
- **Phase II and III** trials were the most frequent, reflecting mid-stage and late-stage research focus.  
- Global collaboration increased significantly between 2020–2022, highlighting the unified scientific response to the pandemic.

---
