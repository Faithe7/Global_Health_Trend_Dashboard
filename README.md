# Analysis and Visualization of Global Health Trends from 2000 - 2021

## Introduction
This repository provides a comprehensive overview of global health trends from 2000 to 2021, focusing on key indicators such as Life Expectancy (LE), Healthy Life Expectancy (HALE), Fertility Rate, Adult Mortality Rate, and Universal Health Coverage (UHC) Service Coverage Index. These indicators are analyzed in relation to GDP across countries, continents, and regions to understand health disparities and economic influences on public health.

## Key Indicators
- **Life Expectancy (LE):** average number of years a newborn is expected to live under current mortality conditions. It is a crucial indicator of a country’s overall health and socioeconomic development.
- **Healthy Life Expectancy (HALE):** average number of years a person is expected to live in good health, free from severe illness or disability. It provides a better measure of quality of life compared to total life expectancy.
- **Fertility Rate:** average number of children a woman is expected to have in her lifetime. It reflects reproductive health, access to family planning, and social-economic conditions.
- **Adult Mortality Rate:** measures the probability of dying between ages 15 and 60 per 1,000 population. It assesses the impact of diseases, healthcare access, and lifestyle factors on adult survival.
- **Universal Health Coverage (UHC) Service Coverage Index:** measures access to essential healthcare services, including maternal care, vaccinations, and disease treatment. A higher UHC index indicates better healthcare accessibility and quality.
- **Gross Domestic Product (GDP):** total value of goods and services produced within a country. It serves as a key economic indicator influencing healthcare, infrastructure, and overall well-being.
- **Country Classification:** categorized based on UN regions (Continents), Sub-regions, SDG Regions and income level (as defined by the World Bank).

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
- **World Income Group:** A country classification by income level (Low-Income, Middle-Income, High-Income) by World Bank.

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

### Life Expectancy
Life Expectancy (LE) measures the average number of years a person is expected to live, reflecting healthcare quality, socioeconomic conditions, and disease burden. Over the past two decades, global LE increased from ~68 years (2000) to ~72 years (2021), driven by improvements in healthcare systems, disease control, and living standards. However, disparities persist across countries, income levels, and development status.

![Life Expectancy Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_LE%26HALE.png)

#### Map Insight
The shape map dynamically visualizes LE trends by year and country, showcasing progress in developed nations and gaps in low-income regions.
- 2000: Lowest LE in Sub-Saharan Africa & South Asia, largely due to infectious diseases and poor healthcare access.
- 2021: Significant LE improvements, especially in East Asia, Latin America, and parts of Africa, attributed to expanded healthcare programs and reduced mortality rates.

#### Drop in World Life Expectancy in 2020
In 2020, global life expectancy (LE) declined for the first time in decades, primarily due to the COVID-19 pandemic. Key factors contributing to this decline include:
- High COVID-19 Mortality: Millions of deaths, especially among the elderly and vulnerable.
- Healthcare Disruptions: Overburdened hospitals, delayed treatments, and reduced routine care.
- Public Health Setbacks: Interrupted vaccinations, maternal health services, and disease control programs.
- Economic & Social Impact: Increased poverty, mental health crises, and substance abuse.

#### LE vs. HALE (Healthy Life Expectancy)
Both LE and HALE have increased over time across most countries. HALE consistently makes up about 85–90% of total LE, meaning that while people are living longer, some years are lived with illness or disability.
- HALE measures years lived in good health, accounting for disabilities and disease burdens.
- HALE is consistently ~8-10 years lower than LE, highlighting the impact of chronic diseases, aging populations, and healthcare disparities.
- HALE growth is slower than LE, emphasizing the need for improved disease prevention and long-term healthcare strategies.

#### LE by Development Status (Developed vs. Developing Nations)
- **Developed Countries:** LE ranges from 70 to 80 years due to universal healthcare, medical advancements, and high living standards.
- **Developing Countries:** LE varies from 40 to 75 years, with growth depending on healthcare access, economic development, and public health initiatives. Many low-income nations still struggle with infectious diseases, maternal health, and healthcare accessibility.

#### LE and GDP Correlation
Higher GDP strongly correlates with higher LE (e.g., Europe, North America, Australia & New Zealand).
  
