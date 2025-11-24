# 📡 Data Science Interview Exam: Bluetooth Scan Data Analysis

## 📖 Project Overview
This project demonstrates the analysis of a **synthetic Bluetooth scan dataset** collected over three weeks. The dataset simulates how multiple sensors detect Bluetooth communications between nearby devices (e.g., smartphones, earbuds) as people move through space.  

The goal is to extract insights about **movement patterns, peak activity times, spatial distribution**, and to explore predictive modeling for identifying when a person might enter a **“dark space”** (areas without sensor coverage).

---

## 📂 Dataset Description
Two CSV files are provided:

- **`sensor_map.csv`**  
  - Contains the coordinates `(x, y)` of each sensor.  
  - Defines the spatial layout of the sensor network.

- **`trajectories.csv`**  
  - Logs Bluetooth detections with:  
    - `timestamp`  
    - `person_id` (anonymized)  
    - `sensor_id`  
    - `signal_strength`  

---

## 🎯 Objectives
- **Data Preprocessing**: Clean and structure raw sensor logs.  
- **Exploratory Analysis**:  
  - Identify peak detection times.  
  - Visualize movement trajectories.  
  - Map sensor coverage and blind spots.  
- **Spatial Analysis**: Study distribution of detections across sensors.  
- **Predictive Modeling**: Explore ML techniques to predict entry into dark spaces.  
- **Visualization**: Present findings with clear tables, charts, and spatial plots.  

---

## 🛠️ Tools & Techniques
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- **Jupyter Notebook** for interactive analysis and visualization  
- **Data Science Methods**:  
  - Time-series analysis  
  - Spatial mapping  
  - Signal strength analysis  
  - Predictive modeling (classification/regression)  

---

## 📊 Expected Output
The final deliverable is a **Jupyter Notebook** containing:  
- Cleaned datasets  
- Exploratory tables and figures  
- Sensor coverage maps  
- Predictive modeling experiments  
- Key insights and conclusions  

---


