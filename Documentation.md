# 📑 Project Documentation  
## Global Malnutrition Trends: A Power BI Analysis (1983–2019)  

---

## 1. Introduction  
Malnutrition continues to be a major global health challenge, particularly for children under five years of age.  
This project leverages **Power BI** to analyze global malnutrition trends between **1983 and 2019** using Kaggle datasets.  

The focus is on understanding different forms of malnutrition (stunting, wasting, underweight, and overweight) and examining correlations with **income levels** and **special country categories** such as:  
- Least Developed Countries (LDC)  
- Low-Income Food Deficient (LIFD)  
- Land-Locked Developing Countries (LLDC)  
- Small Island Developing States (SIDS)  

The goal is to provide **data-driven insights** to policymakers, researchers, and organizations aiming to combat malnutrition.  

---

## 2. Dataset  
The datasets used in this project were sourced from **Kaggle**:  
- `malnutrition-estimates.csv` – Historical malnutrition estimates for multiple countries.  
- `country-wise-average.csv` – Aggregated averages by country.  

These datasets include information about child malnutrition indicators over several decades, along with classification by income levels and country types.  

---

## 3. Objectives  
- Analyze child malnutrition trends globally (1983–2019).  
- Understand correlations between malnutrition and income levels.  
- Identify the most vulnerable countries and regions.  
- Provide actionable insights for health and policy interventions.  

---

## 4. Project Flow  
1. **Data Collection** – Downloaded dataset files from Kaggle.  
2. **Data Connection** – Imported `.csv` files into Power BI.  
3. **Data Preparation** – Performed cleaning, transformation, and calculated fields.  
4. **Visualization Development** – Designed charts and dashboards.  
5. **Dashboard Design** – Created an interactive, responsive Power BI dashboard.  
6. **Report Generation** – Compiled insights into documentation and video explanation.  

---

## 5. Data Preparation  
- Removed missing/irrelevant data.  
- Classified countries based on **income level** and **special categories (LDC, LIFD, LLDC, SIDS)**.  
- Created **calculated fields** for underweight, overweight, and stunting rates.  
- Applied **data filters** for interactivity.  

---

## 6. Visualizations & Scenarios  

### Scenario 1: Count of U5 Population (140)  
- Represents the number of under-five population observations in the dataset.  

### Scenario 2: Sum of Survey Sample (11M)  
- Indicates the robustness of the dataset, with over 11 million samples.  

### Scenario 3: Sum of Underweight (2.08K)  
- Highlights the total number of underweight cases among children under five.  

### Scenario 4: Average Stunting by Income Analysis  
- Visualizes the relationship between income classification and stunting rates.  
- Shows that higher-income countries experience lower stunting levels.  

### Scenario 5: Overweight by Country  
- Summarizes overweight cases in different countries.  

### Scenario 6: Overweight vs. Underweight by Income Classification  
- Ribbon chart analysis to compare underweight vs. overweight conditions by income.  

### Scenario 7: Sum of Income Classification  
- Displays distribution across income brackets.  

---

## 7. Dashboard Highlights  
- **Interactive Filters** – Users can filter by income group, country type, and malnutrition condition.  
- **Comparative Visuals** – Overweight vs. Underweight comparisons.  
- **Trend Analysis** – Multi-decade overview of child malnutrition.  
- **Responsive Design** – Optimized for clear and interactive presentation.  

---

## 8. Results & Insights  
- Malnutrition is **more prevalent in low-income countries**, especially underweight and stunting.  
- **Higher-income countries** tend to face **overweight issues** instead.  
- Regions such as **LDCs and LLDCs** show the highest rates of undernutrition.  
- The dataset demonstrates a **clear economic correlation** with child malnutrition patterns.  

---

## 9. Future Improvements  
- Incorporate **predictive modeling** using Power BI + Python/R.  
- Add **real-time data integration** for live dashboards.  
- Provide **country-specific recommendations** for interventions.  
- Expand with **regional comparison dashboards**.  

---

## 10. Project Deliverables  
The repository includes:  
- 📊 `Malnutrition Data Analysis.pbix` – Power BI dashboard file.  
- 📂 `malnutrition-estimates.csv` – Kaggle dataset file.  
- 📂 `country-wise-average.csv` – Kaggle dataset file.  
- 📝 `README.md` – Project overview and usage guide.  
- 📑 `Documentation.md` (this file) – Step-by-step documentation.  
- 🎥 `Demo Video.mp4` – Explanation video (to be uploaded).  

---
