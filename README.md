# Weather Data Warehouse for Agricultural Decision Support

An ETL pipeline prototype to provide farmers with custom reports and dashboards based on historical weather data.

![Weather Data Visualization](https://github.com/Mckisa17/Agricultural_Decision_Support/blob/main/AMPBC.png) 


## Project Overview

This project aims to build a data warehouse of historical weather data sourced from NOAA, offering a reliable platform for querying and constructing custom reports and dashboards tailored to specific farmer locations.

### Features:

1. **NOAA API Data Extraction**: Automated extraction of weather data, including daily precipitation, minimum, and maximum temperatures.
2. **Data Transformation**: Conversion of raw data into a tabular format suitable for data warehousing.
3. **Data Quality Assessment**: Ensures the integrity and reliability of the stored data.
4. **Data Warehouse Schema**: An optimized schema for storing, querying, and analyzing the weather data.
5. **Visualization**: Samples of crosstab reports and charts generated from the warehouse data.
6. **GeoJSON Support**: Location data of weather stations, including the station ID.

## Getting Started

### Prerequisites

- Python 3.x
- Pandas, Geopandas, Requests, matplotlib, re, geojson, calendar, folium

### Installation

1. Clone the repo:
   ```sh
   git clone https://github.com/YourUsername/weather-data-warehouse.git

###Legal and Ethical Considerations
1. Data Usage: Ensure you adhere to NOAA's data usage policies and any associated costs or rate limits.
2. Accuracy: Ensure data accuracy, especially when advising farmers, to avoid misleading information.
3. Privacy: Always ensure no personal or sensitive data is stored or processed without appropriate permissions.

### Future Improvements
Comprehensive error handling and logging.
Integration with other data sources for enhanced prediction capabilities.
Performance optimization for handling larger datasets.
