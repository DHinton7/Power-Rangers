# Power-Rangers
Cohort 21 Capstone Project for the Certificate of Data Science at Georgetown University School of Continuing Studies.



## Team Power Rangers

Carla Coulson - @couksck <carlacoulson@comcast.net>  
Roman Villoria - @romanvilloria <romanchest@gmail.com>  
Dominique Hinton - @Dhinton7 <dominiquealexandriahinton7@gmail.com>  

## Abstract

The energy sector is a key contributor to climate change, accounting for more than two-thirds of global greenhouse gas (GHG) emissions. And, the energy sector is directly impacted by climate change through increases in usage/consumption of commodities such as water and electricity.

Buildings are significant energy consumers. In 2019, end-use energy consumption by residential and commercial sectors was equal to 28% of total energy consumption in the United States. Our proposed project will predict monthly energy usage based on past energy usage and weather data for a variety of building types, all greater than 50,000 SF in size, located within DC. Given current climate change concerns, having an accurate estimate of future energy usage in large buildings will help the District, and utility providers, effectively conduct strategic planning required to optimize resources, better estimate building operating costs, and set energy and GHG emissions reduction standards and renewable energy goals.


## Project Overview


**Project Purpose:** To provide building owners in DC information  
**Research Question:**  
* The best performing buildings are those most recently constructed and with higher ES ratings.  
* Buildings with improving ES ratings over time exhibit reduced energy and water consumption and GHG emissions.  
* Water usage is correlated to overall energy usage.  
* Increases in energy and water usage are associated with extreme weather evidenced by climate change.  
* Changes in energy usage due to the COVID pandemic have resulted in decreases in energy and water usage.  

**Hypothesis:**  
* Can we predict DC large commercial buildings’ energy usage based on their historical electricity and natural gas consumption and weather patterns? 

![Project Architecture]()

## Summary of Data Science Pipeline


**Ingestion:** Download data from website and upload into database  
**Wrangling:** Clean data and put into tables within database
**Machine Learning:** Use different regression models to find one that best fits the data

## Data Sources 

- [OpenDataDC](https://opendata.dc.gov/datasets/building-energy-benchmarks)

- [NOAA](https://www.ncdc.noaa.gov/)

## File Organization


**data:** Contains the csv files that to go into the database  
**ingestion_wrangling:** Contains the code for instantiating the tables with in the database  
**EDA:** Contains the data exploration  
**machine_learning:** Contains different machine learning models for global model and models by building type  
**storage:** Contains the code for connecting to the database  
**Dont_Look:** Contains dirty code  


### Link to Presentation: [Energy Benchmarks in DC](https://www2.slideshare.net/DominiqueHinton/energy-benchmarking-in-dc)




