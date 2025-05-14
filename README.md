
# 🌍 COVID-19 Data Analysis (Our World in Data)

A step-by-step data analysis project exploring the global impact of the COVID-19 pandemic using the [Our World in Data](https://ourworldindata.org/coronavirus) dataset. This Jupyter Notebook project focuses on trends in cases, deaths, and vaccinations across selected countries using Python's data analysis and visualization tools.

---

## 🎯 Objectives

- Understand global and country-specific COVID-19 trends.
- Explore and clean real-world data using `pandas`.
- Visualize total cases, deaths, and vaccination progress.
- Practice essential data analysis workflows using Python.
- Derive meaningful insights and report findings using markdown.

---

## 🧰 Tools & Libraries Used

- **Python 3.9+**
- **Jupyter Notebook**
- **pandas** – for data manipulation and cleaning
- **matplotlib** – for plotting static charts
- **seaborn** – for advanced visualizations
- **numpy** – for handling missing or infinite values
- *(Optional)* **Plotly Express** – for interactive maps and choropleths

---

## 🚀 How to Run the Project

1. **Clone this repository** or download the notebook file:
   ```bash
   git clone https://github.com/yourusername/covid-data-analysis.git
   cd covid-data-analysis
   ```

2. **Download the Dataset:**
   - Go to [Our World in Data COVID-19 Dataset](https://ourworldindata.org/covid-cases) and download `owid-covid-data.csv`.
   - Place the CSV file in the same folder as the notebook.

3. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open `covid_analysis.ipynb`** and run the cells step by step.

---

## 📊 Key Features

- Filtering and visualizing data for countries like **Kenya**, **USA**, and **India**
- Cleaning and handling missing or infinite values
- Line plots for total cases, deaths, and vaccinations over time
- Comparative charts for new daily cases
- Optional choropleth map visualizing case density per country

---

## 📈 Sample Analyses Performed

- **Total COVID-19 Cases Over Time**
- **New Daily Cases Comparison**
- **Vaccination Progress**
- **Death Rates Across Countries**
- *(Optional)* **Choropleth map for global case density**

---

## 💡 Insights & Reflections

- Countries exhibited vastly different vaccination and case trends over time.
- Kenya experienced slower vaccine rollout compared to the US and India.
- Peaks in new daily cases often coincided with delays in vaccination uptakes.
- Data completeness and consistency varied by country, requiring careful cleaning.
- Forward-filling helped maintain continuity in time-series analysis.

---

## 📁 Folder Structure

```
covid-data-analysis/
│
├── covid_analysis.ipynb         # Main Jupyter notebook
├── owid-covid-data.csv          # COVID-19 dataset from Our World in Data
└── README.md                    # Project documentation
```

---

## 📌 License

This project is for educational purposes. Data sourced from [Our World in Data](https://ourworldindata.org/coronavirus), under a Creative Commons license.

---

## 🙋‍♀️ Contributions

Feel free to fork and improve this analysis by adding more countries, interactive visualizations, or predictions.

---
