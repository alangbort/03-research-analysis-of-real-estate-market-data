# Research analysis of real estate market data

## Objective
Conduct exploratory data analysis to establish the parameters that affect the price of properties

## Description
We had data from the Yandex Real Estate service - an archive of advertisements for apartments for sale in St. Petersburg and neighboring settlements for several years. We needed to learn how to determine the market value of real estate objects. This would allow to track down anomalies and fraudulent activity in the future. 

Two types of data are available for each apartment for sale. The first is entered by the user, the second is obtained automatically on the basis of cartographic data. 

## Data
The following data on track listens in the Yandex.Music service were available:
- **airports_nearest** — distance to the nearest airport (m)
- **balcony** — number of balconies
- **ceiling_height** — ceiling height (m)
- **cityCenters_nearest** — distance to the city center (m)
- **days_exposition** — how many days the ad has been posted (from publication to withdrawal)
- **first_day_exposition** — publication date
- **floor** — floor
- **floors_total** — total number of floors in the building
- **is_apartment** — apartment *(boolean type)*
- **kitchen_area** — kitchen area in square meters (m²)
- **last_price** — price at the time of withdrawal from publication
- **living_area** — living space in square meters (m²)
- **locality_name** — city / town name
- **open_plan** — open plan of the real estate object *(boolean type)*
- **parks_around3000** — number of parks within a 3 km radius
- **parks_nearest** — distance to the nearest park (m)
- **ponds_around3000** — number of ponds within a 3 km radius
- **ponds_nearest** — distance to the nearest pond (m)
- **rooms** — number of rooms
- **studio** — studio apartment *(boolean type)*
- **total_area** — total floor area in square meters (m²)
- **total_images** — number of photos of the apartment in the advertisement

## Technology Stack
Python, Pandas, Matplotlib, Numpy
