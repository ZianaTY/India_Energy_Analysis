# A Transition in Progress: Analyzing India's Energy Production and Consumption from 1991 to 2022 in the Context of Green Energy

## Project Overview

This project aims to analyze the transformation of India’s energy sector from 1991 to 2022, with a particular focus on the transition towards renewable energy sources in the post-liberalization era. The study examines key trends in energy production and consumption, highlighting India’s growing capacity to integrate green energy into its energy mix. By assessing the share of renewables, the shift in energy consumption patterns, and the role of government policies, the analysis provides insights into India’s efforts to balance rapid economic growth with sustainability goals. The findings will offer a comprehensive understanding of how India has progressed in terms of energy diversification, with a specific focus on the development and deployment of renewable energy sources like solar, wind, hydro, and bioenergy, while continuing to rely on fossil fuels such as coal, oil, and natural gas. This project aims to evaluate the speed, challenges, and opportunities within India's energy transition journey and its capacity to achieve its sustainability and decarbonization targets in the coming decades.

## About the Dataset

This project utilizes various datasets from reputable sources to analyze India's energy production and consumption from 1991 to 2022. These datasets provide comprehensive insights into the global and national trends of energy consumption, production, and transitions to green energy. The data sources are as follows:

1. **Our World in Data**  
   - This platform provides detailed information on global energy trends, including renewable and non-renewable energy consumption and production. It aggregates data from various international organizations to offer a comprehensive view of global energy shifts. It is used extensively for analyzing energy mix, fossil fuel production, and electricity generation data.
<a href =https://ourworldindata.org >Our World in Data </a>
2. **Statistical Review of World Energy (Energy Institute, EI)**  
   - The Statistical Review provides a global perspective on energy production, consumption, and trade, offering time-series data. It serves as a key source for understanding trends in fossil fuel production, energy consumption, and electricity generation, helping to benchmark India’s energy transition against global standards.
<a href = https://www.energyinst.org/statistical-review>Statistical review of world energy (Energy Institute, EI) </a>
3. **International Energy Data (U.S. Energy Information Administration, EIA)**  
   - The EIA dataset provides open access to energy data, covering various aspects like primary energy consumption and production across different countries. It is utilized to analyze global and national energy consumption patterns, particularly in relation to fossil fuels and renewables.
<a href = https://www.eia.gov/opendata/index.php#bulk-downloads>International energy data (U.S. Energy Information Administration, EIA</a>
4. **Energy from Fossil Fuels (The Shift Dataportal)**  
   - This dataset highlights the share of fossil fuels in global energy production and consumption. It is critical for assessing the ongoing reliance on fossil fuels in the energy mix, which is important for understanding India’s dependency on coal, oil, and gas, and tracking its shift towards renewable sources.
<a href = https://www.theshiftdataportal.org/energy> Energy from fossil fuels (The Shift Dataportal)</a>
5. **Yearly Electricity Data (Ember)**  
   - Ember’s dataset provides yearly electricity data with a focus on emissions and the role of renewables in the electricity mix. This dataset is essential for understanding the role of green energy in India’s electricity generation, especially the adoption of solar and wind energy.
<a href = https://ember-climate.org/data-catalogue/yearly-electricity-data/> Yearly Electricity Data (Ember </a>
6. **European Electricity Review (Ember)**  
   - Although it primarily focuses on Europe, this dataset provides valuable insights into trends in electricity generation from renewable sources and the overall decarbonization of electricity. Its relevance to India lies in the comparison of Europe’s progress with India’s renewable energy adoption strategies.
<a href =https://ember-climate.org/insights/research/european-electricity-review-2022/ > European Electricity Review (Ember) </a>
7. **Combined Electricity (Our World in Data based on Ember’s Yearly Electricity Data and European Electricity Review)**  
   - This dataset combines electricity data from Ember’s Yearly Electricity Data and European Electricity Review to provide a global perspective on electricity generation. It is instrumental in analyzing the global trends in renewable energy adoption, which can be compared with India’s progress.
<a href = https://github.com/owid/etl/blob/master/etl/steps/data/garden/ember/2023-07-10/combined_electricity.py> Combined Electricity (Our World in Data based on Ember's Yearly Electricity Data and European Electricity Review)</a>
8. **Energy Mix (Our World in Data based on EI’s Statistical Review of World Energy)**  
   - This dataset offers insights into the energy mix across various countries, categorizing energy sources into fossil fuels, renewables, and nuclear. It provides an essential comparison tool for analyzing India’s energy mix over time, especially in the context of the renewable energy transition.
<a href = https://github.com/owid/etl/blob/master/etl/steps/data/garden/energy/2023-07-10/energy_mix.py > Energy mix (Our World in Data based on EI's Statistical review of world energy ) </a>
9. **Fossil Fuel Production (Our World in Data based on EI’s Statistical Review of World Energy & The Shift Dataportal’s Energy from Fossil Fuels)**  
   - This dataset provides information on fossil fuel production, tracking coal, oil, and natural gas production trends globally. It allows for an understanding of India’s fossil fuel production patterns and the challenge of reducing fossil fuel reliance in the energy mix.
<a href = https://github.com/owid/etl/blob/master/etl/steps/data/garden/energy/2023-07-10/fossil_fuel_production.py >Fossil fuel production (Our World in Data based on EI's Statistical review of world energy & The Shift Dataportal's Energy from fossil fuels)</a>
10. **Primary Energy Consumption (Our World in Data based on EI’s Statistical Review of World Energy & EIA’s International Energy Data)**  
    - This dataset aggregates data on primary energy consumption across different countries, combining information from the Energy Institute and the U.S. Energy Information Administration. It is crucial for analyzing the overall energy consumption patterns and the role of different energy sources, including renewables and fossil fuels, in meeting the growing demand in India.
<a href = https://github.com/owid/etl/blob/master/etl/steps/data/garden/energy/2023-07-10/primary_energy_consumption.py>Primary energy consumption (Our World in Data based on EI's Statistical review of world energy & EIA's International energy data)</a> 

These datasets collectively offer a comprehensive view of the energy transition, allowing for an in-depth analysis of how India’s energy sector has evolved from 1991 to 2022 and how fast it is progressing towards a greener energy future.


