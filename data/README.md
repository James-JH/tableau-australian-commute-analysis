# Australian Commuting & Transport Data

## Overview
This folder contains the datasets used to analyse commuting behaviour and transport usage patterns across Australia. The focus is on commuting distance, public transport trends, and road traffic across regions.

## Data Sources
- **Australian Bureau of Statistics (ABS)**
  - Median distance travelled to work by area  
  - Yearly public transport usage (2011, 2016, 2021)  
- **Data Victoria – Department of Transport and Planning**
  - Monthly public transport usage by mode  
  - Road traffic usage by region in Victoria  

## Data Structure
Each dataset is provided in CSV format, with fields relevant to the analysis, including:
- Region / area names  
- Year or month of data collection  
- Transport mode (train, bus, tram, ferry, etc.)  
- Median distance, usage counts, or traffic volume  

## Data Preparation
Before visualisation:
- Filtered unnecessary rows and columns to focus on relevant metrics  
- Standardised field names and categories across datasets  
- Used median values for commuting distance to reduce outlier influence  
- Aggregated monthly and yearly counts where necessary to align datasets  

## Usage
These datasets were used to:
- Compare commuting distances across regions  
- Analyse yearly and seasonal trends in public transport usage  
- Examine traffic volume concentration in metropolitan areas  

## Notes
- Data is aggregated; route-level or travel-time details are not included  
- Remote and hybrid work trends post-2021 are not captured  
- Road traffic analysis is limited to Victoria
