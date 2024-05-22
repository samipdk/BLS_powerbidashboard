## Power BI BLS Dashboard

## Problem Statement
The project aimed to create an interactive and informative dashboard to analyze key economic indicators—Consumer Price Index (CPI), Producer Price Index (PPI), and national employment data—using data extracted from the Bureau of Labor Statistics (BLS) API. This involved fetching the data programmatically, transforming it for analysis, and visualizing it to identify trends and patterns over time.

## Steps Followed

## Data Extraction:

Utilized the BLS API to fetch data on CPI, PPI, and national employment.
Used Python and the requests library to programmatically access the API and retrieve the relevant datasets.

## Data Transformation:

Loaded the fetched data into Pandas DataFrames for processing and manipulation.
Cleaned and transformed the data to ensure consistency and accuracy for analysis.

## Data Loading:

Exported the processed data into a format compatible with Power BI.
Imported the data into Power BI for visualization and dashboard creation.

## Dashboard Creation:

Designed a home page to provide an overview and navigation:

![Homepage](https://github.com/samipdk/BLS_powerbidashboard/assets/137905918/435284c4-a5ce-4c33-b5b6-6085818d2d3b)

Created an "Employment Price Statistics" page with the following elements:
Matrix Tables:
Displayed data for CPI, PPI, and national employment for the previous year, current year, and growth percentage.
Line Charts:
One chart showing trends in CPI and PPI over the past twelve months.

Another chart illustrating national employment data over the same period:

![dashboard](https://github.com/samipdk/BLS_powerbidashboard/assets/137905918/cb219d24-3d8c-42d1-a668-9e730ac0e4ea)

## Solutions Provided: 

- Data Accessibility: Provided a streamlined process to access and retrieve economic data from the BLS API, making it easier for users to obtain and work with this information.
- Data Visualization: Created a comprehensive and interactive Power BI dashboard that visually represents key economic indicators, facilitating better understanding and analysis.
- Trend Analysis: Enabled users to track and compare CPI, PPI, and national employment trends over time, aiding in economic research and decision-making.
- User-Friendly Interface: Designed a user-friendly interface with clear and concise visualizations, making the data accessible and interpretable even for users without a technical background.
- This project showcases the integration of data extraction, transformation, and visualization to create an effective tool for economic analysis.



