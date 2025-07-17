# 🚦 US Accidents Data Analysis — Task 4

This project is part of the **SkillCraft Data Science & Visualization Track – Task 4**, focused on analyzing a large-scale dataset of US traffic accidents to uncover key patterns and visualize trends across time, geography, and conditions.

---

## 📁 Dataset

- **Source**: [Kaggle - US Accidents (March 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **File**: `US_Accidents_March23.csv`
- **Size**: ~900 MB+
- **Fields**:
  - `Start_Time`, `End_Time`
  - `Start_Lat`, `Start_Lng`
  - `Severity`, `Weather_Condition`
  - `State`, `City`, `Street`
  - `Temperature`, `Humidity`, `Visibility`, etc.

---

## 🎯 Objectives

- Identify **patterns** in accidents based on:
  - 🕒 **Time** of day/week/month
  - 🌦️ **Weather conditions**
  - 🌍 **Geographical locations**
- Determine accident **severity trends**
- Visualize **accident hotspots** using interactive maps

---

## 🔧 Tools & Libraries

- Python 3.x
- `pandas`, `numpy` – Data handling
- `matplotlib`, `seaborn` – Plotting and visualization
- `folium` – Geographic heatmaps
- `jupyter notebook`

---

## 📊 Key Features & Insights

- Cleaned over 3 million records for valid geo-time-weather data
- Extracted time-based features (`Hour`, `DayOfWeek`, `Month`)
- Visualized:
  - 📈 Severity vs. Weather
  - ⏰ Hourly accident density
  - 📆 Weekday and monthly trends
  - 🗺️ Location heatmaps via Folium
- Filtered and mapped hotspots using Start_Lat and Start_Lng

---

## 🖼️ Sample Visualizations

![Accidents by Hour of Day graph](/Accidents_by_Hour_of_Day.png)
![Top 10 Weather Conditions graph](/Top_10_Weather_Conditions.png)

- 📍 Accident Hotspot Map  
- 🕒 Accidents by Hour  
- 📅 Accidents by Day and Month  
- 🌧️ Accidents by Weather Conditions  
- 📊 Severity Distribution

---

## ▶️ How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/raga-bot/SCT_DS_4.git
   cd SCT_DS_4
2. Install required libraries:
3. ```bash
   pip install pandas numpy matplotlib seaborn folium
4. Place the CSV file US_Accidents_March23.csv in the project root folder.
5. Open the Jupyter Notebook:
     - jupyter notebook US_Accidents_Task4_Analysis.ipynb


✅ Deliverables

 - Cleaned and preprocessed dataset
 - Exploratory Data Analysis
 - Visual dashboards (static + interactive)
 - GitHub-ready documentation

👤 Author

RagaVarshini B S
Data Science & Visualization Track – Task 4
