# U.S. Immigration Data Analysis

**Alaina Liu | Data Analysis & Visualization Research**

## Overview

This project explores long-term U.S. immigration trends using data from the **Office of Homeland Security Statistics (OHSS), Yearbook of Immigration Statistics 2022**. The analysis examines lawful permanent residence from **1820–2022** and compares refugee and asylum patterns, with particular attention to China, Asia, and overall U.S. totals.

The work uses **Python, pandas, and Plotly** to clean and reshape government data, create comparative visualizations, and interpret changes across time.

## Questions explored

- How has lawful immigration to the United States changed over two centuries?
- How have immigration trends from China compared with overall immigration patterns?
- How did different admission categories contribute to Chinese and overall lawful permanent residence in 2022?
- How did refugee arrivals and affirmative versus defensive asylum outcomes change across **2013–2022**?

## Analysis in the notebook

1. **Lawful permanent residents (1820–2022):** Long-term trends in U.S. immigration.
2. **China and overall immigration by decade:** Compare totals, changes, and China's percentage of overall immigration.
3. **Classes of admission:** Compare admission categories for Chinese and overall lawful permanent residents in FY2022.
4. **Refugees:** Explore refugee arrivals for China, Asia, and all nationalities.
5. **Asylum:** Compare affirmative and defensive grants over time using time-series figures and visual dashboards.

## Research materials

- **[Open the Jupyter notebook](Alaina_immigration_analysis_final.ipynb)** — complete project code, written analysis, tables, and saved visualization outputs.

- **[Read the completed research report (PDF)](reports/US_Immigration_Research_Report_2026.pdf)** — five-page report with methods, figures, key results, and limitations.

## Source data and reproducibility

The notebook loads two OHSS Excel workbooks by filename:

- `lawful_permanent_residents_fy2022.xlsx`
- `refugees_and_asylees_fy2022.xlsx`

They are **not included in this repository**. The original source tables can be obtained from the official [OHSS Yearbook of Immigration Statistics](https://ohss.dhs.gov/topics/immigration/yearbook). To rerun the notebook, place both workbooks in the same directory as the notebook so that its existing relative file paths resolve.

The notebook includes saved outputs to help readers inspect the analysis without rerunning it. Some interactive Plotly displays may require opening the notebook in Jupyter or Colab for full interactivity.

## Tools

Python · pandas · NumPy · Plotly · Matplotlib · Jupyter Notebook

---

*Research findings, caveats, and source references are documented in the completed report and notebook. The analysis is descriptive and does not establish causal effects of immigration policies.*
