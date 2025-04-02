# Interactive Pharmacy Recommendation Dashboard

## Project Overview
This project involves an interactive ArcGIS dashboard for the city of Cornwall, Ontario. The dashboard is designed to assist municipal public health authorities in identifying a candidate neighborhood for funding to support the opening of a new pharmacy.

## Purpose
The dashboard integrates multiple datasets, including census data, the Ontario Marginalization Index, and pharmacy locations, to provide a data-driven recommendation for a new pharmacy location. The analysis considers various demographic and socio-economic factors to ensure the recommendation meets the needs of the local population.

## Geographic Scales
- **Municipal Boundary**: Highlights the boundaries of Cornwall, Ontario.
- **Forward Sortation Area (FSA)**: Represents the first three digits of a postal code and highlights regional divisions within Cornwall.
- **Dissemination Area (DA)**: Represents smaller geographic units composed of adjacent dissemination blocks, providing a more granular level of analysis.

## Data Sources & Variables
### Ontario Marginalization Index (ON-Marg):
The ON-Marg aggregates multiple demographic factors into four dimensions:
- **Households and Dwellings**: Measures types and density of residential accommodations.
- **Material Resources**: Assesses access to basic material needs.
- **Age and Labour Force**: Evaluates the dependency ratio, senior population percentage, and labor force participation.
- **Racialized and Newcomer Populations**: Examines the percentage of recent immigrants and racialized individuals.

#### Weighted ON-Marg Scores (Comparison between Cornwall and Ontario):
- **Material Resources**
  - Global (Ontario): -0.0348
  - Local (Cornwall): 0.9639
- **Age & Labour Force**
  - Global (Ontario): -0.1405
  - Local (Cornwall): 0.6287

### Statistics Canada Census Data:
The following census variables are included:
- **Total Population by Age Group**
- **Population Aged 65 and Older**
- **Total Census Families**
- **Population of Married Couples with Children**
- **Low-Income Status (Ages 16-64)**
- **Population with No Knowledge of English or French**
- **Non-Canadian Citizens**

### Ministry of Health - Pharmacy Locations:
- Extracted pharmacy point locations from the Ministry of Health Service Provider Location File.
- Pharmacies are mapped to visualize accessibility and gaps in service coverage.

## Pharmacy Location Recommendation
### Dissemination Area 35010254 - Northern Cornwall
This dissemination area has a high proportion of senior residents (~5:11 ratio) and a high age and labor marginalization score (247-556). Seniors typically require more medical care, yet there are no pharmacies within walking distance of this area. This lack of accessibility poses a challenge for seniors who may not have access to reliable transportation. Based on the demographic analysis and accessibility factors, this DA is recommended for the establishment of a new pharmacy.

## References
- **Ontario Marginalization Index Dataset**
  - Matheson FI, Moloney G, van Ingen T. (2021). St. Michael’s Hospital & Public Health Ontario.
- **Statistics Canada Boundary Shapefiles**
  - Statistics Canada (2021). Census Boundary Files.
- **Municipal Boundary - Lower Tier Shapefiles**
  - Land Information Ontario (n.d.). GeoHub.
- **Ministry of Health - Health Service Providers Dataset**
  - Ministry of Health (2021). GeoHub.
- **Statistics Canada Census Data**
  - Statistics Canada (2021). Census of Canada Data Tables.

## Usage
This dashboard is publicly accessible and allows users to explore demographic, economic, and health-related data for Cornwall. The interactive features enable users to toggle different data layers, view choropleth maps, and understand the geographic distribution of key variables influencing pharmacy site selection for funding.