### Fertility Rate
The World Fertility Rate has experienced a significant decline over the past two decades, decreasing from 2.8 births per woman in 2000 to 2.3 births per woman in 2021. This global trend reflects a shift toward smaller family sizes, driven by economic development, improved healthcare, increased education levels, and greater access to contraception. However, the rate of decline varies considerably across continents, regions, and individual countries, influenced by socioeconomic factors, cultural norms, and government policies.

![Fertility Rate Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_FR.png) 

#### Map Insight
The Shape Map provides a dynamic, year-by-year transition that visually captures the global decline in Fertility Rate while highlighting regional variations influenced by economic development, healthcare access, cultural norms, and government policies.
  
#### World Fertility Rate
World Fertility Rate decreased from 2.8 birth per woman in 2000 to 2.3 births per woman in 2021, marking global decline over two decades. The rate of increase varies significantly across continents, and individual countries.

#### Continental Trends
- **Africa** (Highest Fertility, Gradual Decline): Despite progress, Sub-Saharan Africa continues to have the highest fertility rates (above 4 births per woman). Countries like Niger, Chad, and Somalia still have fertility rates exceeding 5 births, but family planning programs are driving a slow decline.
- **Asia** (Steady Decline, Aging Populations in Some Regions): East Asia, including China, Japan, and South Korea, now has some of the lowest fertility rates globally (below 1.5 births per woman).
- **Europe & North America:** Lowest fertility rates (1.3–1.8 births per woman), contributing to aging populations.
- **Latin America & Oceania:** Moderate declines, with some countries having around 2 births per woman.

#### Fertility Rate and GDP Correlation 
There is a strong inverse correlation between fertility rate and GDP per capita, with higher-income countries generally experiencing lower birth rates. This trend highlights the impact of economic development, healthcare access, and social factors on reproductive behavior.
- Low-Income Countries (Low GDP, High Fertility)
- Middle-Income Countries (Rising GDP, Declining Fertility)
- High-Income Countries (High GDP, Low Fertility) 

### Adult Mortality Rate
Adult Mortality Rate (AMR) represents the probability of dying between ages 15 and 60 per 1,000 population, highlighting health system effectiveness, socioeconomic conditions, and disease burden. Despite global improvements, AMR trends vary significantly across countries, gender, income groups, and UHC coverage levels.

![AMR Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_AMR.png) 

#### Map Insights
The map visualization dynamically tracks AMR changes year by year, revealing how countries with improved healthcare systems show declining mortality rates, while conflict-affected and low-income countries struggle.
- **2000:** Higher AMR in Sub-Saharan Africa, South Asia, and parts of Latin America.
- **2021:** Significant reductions in East Asia, Latin America, and high-income nations, while some low-income regions remain stagnant.

#### AMR Trends by Gender
Yearly Fluctuation in AMR rate can be seen among male and female based on countries. 
- Men consistently have higher AMR across all regions due to higher exposure to risk factors (e.g., occupational hazards, smoking, alcohol use, violence etc.).
- Women exhibit lower AMR, benefiting from better health-seeking behaviors and lower exposure to certain risk factors.

#### AMR by Income Group
- **High-Income Countries (Low AMR):** AMR consistently below 100 per 1,000, driven by advanced healthcare, preventive measures, and high UHC coverage.
- **Middle-Income Countries (Moderate AMR Decline):** Steady reductions in AMR, but challenges remain due to healthcare accessibility gaps.
- **Low-Income Countries (High AMR, Slowest Progress):** AMR remains above 250 per 1,000 in some countries due to weak health systems, poverty, and infectious disease burden.

#### AMR and UHC SCI Correlation
- Higher UHC SCI, Lower AMR (e.g., Europe, North America, Australia & New Zealand).
- Moderate UHC SCI, Gradual AMR decline (e.g., Latin America, South-East Asia).
- Low UHC SCI, Persistently High AMR (e.g., Sub-Saharan Africa, parts of South Asia, and conflict-affected regions).

### Universal Health Coverage (UHC) Service Coverage Index 
The UHC Service Coverage Index measures access to essential health services, scoring from 0 to 100, with higher values indicating broader healthcare access.

