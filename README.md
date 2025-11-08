# 🚗 Road Accident Analysis Dashboard

## 🎯 Purpose of the Dashboard
This Excel dashboard is created to **analyze and visualize road accident data** across multiple factors such as **accident severity, vehicle type, road type, lighting condition, and area type (urban/rural)**.  
It helps identify patterns and supports **data-driven decision-making** for improving **road safety initiatives** and reducing accident risks.

---

## Dataset

The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Ferns and Petals](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

## 📊 Dashboard Overview

![Road Accident Dashboard](Road%20Accident%20Dashboar.png)

---

## 🔧 Primary KPIs

### 📈 Key Metrics
1. **Total Casualties:** 453,051  
2. **Fatal Casualties (Severe Deaths):** 8,277  
3. **Serious Casualties (Critical Injuries):** 66,298  
4. **Slight Casualties (Minor Injuries):** 378,476  
5. **Casualties by Cars:** 355,553  

### 🧩 Visualization Techniques
- Number cards for big bold KPIs  
- Donut charts with percentage labels  
- Visual icons representing each metric for better readability  

---

## 🚙 Secondary KPIs – Casualties by Vehicle Type

### Vehicle Groups
- Cars  
- Motorcycles  
- Buses  
- Trucks  
- Tractors  
- Others  

### Visualization
- Icons and labels for each vehicle type  
- Number cards displaying total casualties per type  
- Visual storytelling with Excel Icons and SmartArt  

---

## 📅 CY vs PY Casualties Monthly Trend
A **line chart** comparing monthly casualties between the **current year (2021)** and **previous year (2020)** to visualize accident trends throughout the year.

**Visualization Features:**
- X-axis: Month names (Jan–Dec)  
- Y-axis: Number of casualties  
- Data labels and legends for both years  

---

## 🛣️ Casualties by Road Type
This section highlights which **road types** experience the most casualties.

**Categories:**
- Single Carriageway  
- Dual Carriageway  
- Roundabout  
- One-Way Street  
- Slip Road  
- Unknown  

**Visualization:**  
Horizontal **bar chart**, sorted in descending order to identify the most accident-prone road types.

---

## 🌧️ Casualties by Road Surface Condition
Displays how road surface impacts accident severity.

**Categories:**
- Dry  
- Wet  
- Snow/Ice  

**Visualization:**  
**Tree Map** showing the proportion of casualties per surface type — majority occur on **Dry and Wet** surfaces.

---

## 🏙️ Urban vs Rural Casualties
Compares the number of casualties between **urban** and **rural** areas.

**Visualization:**
- **Donut Chart** with contrasting colors (e.g., dark vs light)  
- Urban casualties: 274.3K  
- Rural casualties: 178.7K  

---

## 🌙 Casualties by Light Condition
Analyzes how lighting affects accidents.

**Categories:**
- Daylight  
- Darkness  

**Visualization:**  
**Donut Chart** showing that most accidents occur during **daylight hours** (326.7K) compared to **darkness** (126.3K).

---

## ⚙️ Filter Panel
Interactive filters to explore accident data dynamically.

**Filter Options:**
- **Year:** 2020, 2021, 2022  
- **Area Type:** Urban / Rural  
- **Weather Conditions:** Fine, Fog, Rain, Snow, etc.  
- **Wind Conditions:** High Winds, No High Winds, Other  

**Visualization:**  
**Excel Slicers** styled with custom colors matching the dashboard theme.

---

## 🔗 Linked Image Navigation
Used **clickable icons** to navigate to different dashboard sections or datasets.

**Setup:**
1. Insert icons via *Insert → Icons* or *Pictures*  
2. Right-click → *Link → Place in This Document* → Choose sheet (e.g., Dataset)  
3. Optional hover effect using Shape Format options  

---

## 🧩 Data Setup and Modeling
- All visuals are powered by **Pivot Tables**  
- Raw data stored in a single clean sheet: `RoadAccidentData`  
- Used **Excel Tables** and **Named Ranges** for structured references  
- Added **helper columns** for Year, Month, Light Condition, Road Type Group, etc.  

---

## 🧰 Tools and Features Used

| Feature | Use Case |
|----------|-----------|
| **Pivot Tables** | Aggregating accident data |
| **Pivot Charts** | Creating dynamic visuals |
| **Donut Charts** | For percentage and category comparison |
| **Line Charts** | Time-series (monthly) trend analysis |
| **Bar Charts** | Category-wise comparisons |
| **Slicers** | Interactive filtering |
| **Shapes & Icons** | Visual storytelling and navigation |
| **Conditional Formatting** | Color indicators for better insights |

---

## 🧠 Key Insights
- **Majority of accidents** occur on **single carriageways**.  
- **Urban areas** have significantly higher casualties than rural.  
- **Daylight hours** see more accidents, possibly due to increased traffic density.  
- **Cars** contribute to the largest share of total casualties.  
- **Dry road conditions** account for the highest number of accidents.

---

## 🚀 Future Enhancements
- Integrate the dataset into **Power BI** for dynamic dashboards.  
- Add **forecasting models** for accident prediction.  
- Include **heatmaps** for geographic accident visualization.  
- Enable **automated data refresh** for real-time monitoring.  

---

## 🧠 Author - Hariom Rajgor

This project is part of my portfolio, showcasing the Advanced Excel skills essential for data analyst roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

### Stay Updated and Join the Community


Thank you for your support, and I look forward to connecting with you! 
