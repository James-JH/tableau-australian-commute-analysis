# Australian Commute Patterns & Transport Usage Dashboard

## Overview
In this project, I explore commuting behaviour and transport usage patterns across Australia, focusing on how far people travel to work, how public transport usage has changed over time, and how transport demand differs between capital cities and regional areas.

I combined national and state-level datasets to create clear, comparable insights for urban planners, policymakers, and the general public. To improve analytical clarity, I intentionally avoided map-based visualisations and instead focused on trend and comparison-driven charts.

## Key Questions
- How do commuting distances differ between capital cities and regional Australia?
- Which regions commute the furthest to their place of work?
- How has public transport usage changed between 2011 and 2021?
- What seasonal trends exist across different public transport modes?
- How does road traffic usage vary across regions in Victoria?

## Data Sources
- **Australian Bureau of Statistics (ABS)**
  - Median distance travelled to work by area
  - Yearly public transport usage (2011, 2016, 2021)
- **Data Victoria – Department of Transport and Planning**
  - Monthly public transport usage by mode
  - Traffic and road usage by region in Victoria

## Visualisations Included
- **Median commuting distance by Greater Capital City Statistical Area**
  - I used this to show how commuters in the ACT, Greater Melbourne, and Greater Brisbane generally travel further to work compared to regional areas.
- **Yearly public transport usage by mode**
  - I compared changes in train, bus, tram, taxi, and ferry usage across census years.
- **Monthly public transport usage**
  - I visualised seasonal demand patterns across metro and regional transport modes.
- **Total annual road traffic usage in Victoria**
  - I highlighted traffic concentration across metropolitan regions versus other areas.

Each visualisation was designed to prioritise trend detection, comparability, and accessibility.

## Key Insights
- I found that capital city residents generally experience longer median commute distances than those living in regional areas.
- Public transport usage shows strong growth in metro rail-based modes, particularly trains and trams.
- Transport demand exhibits clear seasonal variation across most public transport modes.
- Road traffic volume in Victoria is heavily concentrated in metropolitan regions, highlighting ongoing infrastructure pressure.

## Design Decisions
- I avoided map-based visualisations to prevent geographic size from dominating interpretation.
- I selected median commute distance instead of mean to reduce the influence of extreme outliers.
- I implemented interactive filters to allow exploration by year, region, and transport mode.
- I used consistent colour palettes and layouts to reduce cognitive load and improve readability.

## Limitations & Future Work
- Commute data is limited to median distance and does not capture full distributions or travel time.
- Public transport data is aggregated at regional and yearly levels, limiting route-level analysis.
- Remote and hybrid work trends, particularly post-2021, are not reflected in the data.
- Road traffic analysis is limited to Victoria and cannot be compared nationally.

In future iterations, I would like to:
- Incorporate travel time and congestion-based metrics
- Analyse post-pandemic transport trends (2022 onwards)
- Add sustainability and emissions indicators
- Integrate real-time or sensor-based transport data

## Tools & Technologies
- Tableau for interactive dashboard development
- Public datasets from ABS and Data Victoria
- Data cleaning and preprocessing performed prior to visualisation

## Intended Audience
- Government and transport policymakers
- Urban and infrastructure planners
- Data analytics and visualisation professionals
- Members of the public interested in Australian transport trends

## Author
James Huynh  
Dashboard created: 01/09/2024
