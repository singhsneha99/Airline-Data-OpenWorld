# Airline Route Data Analysis

This project performs analysis on airline route data to gain insights into global flights, airlines, airports etc.

## Datasets Used

The following open source datasets from OpenFlights were used:

- `airports.dat`: Details on airports including location, city, country etc
- `airlines.dat`: Airline names, call signs, countries etc 
- `routes.dat`: Airline routes between airports including stops, equipment

## Analysis Workflow

The process followed was:

1. Import datasets into Pandas DataFrames
2. Merge airline info into routes DataFrame 
3. Merge airport names and geography data into routes
4. Save merged DataFrame into consolidated CSV
5. Analyze data to gain insights 
   - Top destinations
   - Traffic patterns
   - Airline market share
   - Airport hierarchies etc

## Usage

The Jupyter notebook contains the data import, processing and analysis code.

The final merged `flights.csv` dataset with airport and airline information joined is also included.


## Visualization

You can find my visualizations at: https://public.tableau.com/views/AirlineData_17045828053120/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
