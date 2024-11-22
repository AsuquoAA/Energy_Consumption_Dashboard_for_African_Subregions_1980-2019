# Energy Consumption Dashboard for African Subregions (1980–2019)

This interactive dashboard allows users to explore the major energy sources across various subregions in Africa and analyze which subregion produced the highest amount of energy for consumption from 1980 to 2019.

---

## Research Question

1. What are the major energy sources in the subregions of Africa
2. Which subregion produces the highest amount of energy for consumption from 1980 to 2019?

---

## Features

1. Interactive Grid: The dashboard contains a 3x3 grid layout where:
- 5 Interactive Bar Charts: These bar charts represent the energy sources for the countries in Northern, Western, Central, Eastern, and Southern Africa. The bar charts are dynamically updated based on the year selected using the slider.
- 1 Static Line Chart: A larger, static line chart shows the total energy consumption of each African subregion (North, West, Central, East, South) from 1980 to 2019. This chart provides a comprehensive view of the energy consumption trends for each subregion.
2. Year Slider: The year slider allows users to interactively choose a year between 1980 and 2019, and the bar charts are updated accordingly to reflect the energy sources for that year in each subregion.

---

## Setup and Installation

To run this dashboard, the following libraries are required:
  1. pandas
  2. numpy
  3. matplotlib
  4. seaborn
  5. ipywidgets
- code: pip install pandas numpy matplotlib seaborn ipywidgets

---

## How to run this project

1. Clone the Repository:
- code: git clone https://github.com/Lazycodes/Energy_Consumption_Dashboard_for_African_Subregions_1980-2019.git
2. Navigating to directory
- code: cd Energy_Consumption_Dashboard_for_African_Subregions_1980-2019

---

## Dataset Sources

1. <a href="https://github.com/Lazycodes/Energy_Consumption_Dashboard_for_African_Subregions_1980-2019/blob/main/energy.csv">Energy_Consumption_Data</a>
2. <a href="https://www.worldometers.info/geography/how-many-countries-in-africa/">African_Countries_Information</a>

---

## Process Workflow

### Data Processing

- The energy data is cleaned by removing unnecessary columns, replacing certain country names for consistency, and converting energy consumption values from quads to petajoules (PJ).
- The dataset is reshaped into a pivot table for easy analysis, and missing values are filled with zeros to indicate zero energy consumption for certain years and countries.
- The country-subregion data is cleaned and merged with the energy data, allowing the analysis of energy consumption by subregion.

### Analysis

- The analysis is split into five subregions: Northern Africa, Western Africa, Central Africa, Eastern Africa, and Southern Africa.
- The total energy consumption for each subregion is calculated, and interactive visualizations are provided to display the energy sources for each subregion across different years.
- A static plot displays the total energy consumption of each subregion from 1980 to 2019.
- A slider is used to interactively update the energy sources by year.

### Sample Output
![Sample_Output1](https://github.com/Lazycodes/Energy_Consumption_Dashboard_for_African_Subregions_1980-2019/blob/main/Screenshot%202024-11-22%20at%2022.07.53.png)
![Sample_Output2](https://github.com/Lazycodes/Energy_Consumption_Dashboard_for_African_Subregions_1980-2019/blob/main/Screenshot%202024-11-22%20at%2022.05.44.png)
![Sample_Output3](https://github.com/Lazycodes/Energy_Consumption_Dashboard_for_African_Subregions_1980-2019/blob/main/Screenshot%202024-11-22%20at%2022.04.51.png)

---

## Acknowledgements
I would like to express my sincere gratitude to the University of Michigan for providing me with the opportunity to develop and apply my skills through their courses. Their exceptional teaching resources have significantly contributed to the completion of this project.
