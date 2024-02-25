# European-High-Income-Countries-Data-Analysis

## Introduction
This project explores economic and social indicators for European high-income countries over the past 20 years, utilizing data fetched from the World Bank API. Through comprehensive data analysis, this project aims to uncover trends and insights into the economic performance, population dynamics, and social indicators of these countries.

## Objectives
To fetch real-world data on European high-income countries using the World Bank API.
To perform data cleaning and preparation for analysis.
To conduct exploratory and in-depth analysis on key economic and social indicators.
To identify trends, anomalies, and insights within the data.
Data Sources
The data was sourced from the World Bank API, focusing on the following indicators:

- GDP per Capita (Current US$)
- GDP Growth (Annual %)
- GNI per capita (Current US$)
- Total Population
- Unemployment Rate (% of Total Labor Force)
- Inflation, Consumer Prices (Annual %)
- Human Capital Index

## Methodology
### Data Collection
Utilized the wbgapi Python library to fetch data for the last 20 years across multiple indicators for European high-income countries.

### Data Preparation & Cleaning
Transformed and cleaned the data using Pandas, preparing it for analysis.

### Data Analysis
Conducted both exploratory and in-depth analysis to explore economic trends, demographic changes, and other social indicators. Analysis included the use of statistical methods and data visualization techniques.

## Key Findings

The comprehensive analysis of European high-income countries based on World Bank data revealed several key findings regarding economic health, social indicators, and the impact of economic crises:

1) Income Levels and Economic Health:

- There's a strong positive correlation between GDP per Capita and GNI per Capita, underscoring their mutual relevance as indicators of a country's economic health.
- A notable observation is the substantial income gap within the dataset, with the highest GDP per Capita significantly exceeding the lowest, pointing to disparities in economic wealth among countries.
2) Analysis of Economic Indicators:

- The study found weak correlations between inflation and GDP growth, suggesting that higher inflation does not consistently align with higher economic growth within this dataset.
- A weak inverse relationship between GDP growth and unemployment rates was observed, providing some support to Okun's law but also highlighting unique economic dynamics in these countries.
3) Impact of Economic Crises:

- Economic downturns have a significant adverse effect on both GDP and GNI per Capita, with lower-income groups experiencing more pronounced declines and slower recoveries. This suggests increased vulnerability of lower-income groups to economic fluctuations and a widening income gap during crises.
4) Inflation, Unemployment, and Economic Health:

- Both inflation and unemployment rates negatively influence GDP per Capita and GNI per Capita, indicating that financial stability is crucial for wealth creation.

## Tools & Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- wbgapi for fetching World Bank data
## How to Run
Ensure you have Python installed along with the required libraries: Pandas, Matplotlib, Seaborn, and wbgapi.

1) Clone this repository to your local machine.
2) Navigate to the project directory.
3) Run the Jupyter Notebook
## Visualization
The project includes various visualizations to represent the data analysis findings. These visualizations help in understanding the trends and patterns in the data more intuitively.

## Conclusion
This analysis provides valuable insights into the economic and social landscape of European high-income countries, highlighting the utili
