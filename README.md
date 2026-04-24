# 🚦 Traffic Accident Data Analysis & Visualization

## 📌 Project Overview

This project analyzes and visualizes traffic accident data to uncover patterns related to:

* Weather conditions 🌦️
* Time of day ⏰
* Accident severity 🚑
* Geographic hotspots 📍

Due to the large size of the original dataset, a **sample dataset** is used for efficient analysis and GitHub compatibility.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Analyze accident trends based on time and weather
* Visualize severity distribution
* Identify accident-prone locations using heatmaps

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib
* Seaborn
* Folium (for maps)

---

## 📂 Dataset

* Original dataset: `US_Accidents_March2023.csv` (very large)
* Sample dataset used: `US_Accidents_sample.csv` (5000 rows)

### Key Features:

* `Start_Time` → timestamp of accident
* `Start_Lat`, `Start_Lng` → location coordinates
* `Weather_Condition` → weather during accident
* `Severity` → accident severity level

---

## ⚙️ Data Preprocessing

* Converted `Start_Time` to datetime format
* Extracted **hour of accident**
* Removed rows with missing latitude/longitude
* Created a smaller sample dataset for performance

---

## 📊 Exploratory Data Analysis

### 🌦️ Accidents by Weather

* Top 10 weather conditions contributing to accidents

### ⏰ Accidents by Time of Day

* Histogram showing accident frequency across 24 hours

### 🚑 Accidents by Severity

* Count plot of severity levels

### 📍 Accident Hotspots

* Interactive heatmap using Folium
* Saved as:

  ```
  accident_hotspots.html
  ```

### 🔥 Weather vs Severity

* Heatmap showing relationship between weather and severity

---

## 📈 Output

The project generates:

* Bar charts and histograms
* Heatmaps (Seaborn)
* Interactive map (Folium)

---

## 🚀 How to Run

### 1. Clone the repository

```bash id="0qx7ak"
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash id="kpj8q3"
pip install pandas matplotlib seaborn folium
```

### 3. Run the script

```bash id="0mfk0y"
python your_script_name.py
```

---

## ⚠️ Notes

* Full dataset is very large, so only a sample is used
* Heatmap uses limited points (5000) for performance
* Ensure CSV file is in the correct directory

---

## 💡 Future Improvements

* Use full dataset with optimized processing
* Add real-time accident analysis
* Build interactive dashboards (Streamlit / Power BI)
* Apply machine learning for accident prediction

---

## 📬 Contact

Feel free to reach out for collaboration or suggestions!

---

⭐ If you found this project useful, consider giving it a star!
