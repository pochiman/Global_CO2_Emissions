# Global CO2 Emissions

## The Situation
You've recently been hired as a Data Analyst at Maven Environmental, a US-based environmental non-profit organization.

## The Assignment
To better understand which regions are the global drivers of carbon emissions and their impact, you'll be leveraging CO2 emission data from 1750 - 2022.
Your goal is to transform the data into a dynamic dashboard that the public can use to identify patterns, trends and drivers of global CO2 emissions.

## The Objectives
1. Profile and QA the data
2. Prepare the data for visualization
3. Visualize the data and summarize findings

## The Data Set

#### Global CO2 Emissions
This data set includes global fossil fuel emissions data from 1750 - 2021 by country, paired with population data for the same year/country detail. Historical CO2 datapoints are estimated based off the industrial factors reflected in each time period.

#### Recommended Analysis
1. How have global emissions of carbon dioxide (CO2) changed over time?
2. Who emits the most CO2 each year?
3. Where in the world does the average person emit the most carbon dioxide (CO2) each year?
4. How have global emissions of carbon dioxide (CO2) from fossil fuels and land use changed over time?

#### Objective 1: Profile and QA the data
Your first objective is to explore and profile the data while optimizing the source for visualization including: filtering out records which aren't at the country level, updating field types and creating a parameter.

* Connect to the visualizing_global_co2_data csv (extract the data). Take a moment to familiarize yourself with the data. Which countries are the largest contributors of CO2?
* Add a data source filter to exclude NULL iso codes
* Convert all fields with “Co2” in their name to be Number (whole) data types and change them to be continuous measures
* Create a new integer type parameter named Top N with a default value of 10

#### Objective 2: Visualize the data
Your second objective is to visualize the data using a line chart, map and scatter plot to show the trends and relationships between CO2 emissions and country populations.

* Create a sheet with a line chart showing the % of total share of CO2 by year for the top 10 countries using your TOP N parameter (remove any null value countries)
* Create a sheet with a map at country level using Co2 Per Capita for the year 2021 only (fix any country/region errors, remove null value countries)
* Create a sheet with a scatter plot comparing Co2 and population at country level, with bubbles sized by Temperature Change From Co2 for the year 2021 (BONUS: Add a linear regression trend line)
* Color all 3 visualizations using Co2 per capita and apply a divergent color scale

#### Objective 3: Build an interactive dashboard
Your final objective is to build an interactive dashboard combinining your 3 visualizations in addition to filters/parameters for user interaction.

* Add sheets to your dashboard to show % of Co2 trend as a line chart, Co2 per capita as a map, and the relationships between Co2 and population as a scatter plot
* Assemble the charts into a rough dashboard layout and include a title and TOP N parameter at the top of your dashboard (you can design your own layout, or follow the solution)
* Add a filter for country (TIP: create a copy of the country field to avoid impacting your TOP function), and apply the filter to all sheets on the dashboard (make the filter in-context)
* Adjust formatting, alignment and polish to finalize the dashboard
* Do you notice any interesting patterns or trends? What insights do you find when looking at the global Co2 impact and trends?

#### [Project Link](https://public.tableau.com/app/profile/pocholo.tan/viz/GlobalCO2Emissions_17458938698770/GlobalCO2Emissions?publish=yes)