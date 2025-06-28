# COVID-19 Data Analysis and Visualization

This project provides a comprehensive analysis and visualization of the global impact of COVID-19 using real-world data. The goal is to extract meaningful insights through data wrangling, preprocessing, analysis, and various visualization techniques including geospatial mapping.

## 📌 Objective

To perform end-to-end exploratory data analysis (EDA) on COVID-19 datasets and visualize:
- Trends in confirmed cases, deaths, and vaccinations
- Country-wise comparisons
- Geospatial distribution of the virus using interactive maps

## 🗂️ Dataset

- Source: [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/covid-deaths)  
- Format: CSV  
- Contains: Daily case counts, deaths, tests, vaccinations, continent/country names, population, and more

## 🔧 Tools & Technologies Used

- **Python**: Core programming
- **Pandas**: Data manipulation and preprocessing
- **Matplotlib**: Basic plotting and trend analysis
- **Seaborn**: Statistical visualizations
- **Folium**: Interactive geographic maps
- **Jupyter Notebook**: Project development environment

## 📊 Features & Analysis Performed

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Date formatting
   - Filtering and grouping data for analysis

2. **Trend Analysis**
   - Daily and cumulative case trends for top countries
   - Death and recovery trends over time
   - Vaccination progress globally

3. **Comparative Visualizations**
   - Bar plots: Top 10 countries by total confirmed cases and deaths
   - Line plots: Daily trends for selected countries
   - Pie charts: Proportion of global cases/deaths

4. **Geospatial Visualization**
   - **Folium Choropleth Map**: Total cases per country
   - Color-coded world map to visually compare infection rates

## 📌 Sample Visualizations

- Line plot: Confirmed cases over time (Top 5 countries)
- Bar chart: Top 10 countries by COVID-19 deaths
- Pie chart: Distribution of cases across continents
- Folium map: Cases per country with interactive tooltips

## 📈 Key Insights

- Identification of countries with the highest and lowest case counts
- Trends in how the virus spread geographically over time
- Comparison between continents and vaccination progress

## 📁 Project Structure

covid19-analysis/
│
├── covid_analysis.ipynb # Main Jupyter Notebook
├── covid_data.csv # Raw dataset
├── README.md # Project documentation
└── outputs/ # Plots and visualizations

## 🚀 How to Run

1. Clone the repository
2. Install required libraries (Pandas, Matplotlib, Seaborn, Folium)
3. Open `covid_analysis.ipynb` in Jupyter Notebook or VS Code
4. Run cells sequentially to see preprocessing, analysis, and visualizations

## ✅ Prerequisites

```bash
pip install pandas matplotlib seaborn folium
