# 🌍 Energy Consumption Data Visualization Tutorial

This project explores global energy consumption patterns using a comprehensive dataset from **Our World in Data**. It focuses on selected energy-related metrics across different countries and years, visualized with Python data tools.

---

## 📊 Dataset Overview

- **Source:** Our World in Data ([link to dataset](https://ourworldindata.org/energy))
- **Description:** The dataset includes metrics on:
  - Primary energy use
  - Electricity generation and mix (coal, gas, nuclear, solar, etc.)
  - CO₂ intensity of electricity
  - Energy per capita & per GDP
  - Production data (coal, gas, oil)
- **Filtered Columns Used (25):**
  - `country`, `year`, `carbonintensityelec`, `coal_production`, `electricity_generation`, `biofuel_electricity`, `coal_electricity`, `fossil_electricity`, `gas_electricity`, `hydro_electricity`, `nuclear_electricity`, `oil_electricity`, `renewables_electricity`, `solar_electricity`, `wind_electricity`, `energypergdp`, `energypercapita`, `fossilshareelec`, `gasshareelec`, `gas_production`, `lowcarbonshare_elec`, `oil_production`, `population`, `gdp`

---

## 🛠️ Tools & Libraries

- `pandas` for data wrangling
- `matplotlib` and `seaborn` for visualizations
- `warnings` module to suppress irrelevant output

---

## 📈 Project Workflow

1. **Import Libraries**
2. **Load and Filter Dataset**
3. **Preprocess & Handle Missing Data**
4. **Exploratory Data Analysis**
   - Country-wise energy consumption trends
   - Comparison of electricity sources (renewables vs fossil)
   - Visualization of CO₂ intensity vs energy efficiency
5. **Visualization Techniques**
   - Line plots, bar charts, heatmaps
   - Multi-variable comparison
6. **Key Insights**
   - Share of renewables across regions
   - Fossil fuel dependency trends

---

## 📌 How to Run

1. Clone the repository or download the notebook.
2. Install required libraries using:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the `.ipynb` notebook in Jupyter or VS Code and run all cells.

---

## 📄 License

This project is for educational and non-commercial use. Dataset © Our World in Data.
