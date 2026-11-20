# Tourism as an Economic Engine — Saudi Arabia Vision 2030

A reconstructed data-analysis project examining the relationship between tourism expenditure and Saudi Arabia's economic diversification under Vision 2030.

## What the project studies

The original study combined tourism and macroeconomic indicators from sources including the World Bank, UN Tourism (UNWTO), and WTTC. It used time-series comparison, correlation analysis, data visualization, and an ARIMA forecasting framework to investigate how tourism development relates to Saudi Arabia's broader economic trajectory.

The original project draft reports a **moderate positive correlation of r = 0.495** between tourism expenditure and GDP. That value is retained here as a *reported result from the original analysis*; the full historical dataset used to produce it was not recoverable from the old project files.

## Repository structure

```text
tourism-economic-engine/
├── README.md
├── requirements.txt
├── data/
│   └── recovered_observations.csv
├── analysis/
│   └── tourism_analysis.ipynb
├── visuals/
│   ├── recovered_gdp_trend.png
│   └── recovered_tourism_trend.png
└── paper/
    └── original_project_draft.pdf
```

## Recovered evidence

The surviving paper contains explicit observations for GDP and tourism expenditure in selected years, including 2002, 2010, 2015, 2019, and 2021. These values are stored in `data/recovered_observations.csv` with notes describing whether each value was directly reported or unavailable.

The notebook deliberately **does not invent missing historical observations**. It visualizes the recovered data, documents the original `r = 0.495` result, and contains a reusable ARIMA workflow that can be run after the full World Bank/UN Tourism series is restored.

## Methods

- Data cleaning and organization
- Time-series trend analysis
- Comparative analysis around Vision 2030
- Pearson correlation analysis
- ARIMA time-series forecasting framework
- Economic data visualization

## Key finding from the original study

The original analysis reported `r = 0.495` between international tourism expenditure and GDP, indicating a moderate positive relationship. This should be interpreted as association rather than evidence that tourism alone caused GDP growth.

## Data sources

- World Bank — GDP (current US$): https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=SA
- World Bank / UN Tourism — International tourism expenditures: https://data.worldbank.org/indicator/ST.INT.XPND.CD
- UN Tourism: https://www.unwto.org/tourism-statistics/key-tourism-statistics
- WTTC: https://wttc.org/
- Saudi Vision 2030: https://www.vision2030.gov.sa/

## Status

**Reconstructed from surviving project material.** The original raw analysis files were lost. The repository preserves the original paper, recovered observations, and a reproducible analysis scaffold without fabricating missing data.

## Author

Sahib Preet Singh
