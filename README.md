# MSc-Forecasting-the-Distribution-of-Renewable-Energy-Sources-Production-in-Madeira

For my MSc thesis, I am working on a project titled "Forecasting the Distribution of Renewable Energy Sources Production in Madeira", which is suoervised by Professor Vítor Santos and Maria Anastasiadou. I am using real renewable energy production data, provided by "Empresa de Eletricidade da Madeira" (EEM), the regional utility provider. The expected goal of this research is to contribute to the reduction of Madeira’s reliance on fossil fuels, while also supporting the United Nations' 7th Sustainable Development Goal (Affordable and Clean Energy). Due to compliance reasons, the Jupyter Notebook files nor the original datasets can be shared here, instead a description of the scope of the project and data transformations will be shared:

## Overview

Climate change is a consequence of the utilization of fossil fuels, which were key factors to human industrialization and advancements, ever since the first industrial revolution. Nonetheless, fossil fuels need to be burnt to generate energy, and when they burn, they release large amounts of harmful gases, with the most noteworthy being Carbon Dioxide. This gas is the main responsible for climate change.

Nevertheless, Energy is an absolute must for ensuring that people can fulfill their primary needs, such as cooking, heating and transportation. The increased urge of cleaner and limitless energy sources as led to the increased use of renewable energy sources over the last years, as these are greener and unlimited.

However, Madeira Island, a small Portuguese island located in the North Atlantic Ocean, is not an exception to this energy reality. Despite all the efforts that have been conducted, only 40% of Madeira’s energy production comes from renewable sources. In comparison, 75% of Portugal’s mainland energy production comes from renewable sources. Weather variability constrains Madeira's reliance on renewable energy. 

Hence, this project aims to mitigate weather variability, by producing accurate renewable energy production forecasts, to sustain decision-making in Madeira.

This project is following the CRISP-DM Methodology.  

## Data

This project is using the following data:

### Data from EEM

* Solar, Wind, Biomass, Hydropower, Fossil Fuel and Natural Gas energy production, Every 15 minutes, from January 1st 2021 until August 31st 2024.
  
* Yearly evolution of the installed capacity for each of the aforementioned energy sources from 2021 to 2025.

### Weather Data

Given the importance of weather data for producing accurate forecasts, this research is complemented with weather data retrieved via Visual Crossing Weather API (https://www.visualcrossing.com/). 
The following weather variables were retrieved from the aforementioned API, in an hourly format, from 1st of January 2021 until 31st of August 2024:

* **temp** - Temperature on the corresponding weather station, in Celsius Degrees.
  
* **humidity** - Relative Humidity on the corresponding weather station, in %.
  
* **dew** - the temperature at which air is saturated with water vapor and condensation occurs, on the corresponding weather station, in Celsius Degrees.
  
*  **precip** - Precipitation on the corresponding weather station, in milimeters.
  
*  **windgust** -  brief or sudden increase in wind speed, on the corresponding weather station, in kph.

*  **windspeed**- rate at which air moves from one place to another, on the corresponding weather station, in kph.

*  **winddir** - direction from which the wind is blowing, on the corresponding weather station, in degrees.

*  **pressure** - Sea Level Pressure, in mb.

*  **visibility** - maximum distance at which objects can be clearly seen in daylight, on the corresponding weather station, in km.

*   **cloudiness** - portion of the sky covered by clouds, on the corresponding weather station, in km.

*   **solarradiation** - power of sunlight received, in W/m2.
