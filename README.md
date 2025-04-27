# UNICEF Indicator 2 Data Visualization Project

## Project Overview
This project visualizes global data related to **violent discipline among children aged 1–14 years**, based on UNICEF Indicator 2. The purpose of the project is to raise public awareness and provide insights into the severity and distribution of child violence across different countries.

Visualizations include:
- A **World Map** showing the global distribution.
- A **Bar Chart** highlighting the top 15 countries with the highest violent discipline rates.
- A **Scatterplot with Regression Line** to explore country variations.
- A **Density Plot** to show distribution trends.

All visualizations are created using **Python** libraries: `pandas`, `geopandas`, and `plotnine`, and rendered using **Google Colab** and **Quarto**.

## Files Used

| File Name                         | Description                                       |
|:----------------------------------|:--------------------------------------------------|
| `unicef_indicator_2 (1).csv`       | Cleaned UNICEF data for violent discipline rates. |
| `unicef_metadata (1).csv`          | Metadata description for UNICEF indicators.      |
| `ne_110m_admin_0_countries.zip`    | Shapefile data for drawing the world map.         |
| `Untitled23.ipynb`                 | Jupyter Notebook with data cleaning and plots.    |
| `unicef_report.qmd`                | Quarto file for clean HTML reporting.             |

## Steps Performed

1. **Loaded and cleaned** the UNICEF data.
2. **Downloaded** and **extracted** the Natural Earth world shapefile.
3. **Merged** country shapefile data with UNICEF indicator data.
4. **Plotted** four key visualizations:
   - Choropleth world map.
   - Top countries bar chart.
   - Scatterplot with linear regression.
   - Density plot of distribution.
5. **Rendered** the project using **Quarto** to generate a final HTML report.

## Requirements

Install the following libraries if not already available:
```bash
pip install pandas geopandas plotnine requests
```

To render Quarto `.qmd` file:
```bash
pip install quarto-cli
```

## How to Run

1. Open the `Untitled23.ipynb` notebook on Google Colab.
2. Run all cells to generate the plots.
3. Alternatively, render `unicef_report.qmd` locally or on GitHub Pages to produce the final HTML report.

## Credits
- UNICEF Data Source: [UNICEF Global Databases](https://data.unicef.org/)
- World Shape Data: [Natural Earth Data](https://www.naturalearthdata.com/)

## License
This project is for educational and awareness purposes only.
