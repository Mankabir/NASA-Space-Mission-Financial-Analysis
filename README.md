# Exploring NASA's Budgets: A Deep Dive into the Cost of Solar System Exploration

## Overview
This repository contains a Jupyter notebook that provides a comprehensive analysis of NASA's budgets over the past 60 years, focusing on the costs associated with solar system exploration. Utilizing a dataset provided by The Planetary Society, this project offers insights into the financial aspects of some of the most ambitious space missions.

## Dataset
The analysis is based on three primary tables:

1. **mission_budgets**: 
   - **Columns**: `mission`, `fiscal_year`, `cost_type`, `cost_group`, `cost_MUSD`
   - **Description**: Each row represents the cost in a fiscal year of one aspect of a project for a specific mission. Costs are detailed in million US dollars.

2. **inflation**:
   - **Columns**: `fiscal_year`, `inflation_adjustment`
   - **Description**: Provides inflation adjustment factors for each fiscal year. The year 1976 includes two values due to high inflation - "1976" for the start of the year and "1976TQ" for the third quarter onwards.

3. **mission_details**:
   - **Columns**: `mission`, `mission_full_name`, `destination`, `program`
   - **Description**: Contains details about each mission, including its full name, destination in the solar system, and the NASA program it is part of.

## Analysis Overview
The Jupyter notebook conducts several analyses, including:

- Calculation of total mission costs and adjustments for inflation.
- Identification of the highest-cost mission when adjusted for inflation.
- Analysis of yearly spending trends and allocation of funds to different destinations.
- Visualizations that highlight spending patterns over time and across different solar system destinations.

## Acknowledgements
Data used in this analysis is sourced from the [Planetary Exploration Budget Dataset](https://www.planetary.org/space-policy/planetary-exploration-budget-dataset) provided by The Planetary Society.
