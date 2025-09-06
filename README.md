# ⚡ SmartGrid Insights: Peak Energy Optimization in South Carolina

This project provides a **data-driven approach** to forecast residential energy consumption in **South Carolina during peak summer months**, helping energy providers manage grid demand, optimize energy allocation, and promote sustainable consumption.

---

## 📌 Project Overview

Developed as part of **IST 687 - Introduction to Data Science**, this project leverages **machine learning**, **weather data**, and **home characteristics** to identify the key drivers of energy consumption and predict heating and cooling demands for July.  

**Goals:**
- Forecast residential energy consumption accurately.
- Identify factors influencing energy use.
- Deliver actionable insights via an interactive **Shiny application**.

---

## 🗃️ Data Sources

1. **Static House Data**
   - Home attributes: square footage, bedrooms, HVAC type & efficiency, county.
   
2. **Energy Usage Data**
   - Hourly consumption of electricity, natural gas, propane, and breakdown for heating and cooling.

3. **Weather Data**
   - Hourly temperature, humidity, wind speed/direction across South Carolina counties.

---

## 🧪 Methodology

**1. Data Cleaning & Integration**
- Merged datasets by building ID and timestamp.
- Handled missing values and standardized units.

**2. Exploratory Data Analysis (EDA)**
- Trends in home size, HVAC systems, and occupancy.
- Energy consumption patterns over time.
- Temperature correlation with heating and cooling demand.

**3. Predictive Modeling**
- **Linear Regression** as baseline.
- **XGBoost** for advanced prediction.

**4. Deployment**
- Interactive **Shiny App** to visualize actual vs predicted consumption.

---

## 🧠 Key Insights

- Cooling energy use rises sharply with high temperatures, peaking in July.  
- HVAC efficiency, number of occupants, and home size are **strong predictors** of energy demand.  
- XGBoost outperforms Linear Regression:
  - Cooling R²: 0.69  
  - Heating R²: 0.66  

**Example Visualizations:**  

![Insulation EDA](Files/insulation_data_eda.png)  
*EDA reveals insulation and home characteristics affecting energy consumption*  

![Heating Energy Comparison](Files/Heating_Energy_Comparison.png)  
*Comparison of predicted vs actual heating energy across homes*  

![Cooling Energy Comparison](Files/Cooling_Energy_Comparison.png)  
*Cooling energy spikes during peak summer months and aligns with predictions*

---

## ✅ Recommendations & Business Impact

- **Promote energy-efficient technologies**: heat pumps, insulation, smart thermostats.  
- **Implement smart pricing strategies**: incentivize off-peak usage.  
- **Target high-usage households**: personalized energy conservation programs.  
- **Support utility planning**: forecast peak demand and prevent grid overload.  

This project demonstrates how **data analytics and machine learning** can support **real-world energy management**, reduce costs, and improve sustainability.

---

## 🛠️ Technologies Used

- **R:** tidyverse, ggplot2, xgboost, shiny  
- **RStudio**  
- **Git/GitHub**  
- **Data Visualization & Machine Learning**  

---

## 🚀 Interactive Visualization

Access the **Shiny App** to explore energy consumption patterns and forecast outcomes dynamically.  
*(Replace this with your deployed app link if available)*

---

🌱 **Using predictive analytics to optimize energy demand and promote sustainable living in South Carolina.**
