# Democracy index - Data package

This data package contains the data that powers the chart ["Democracy index"](https://ourworldindata.org/grapher/democracy-index-eiu?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 06, 2024.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Democracy score
Extent to which citizens can choose their political leaders in free and fair elections, enjoy civil liberties, prefer democracy over other political systems, can and do participate in politics, and have a functioning government that acts on their behalf. It ranges from 0 to 10 (most democratic).
Last updated: May 22, 2024  
Next update: May 2025  
Date range: 2006–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Economist Intelligence Unit (2006-2023) – processed by Our World in Data

#### Full citation
Economist Intelligence Unit (2006-2023) – processed by Our World in Data. “Democracy score” [dataset]. Economist Intelligence Unit, “Democracy Index 2021: The China challenge”; Economist Intelligence Unit, “Democracy Index 2022: Frontline democracy and the battle for Ukraine”; Economist Intelligence Unit, “Democracy Index 2023: Age of Conflict”; Gapminder, “Democracy Index v4” [original data].
Source: Economist Intelligence Unit (2006-2023) – processed by Our World In Data

### What you should know about this data

### Sources

#### Economist Intelligence Unit – Democracy Index 2021: The China challenge
Retrieved on: 2024-05-22  
Retrieved from: https://www.economistgroup.com/group-news/economist-intelligence/democracy-index-2021-less-than-half-the-world-lives-in-a-democracy  

#### Economist Intelligence Unit – Democracy Index 2022: Frontline democracy and the battle for Ukraine
Retrieved on: 2024-05-22  
Retrieved from: https://www.eiu.com/n/campaigns/democracy-index-2022  

#### Economist Intelligence Unit – Democracy Index 2023: Age of Conflict
Retrieved on: 2024-05-22  
Retrieved from: https://www.economistgroup.com/group-news/economist-intelligence/eius-2023-democracy-index-conflict-and-polarisation-drive-a-new-low-for  

#### Gapminder – Democracy Index
Retrieved on: 2024-05-22  
Retrieved from: https://www.gapminder.org/data/documentation/democracy-index/  

#### Notes on our processing step for this indicator
Values for continents have been obtained by averaging the values of the countries in the continent.


    