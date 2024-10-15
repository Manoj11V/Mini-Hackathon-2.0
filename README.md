# Mini-Hackathon-2.0
# India Electric Vehicle (EV) Market Analysis

## Overview
This project analyzes the electric vehicle (EV) market in India using various datasets. The analysis focuses on EV adoption trends, manufacturer performance, the impact of government policies, geographical analysis, and environmental impact. Unfortunately, there is no proper data representing the price of EVs and their features like battery life, range, or charging time, so that part of the analysis was not performed.

## Datasets
The datasets used in this analysis include:
- **EV Maker by Place:** Contains information about EV manufacturers and their locations.
- **Operational PC:** Data on the number of operational charging stations across states.
- **Vehicle Class:** Registration numbers by vehicle class.
- **EV Category (ev_cat):** Monthly data on different vehicle types and their sales over time.
- **EV Sales by Makers and Categories (ev_sales):** Sales data from various EV manufacturers from 2015 to 2024.

## Objectives

### EV Adoption Trends
- **Analysis:** The dataset `ev_sales` was used to explore the growth of EV adoption in India from 2015 to 2024.
- **Method:** A line plot was created to visualize the trend of EV sales over the years.
- **Findings:** The sales of EVs have shown a significant upward trend, particularly after 2019.

### Manufacturer Performance
- **Analysis:** EV manufacturers were compared based on their total sales from 2015 to 2024.
- **Method:** The `ev_sales` dataset was used to calculate the total sales for each manufacturer, and the top 10 performers were identified.
- **Findings:** The leading manufacturers were highlighted based on their overall contribution to the EV market.

### Price vs. Features
- **Analysis:** Unfortunately, the dataset does not contain adequate information regarding the price of EVs and their features such as battery life, range, or charging time. Therefore, this part of the analysis was skipped.

### Impact of Government Policies
- **Analysis:** The potential impact of government policies, such as the reduction of Goods and Services Tax (GST) from 12% to 5% in 2019, and the Electric Mobility Promotion Scheme (EMPS) 2024, which provides subsidies for electric two- and three-wheelers, was explored.
- **Method:** A bar chart was created to show the increase in EV adoption after these policy changes.
- **Findings:** Policy changes appear to have positively impacted EV adoption in India.

### Geographical Analysis
- **Analysis:** The EV adoption rates and the number of operational charging stations were analyzed by state.
- **Method:** Data from the `Ev_maker_df` and `Op_pc` datasets were grouped by state to identify leading regions.
- **Findings:** Delhi and Tamil Nadu lead in both EV adoption and the number of charging stations, which may indicate a higher rate of infrastructure development in these regions.

### Environmental Impact
- **Analysis:** The growth in EV production was analyzed in terms of its potential environmental impact, focusing on reduced emissions of hazardous gases.
- **Method:** A bar chart was used to visualize the overall increase in EV sales.
- **Findings:** The increased production and adoption of EVs in India contribute to the reduction of harmful emissions, supporting the push for cleaner energy.

## Tools Used
- **Data Processing and Analysis:** Pandas for data manipulation and analysis.
- **Visualization:** Matplotlib and Power BI for data visualization.

