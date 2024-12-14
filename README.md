
# Climate Impact and Correlation Analyzer

## Overview
The global climate crisis—marked by rising temperatures, melting ice caps, and increasing natural disasters—has disrupted ecosystems, agriculture, and human health. Understanding the interconnectedness of these factors is critical for evidence-based decision-making and effective climate strategies.

This project introduces **Climate Impact and Correlation Analyzer**, an interactive data visualization platform that combines global datasets on surface temperature, carbon emissions, sea levels, and natural disasters. The platform provides advanced visual tools to analyze and uncover correlations, enabling researchers, policymakers, and stakeholders to make data-driven decisions.

---

## Data Summary
The platform integrates the following datasets:

1. **Global Surface Temperature**: Monthly averages from the 18th century to present.
2. **Carbon Emissions**: Country-level emissions data spanning the 20th century.
3. **Sea Level Rise**: Historical mean sea level records from the 19th century onward.
4. **Natural Disasters**: Compilation of events like floods, droughts, and extreme weather.

All datasets were preprocessed to ensure consistency, including:
- Cleaning and standardizing units.
- Aligning data to a "Country-Year" format.
- Handling missing values through interpolation.

Sources:
- [Global Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- [Carbon Emissions Data](https://www.kaggle.com/datasets/ankanhore545/carbon-dioxide-emissions-of-the-world)
- [Sea Level Rise Data](https://www.kaggle.com/datasets/jarredpriester/global-sea-level-rise)
- [Natural Disaster Data](https://ourworldindata.org/natural-disasters)

---

## Research Challenges
1. **Data Quality**: Handling missing or incomplete data introduced interpolation uncertainty.
2. **Data Volume**: Large datasets required computationally efficient preprocessing.
3. **Visualization Complexity**: Designing intuitive, multi-dimensional visualizations for non-linear relationships was challenging.

---

## Running the Code
### Prerequisites
- **Python** (version >= 3.8)
- Libraries: `Pandas`, `NumPy`, `Plotly`, `Chart.js`, `Flask`

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/CERZ3X/CS524.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the interface:
   ```bash
   python Climate_Analyzer.py
   ```
4. Open `http://localhost:5000` in your browser to interact with the platform.

---

## Results
### Key Insights
1. **Correlation Between Carbon Emissions and Temperature**:
   - A strong positive correlation, especially post-20th century.
2. **Rising Sea Levels**:
   - Accelerated in recent decades due to ice melt and thermal expansion.
3. **Natural Disaster Trends**:
   - Frequency and intensity of disasters correlate with temperature anomalies.
4. **Regional Disparities**:
   - Certain regions exhibit disproportionately high emissions and temperature anomalies.

### Example Visualizations
- **Heatmaps**: Show regional temperature variations.
- **3D Globe**: Interactive temperature anomaly visualization.
- **Stacked Bar Charts**: Natural disaster frequencies over time.
- **Correlation Heatmaps**: Explore relationships between temperature anomalies, emissions, and disasters.

---

## Future Work
- **Data Integration**: Include socioeconomic indicators like GDP and population density.
- **Predictive Models**: Leverage machine learning for forecasting climate trends.

---

## References
1. IPCC AR6 Synthesis Report: Climate Change 2023.
2. Liu, C., et al. "Interactive Climate Data Analysis Dashboard," IEEE Transactions, 2019.
3. Smith, P., et al. "Linking Emissions and Sea-Level Rise," Climate Journal, 2021.
4. NASA GISS, "Surface Temperature Analysis," 2024.
5. Kaggle Datasets, 2024.

---

## Authors
Abhiram Vasudeva ,
Sanjay Kalaivanan ,
Purvi Vadher.
