# Analysis and Visualization of Global Health Trends from 2000 - 2021

## Introduction
This repository provides a comprehensive overview of global health trends from 2000 to 2021, focusing on key indicators such as Life Expectancy (LE), Healthy Life Expectancy (HALE), Fertility Rate, Adult Mortality Rate, and Universal Health Coverage (UHC) Service Coverage Index. These indicators are analyzed in relation to GDP across countries, continents, and regions to understand health disparities and economic influences on public health.

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

![Data Model](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_data_model.png)

## Dashboard Insights
### Global Health Trend Overview
Global health has significantly evolved from 2000 to 2021, driven by advancements in healthcare access, economic growth, and policy interventions.

### Life Expectancy and Healthy Life Expectancy
Life Expectancy (LE) and Healthy Life Expectancy (HALE) has significantly improved over the past two decades, reflecting advancements in healthcare, disease prevention, economic development, and living standards. However, disparities remain across regions and income groups due to differences in healthcare access, socio-economic conditions, and public health policies.

![Life Expectancy Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_LE%26HALE.png)

- **Shape Map Insight:** The Shape Map provides a dynamic, year-by-year transition that clearly illustrates the global increase in Life Expectancy, with regional variations based on economic development, healthcare access, and policy initiatives.

- **World Life Expectancy:** World Life Expectancy increased from 68 years in 2000 to 72 years in 2021, marking a 6-year global gain over two decades. The rate of increase varies significantly across continents, and individual countries.

- **Trends in LE and HALE:** Both LE and HALE have increased over time across most countries. HALE consistently makes up about 85–90% of total LE, meaning that while people are living longer, some years are lived with illness or disability.

- **Developement Status:** Developed countries consistently show higher LE (70+ years) with slower growth. Developing countries started at lower LE (~60 years) but have shown significant increases.
  
### Fertility Rate
The World Fertility Rate has experienced a significant decline over the past two decades, decreasing from 2.8 births per woman in 2000 to 2.3 births per woman in 2021. This global trend reflects a shift toward smaller family sizes, driven by economic development, improved healthcare, increased education levels, and greater access to contraception. However, the rate of decline varies considerably across continents, regions, and individual countries, influenced by socioeconomic factors, cultural norms, and government policies.

![Fertility Rate Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_FR.png) 

- **Shape Map Insight:** The Shape Map provides a dynamic, year-by-year transition that visually captures the global decline in Fertility Rate while highlighting regional variations influenced by economic development, healthcare access, cultural norms, and government policies.

- **World Fertility Rate:** World Fertility Rate decreased from 2.8 birth per woman in 2000 to 2.3 births per woman in 2021, marking global decline over two decades. The rate of increase varies significantly across continents, and individual countries.

#### Continental Trends
- **Africa** (Highest Fertility, Gradual Decline): Despite progress, Sub-Saharan Africa continues to have the highest fertility rates (above 4.0 births per woman). Countries like Niger, Chad, and Somalia still have fertility rates exceeding 5.0 births, but family planning programs are driving a slow decline.

- **Asia** (Steady Decline, Aging Populations in Some Regions): East Asia, including China, Japan, and South Korea, now has some of the lowest fertility rates globally (below 1.5 births per woman).

- **Europe & North America:** Lowest fertility rates (1.3–1.8 births per woman), contributing to aging populations.

- **Latin America & Oceania:** Moderate declines, with some countries stabilizing around 2.0 births per woman.

#### Fertility Rate and GDP Correlation 
There is a strong inverse correlation between fertility rate and GDP per capita, with higher-income countries generally experiencing lower birth rates. This trend highlights the impact of economic development, healthcare access, and social factors on reproductive behavior.

- Low-Income Countries (Low GDP, High Fertility)

- Middle-Income Countries (Rising GDP, Declining Fertility)

- High-Income Countries (High GDP, Low Fertility) 

#### Key Influencing Factors:
- **Education & Urbanization:** Economic shifts and lifestyle changes lead to smaller families.

- **Healthcare Access:** Expanded contraception and maternal care reduce unintended pregnancies.

- **Government Policies**: Some countries promote higher births (e.g., France, Hungary), while others previously enforced restrictions (e.g., China).

### Adult Mortality Rate

![AMR Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_AMR.png) 

- **World Adult Mortality Rate:** 

### Universal Health Coverage (UHC) Service Coverage Index 

![UHC SCI Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_UHC_SCI.png) 

- **UHC** 

### Key Metric


## Recommendations


## Conclusion


## Download
<a href = "https://github.com/Faithe7/Global_Health_Trend_Dashboard/raw/refs/heads/main/Assets/Faith_Eliot_Global_Health_Trends_Dashboard.pbix"> Download the Power BI file </a>
