# Global_Health_Trend_Dashboard
This repository provides a comprehensive overview of global health trends from 2000 to 2021, focusing on key indicators such as Life Expectancy (LE), Healthy Life Expectancy (HALE), Fertility Rate, Adult Mortality Rate, and Universal Health Coverage (UHC) Service Coverage Index. These indicators are analyzed in relation to GDP across countries, continents, and regions to understand health disparities and economic influences on public health.

## Introduction


## Key Indicators
- **Life Expectancy (LE):** average number of years a newborn is expected to live under current mortality conditions. It is a crucial indicator of a country’s overall health and socioeconomic development.
- **Healthy Life Expectancy (HALE):** estimates the average number of years a person is expected to live in good health, free from severe illness or disability. It provides a better measure of quality of life compared to total life expectancy.
- **Fertility Rate:** average number of children a woman is expected to have in her lifetime. It reflects reproductive health, access to family planning, and social-economic conditions.
- **Adult Mortality Rate:** measures the probability of dying between ages 15 and 60 per 1,000 population. It helps assess the impact of diseases, healthcare access, and lifestyle factors on adult survival.
- **Universal Health Coverage (UHC) Service Coverage Index:** measures access to essential healthcare services, including maternal care, vaccinations, and disease treatment. A higher UHC index indicates better healthcare accessibility and quality.
- **Gross Domestic Product (GDP):** total value of goods and services produced within a country. It serves as a key economic indicator influencing healthcare, infrastructure, and overall well-being.
- **Country Classification:** categorized based on UN regions (continents), Sub-regions, SDG Regions and income level (as defined by the World Bank).

## About the Datasets
Each dataset conatins similar columns namely:
- **Indicator Code:** Unique identifier for each health or economic metric.
- **Continent:** The geographic region where the country is located.
- **Continent Code:** A standardized alphabetical code representing each continent.
- **Country:** The name of the nation being analyzed.
- **Country Code:** A standardized code assigned to each country for classification.
- **Year:** The specific year for which the data is recorded.
- **Sex:** The demographic category (Male, Female, or Both sexes).
- **Value:** The primary recorded figure for the indicator.
- **Low Value:** The minimum figure for the indicator.
- **High Value:** The maximum figure for the indicator

Country Classification Dataset contains specific columns namely:
- **Sub Region:** A geographic division within a continent for regional analysis.
- **SDG Region:** A classification based on Sustainable Development Goal (SDG) monitoring.
- **World Income Group:** A country classification by income level (Low, Lower-Middle, Upper-Middle, High) by World Bank.

## Objectives
- **Analyze Global Health Trends:** Examine changes in life expectancy, healthy life expectancy, fertility rate, and adult mortality rate across countries and regions.
- **Assess Healthcare Access:** Evaluate Universal Health Coverage (UHC) service levels and disparities.
- **Explore Economic Impact:** Investigate the relationship between GDP and health outcomes.
- **Compare Regional and Income Group Disparities:** Identify variations across continents, sub-regions, SDG regions, and World Income Groups.
- **Support Data-Driven Policy Making:** Provide insights for policymakers to improve healthcare systems and access.

## Tools
- Excel
- Power BI

## Technique and Skills
- Data Cleaning
- Data Normalization
- Data Transformation with Powery Query
- Data Modelling
- Custom Map Import
- DAX
- Page Navigation
- Slicers for interactive filtering
- Custom Informative Tooltip
- Report Automation
- Data Visualization

## Datasource
<a href = "https://www.who.int/data/gho/data/indicators/indicators-index"> WHO </a> 

<a href = "https://databank.worldbank.org/source/world-development-indicators/Series/SH.UHC.SRVS.CV.XD"> World Bank Group </a>

## Data Model
The datasets were first normalized in Excel, then transformed in Power Query. Date columns were created for each datasets using the year column in Power Query. Then, date table was created. Finally relationships were created between the tables in the dataset. 

![Data Model](Link)

## Dashboard Insights
### Global Health Trend Overview
Global health has significantly evolved from 2000 to 2021, driven by advancements in healthcare access, economic growth, and policy interventions.

### Life Expectancy and Healthy Life Expectancy

![Life Expectancy Dashboard](Link) 

- **World Life Expectancy:** 

### Fertility Rate

![Fertility Rate Dashboard](Link) 

- **World Fertility Rate:** 

### Adult Mortality Rate

![AMR](Link) 

- **World Adult Mortality Rate:** 

### Universal Health Coverage (UHC) Service Coverage Index 

![UHC](Link) 

- **UHC** 

### Key Metric


## Recommendations


## Conclusion


## Download
<a href = "Link"> Download the Power BI file </a>