![UHC SCI Dashboard](https://github.com/Faithe7/Global_Health_Trend_Dashboard/blob/main/Assets/Global_Health_Trends_dashboard_UHC_SCI.png) 

#### Map Insights
- **Dynamic Yearly Progression:** The map illustrates UHC improvements over time, with higher-income nations achieving broader coverage while low-income regions progress more slowly.
- **Regional Variations:** Countries with strong public healthcare systems (e.g., Japan, Canada, Germany) have consistently high UHC scores (80+), while those with weaker health infrastructure (e.g., parts of Africa and South Asia) remain below 50.

#### Global UHC Index & Yearly Trend
The global average UHC SCI has steadily increased, reflecting growing healthcare investments.
- **2000:** Global UHC SCI ~ 45
- **2021:** Global UHC SCI ~ 68

#### UHC SCI Trends by SDG Regions
- **Australia & New Zealand:** 2000 UHC SCI: ~78 | 2021 UHC SCI: ~86
Consistently high UHC scores, driven by universal healthcare systems. Minimal disparities, with strong access to essential health services.
- **Central Asia & Southern Asia:** 2000 UHC SCI: ~39 | 2021 UHC SCI: ~63
Significant progress, but certain areas still face challenges.
- **Eastern Asia & South-East Asia:** 2000 UHC SCI: ~43 | 2021 UHC SCI: ~69
Improvent in coverage due to health care investment and access to essential services.
- **Latin America & the Caribbean:** 2000 UHC SCI: ~51 | 2021 UHC SCI: ~75
- **Northern America & Europe:** 2000 UHC SCI: ~67 | 2021 UHC SCI: ~81
Europe maintains high UHC scores (70–80) due to universal public healthcare. North America varies; Canada has near-universal access, while the U.S. faces some coverage gaps.
- **Oceania (Excluding Australia & New Zealand):** 2000 UHC SCI: ~38 | 2021 UHC SCI: ~51
Limited healthcare infrastructure in Pacific Island countries. Small improvements due to international health aid and regional healthcare policies.
- **Sub-Saharan Africa:** 2000 UHC SCI: ~24 | 2021 UHC SCI: ~46
Slow progress due to funding limitations and weak health systems. Namibia, Algeria, Morocco, Egypy, and South Africa show notable improvements.
- **Western Asia & Northern Africa:** 2000 UHC SCI: ~52 | 2021 UHC SCI: ~69
Oil-rich countries (UAE, Saudi Arabia) have strong public healthcare. Conflict-affected nations still struggle with healthcare access.

#### UHC SCI & GDP Correlation (Continental Overview):
- **High-Income Continents (Europe, North America):** Strong correlation between high GDP and UHC SCI above 80 due to universal healthcare policies.
- **Middle-Income Continents (Asia, Latin America):** Moderate correlation, with UHC SCI scores between 50-75, improving with economic growth and policy reforms.
- **Low-Income Continents (Africa, parts of South Asia, parts of Oceania):** Weak correlation, with UHC SCI often below 50, as economic growth alone is not sufficient without strong healthcare policies and access to healthcare services.

## Recommendations
To improve Life Expectancy (LE), Healthy Life Expectancy (HALE), Fertility Rate, Adult Mortality Rate (AMR), and Universal Health Coverage (UHC), the following key strategies are essential:
- **Strengthen Healthcare Systems:** Expand primary care, disease prevention, and emergency preparedness to enhance LE & HALE.
- **Enhance Universal Health Coverage (UHC):** Improve health infrastructure, workforce capacity, and financial protection for equitable healthcare access.
- **Address Non-Communicable & Infectious Diseases:** Invest in vaccination, chronic disease management, and mental health programs to reduce AMR.
- **Optimize Fertility & Reproductive Health:** Support family planning, maternal care, and gender equality initiatives to stabilize fertility rates.
- **Reduce Health Disparities:** Implement targeted policies in low-income regions, ensuring affordable healthcare and better health outcomes.

## Conclusion
Achieving sustainable global health improvements requires integrated healthcare policies, equitable access, and continuous investment in preventive and curative services.

## Download
<a href = "https://github.com/Faithe7/Global_Health_Trend_Dashboard/raw/refs/heads/main/Assets/Faith_Eliot_Global_Health_Trends_Dashboard.pbix"> Download the Power BI file </a>
