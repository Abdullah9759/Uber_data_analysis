# Uber_data_analysis
# Uber Data Analysis Project

## 📌 Project Overview
This project analyzes Uber trip data to discover insights on demand patterns, peak hours, and location-based trends.  
The analysis involves **data cleaning, exploratory data analysis (EDA), and visualization** using Python.  
The goal is to help ride-hailing companies and drivers optimize operations and resource allocation.

---

## 📂 Dataset Access
The full dataset is too large to upload directly to GitHub.  
You can download it here: **[Google Drive Link](https://drive.google.com/file/d/1WLCtVtwlSJGuS1biWnw81-LB1cxX2Dbm/view?usp=drive_link)**  

For testing purposes, a **sample dataset** (`uber_sample.csv`) is included in this repository.

---

## 🛠 Tools & Libraries Used
- **Python** – Core programming language
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Jupyter Notebook** – Development environment

---

## 🔍 Steps Performed
1. **Data Collection** – Imported Uber trip dataset from CSV.
2. **Data Cleaning** – Removed duplicates, handled missing values, and converted date/time columns.
3. **Exploratory Data Analysis (EDA)** –  
   - Trip distribution by hour of day  
   - Day-wise and month-wise demand analysis  
   - Popular pickup locations  
4. **Visualization** – Created time-series plots, bar charts, and heatmaps to understand patterns.
5. **Insights & Conclusions** – Summarized operational recommendations.

---

## 📊 Key Insights
- Highest demand occurs during weekday rush hours (7–9 AM & 5–7 PM).
- Weekends show slightly lower trip volume but longer average trip distances.
- Certain pickup zones have consistently higher demand.

---

## 🚀 How to Run the Project
1. **Clone this repository**  
   ```bash
   git clone https://github.com/yourusername/uber-data-analysis.git
   cd uber-data-analysis

2.**Install dependencies**
  pip install -r requirements.txt

3.**Run Jupyter Notebook**
  jupyter notebook

4.**Open and run uber_analysis.ipynb**
