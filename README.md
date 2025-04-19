# MSc-Forecasting-the-Distribution-of-Renewable-Energy-Sources-Production-in-Madeira

For my MSc thesis, I am working on a project titled "Forecasting the Distribution of Renewable Energy Sources Production in Madeira", which is supervised by Professor Vítor Santos and Maria Anastasiadou. I am using **real renewable energy production data**, provided by "Empresa de Eletricidade da Madeira" (EEM), the **regional utility provider**. 

The expected goal of this research is to contribute to the **reduction of Madeira’s reliance on fossil fuels**, while also supporting the United Nations' 7th Sustainable Development Goal (Affordable and Clean Energy). 
Due to compliance restrictions, the Jupyter Notebook files and original datasets cannot be shared. Instead, a description of the project's scope, data description and transformation process **will be provided** on the "Data" section.

## Overview

Climate change is a consequence of the utilization of **fossil fuels**, which were key factors to human industrialization and advancements, ever since the first industrial revolution. Nonetheless, fossil fuels need to be burnt to generate energy, and when they burn, they release **large amounts of harmful gases**, with the most noteworthy being Carbon Dioxide. This gas is the **main responsible** for climate change.

Nevertheless, Energy is an absolute must for ensuring that people can fulfill their **primary needs**, such as cooking, heating and transportation. The increased urge of cleaner and limitless energy sources has led to the increased use of renewable energy sources over the last years, as these are **greener** and **unlimited**.

However, Madeira Island, a small Portuguese island located in the North Atlantic Ocean, is not an exception to global energy challenge. Despite significant efforts, **only 40% of Madeira’s energy production comes from renewable sources**, compared to **75% on Portugal’s mainland**. One of the key limiting factors is **weather variability**, which constrains Madeira's ability to rely more on renewable energy. 

Hence, this project aims to **mitigate weather variability**, by producing **accurate renewable energy production forecasts**, to sustain decision-making in Madeira.

This project is following the **CRISP-DM Methodology**.  

## Data

This project is using the following data:

### Data from EEM

* **Solar**, **Wind**, **Biomass**, **Hydropower**, **Fossil Fuel** and **Natural Gas** energy production, every 15 minutes, from January 1st 2021 until August 31st 2024.
  
* Yearly evolution of the **installed capacity** for each of the aforementioned energy sources from 2021 to 2025.

### Weather Data

Given the critical role of weather conditions in generating accurate forecasts, this research incorporates weather data obtained through the Visual Crossing Weather API (visualcrossing.com).
The following weather variables were collected on an hourly basis from January 1st 2021 until August 31st 2024:

* **temp** - Temperature recorded at the corresponding weather station, measured in degrees Celsius.
  
* **humidity** - Relative Humidity recorded at the corresponding weather station, in %.
  
* **dew** -  measured temperature at which air is saturated with water vapor and condensation occurs, at the corresponding weather station, in degrees Celsius.
  
*  **precip** - precipitation recorded at the corresponding weather station, in millimeters.
  
*  **windgust** -  brief or sudden increase in wind speed, at the corresponding weather station, in kph.

*  **windspeed**- rate at which air moves from one place to another, at the corresponding weather station, in kph.

*  **winddir** - direction from which the wind is blowing, at the corresponding weather station, in degrees.

*  **pressure** - Sea Level Pressure, at the corresponding weather station, in mb.

*  **visibility** - maximum distance at which objects can be clearly seen in daylight, at the corresponding weather station, in km.

*   **cloudiness** - portion of the sky covered by clouds, at the corresponding weather station, in km.

*   **solarradiation** - power of sunlight received, at the corresponding weather station, in W/m2.
