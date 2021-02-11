# UCD Bootcamp Data Analytics - Project 1: Anxiety and Depression in the Time of COVID-19
## Overview
This project analyzed COVID-19 case counts and levels of anxiety and depression in the US, to better understand the impact of the pandemic on the mental health of Americans. The project:
- Collected, aggregated, cleaned and re-organized key datasets (see Data Sources below).  
- Analyzed and visualized the data using bar charts, line graphs, scatter plots and linear regression models.
- Documented several powerful conclusions drawn from this analysis (see Findings below).
- The project results are fully documented in the final project presentation: Final_Project1_Pres.ppt.

## Findings
- Anxiety and depression levels increased significantly amongst the US population between 2019-2021.
    - As the numbers of national COVID cases increased and decreased throughout 2020, so did the anxiety and depression levels within the US population. 
    - This was also true at the state level in California and New York (although it wasn’t as highly correlated as the national data).
- Women reported experiencing significantly higher levels of anxiety and depression than men (roughly 25% higher) during this time. 
    - It appears that women are experiencing a higher loss of employment income, which could be a contributing factor.
- The younger the age group, the higher the levels of anxiety and depression. At the peak of the pandemic over 50% of people 18-29 years old were experiencing symptoms of anxiety or depression.	 
    - This may be, in part, a result of disrupted college plans as most college students experienced significant disruptions to their college plans

## Data Sources
- Anxiety & depression levels prior to the pandemic: https://www.cdc.gov/nchs/data/nhis/earlyrelease/ERmentalhealth-508.pdf
- Anxiety & depression levels during the pandemic: https://www.cdc.gov/nchs/covid19/pulse/mental-health.htm
- CDC COVID confirmed cases and death rates (2020-current): https://healthdata.gov/dataset/united-states-covid-19-cases-and-deaths-state-over-time
- Key factors impacting young adults –Phase III of the CDC Household Pulse Survey: https://www.census.gov/programs-surveys/household-pulse-survey/data.html#phase3
- Key COVID-19 Shutdown and Re-opening dates for California & New York Sources: State public health websites & public reporting (mt_data/COVID_State_Timeline_Data.xlsx)

## Project Artifacts
The project used a combination of Excel, Python, Pandas and Matplotlib and consists of:
- A Jupyter notebook (IAD-BaselineComparison.ipynb) that establishes a baseline for the percentage of Americans experiencing symptoms of anxiety and/or depression (IAD%)
- A Jupyter notebook (covid_19_bar_chart_covid_confirmed_cases_deaths.ipnyb) that reads in our cleaned up COVID-19 dataset (Resources/covid_19_data.csv) and generates bar charts of confirmed COVID-19 cases and deaths for the US, California and New York.
- A Jupyter notebook (IAD_Clean_DataFrames.ipynb) that reads in the IAD data (Resources/Indicators_of_Anxiety_or_Depression_Based_on_Reported_Frequency_of_Symptoms_During_Last_7_Days.csv), cleans it up and reformats it for analysis, producing a final clean dataset (output_data/AID_processed_data.csv).
- A Jupyter notebook (AID_Charts) that reads in the cleaned up IAD dataset and produces several line graphs and bar charts visualizing this data.
- A Jupyter notebook (RegressionModels.ipnyb) that reads in a merged CSV of the COVID and IAD data (mt_data/clean_covid_iad_scatter_in.csv) and produces a series of scatterplots and linear regression models.
- A Jupyter notebook (Depression and Anxiety Potential Factors Analysis.ipynb) that reads in several of latest detailed tables from the Household Pulse survey () and explores and visualizes the data via a series of dataframes and bar charts.
- All of the bar charts and line graphs are saved as .png files in the Data_Evaluation/output_data/ folder.    
- All of the scatterplots and linear regression models are stored as .png files in the mt_data\ folder.
