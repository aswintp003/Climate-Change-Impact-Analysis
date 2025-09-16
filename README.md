Analyzing climate and crop data using pandas, matplotlib, and seaborn to uncover seasonal patterns, temperature trends, and agricultural risks driven by climate change.
# 🌍 Climate Change Impact Analysis

This project explores the relationship between climate variables and agricultural outcomes, focusing on seasonal temperature trends, precipitation levels, and geospatial data. It uses Python for data cleaning, transformation, and visualization to uncover patterns that may influence crop success.

## 📌 Objectives

- Handle missing climate data using seasonal averages
- Convert geospatial coordinates into usable numeric formats
- Visualize seasonal temperature distributions and monthly trends
- Analyze the impact of precipitation and temperature on crop outcomes

## 🧰 Tools & Technologies

- **Python** – Core programming language  
- **Pandas, NumPy** – Data cleaning and manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Jupyter Notebook** – Exploratory analysis  
- **GitHub** – Version control and documentation

## 📊 Key Features

### ✅ Missing Data Imputation
- Filled missing values in `AvgTemp` and `AvgTempUncertainty` using **seasonal group means**
- Tracked and verified imputed rows using temporary flags

### ✅ Geospatial Conversion
- Converted latitude and longitude strings (e.g., `"23.5N"`, `"78.9W"`) into signed float values
- Handled missing and malformed entries gracefully

### ✅ Temporal Parsing
- Converted `CDate` column to datetime format
- Extracted **month** for seasonal trend analysis

### ✅ Visual Insights
- **Boxplot** of temperature distribution across seasons  
- **Boxplot** of precipitation vs crop success (`Label`)  
- **Line plot** of average temperature by month and season  
- **Boxplot** of temperature distribution by crop outcome
