# Capital Bike Share Demand Forecasting

- This project focuses on analyzing and forecasting the demand for bicycles using the Capital Bike Share dataset. The goal is to leverage machine learning models by predicting future demand based on factors such as time of day, day of the week, season, and weather conditions.

## Project Overview

### About Capital Bike Share

   - Capital Bike Share is a bike-sharing program based in the Washington, D.C. metropolitan area. The system allows users to rent and return bicycles throughout the city, offering different pricing options for members and casual riders.
   - for more information: (https://capitalbikeshare.com/)

### Project Goals and Scope

   - This project analyzes bike-sharing data to derive actionable insights and predict demand trends using machine learning models. Key objectives include:

- **Predictive Modeling**: Develop linear regression models to forecast bike demand and related metrics, assisting in operational planning and resource allocation.
- **Data Visualization**: Create an interactive Tableau dashboard using a representative sample of the dataset to explore trends in ride patterns, user behavior, and bike types.

## Bike Demand Dashboard

- You can view the interactive dashboard on Tableau Public here:

   [Click here to view the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/emre.sahin1866/viz/BikeDemandDashboard/Dashboard)



- **Key Performance Indicators (KPIs)**: Identify and analyze key metrics such as:
  - **Ride Duration Trends**: Measure the average ride duration per user type (Member, Casual) and bike type (Classic, E-Bike) across different months/years.
  - **Bike Type Preference**: Measure the percentage change in the distribution of rides between bike types (Classic, E-Bike) over time (yearly or quarterly)
  - **Peak Hour Utilization**: Identify the most popular usage hours for Members and Casual users, and track the change in bike usage during peak and off-peak hours.

   This project uses two key datasets:

1. **Capital Bike Share Ride Dataset (`CBS_2021-2023_Full.csv`)**:  
   Rides dataset contains detailed information about each bike ride, including:
   - **Rideable Type**: Type of bike (classic, electric, docked)
   - **Member or Casual**: Whether the rider is a member or casual
   - **Start and End Dates and Times**: `started_at` and `ended_at`
   - **Station Information**: `start_station_name`, `end_station_name`, `start_station_id`, `end_station_id`
   - **Geo Locations**: `start_lat`, `start_lng`, `end_lat`, `end_lng`
   
2. **Hourly Weather Dataset(`CBS_2021-2023_Hourly_Weather`)**:
   The weather data includes hourly information about:
   - **Humidity**: The humidity level
   - **Temperature**: The temperature at the time of the ride
   - **WMO Code**: The World Meteorological Organization code
   - **Windspeed**: The windspeed at the time of the ride

   - WMO codes in the weather data range from 00 to 99, with each code representing specific weather conditions.
   - A detailed explanation can be found at: (https://www.meteopool.org/en/encyclopedia-wmo-ww-wx-code-id2)
   

### Download Instructions:

1. **Capital Bike Share Ride Dataset (`CBS_2021-2023_Full.csv`)**:  
   Download the full ride dataset from **Google Drive**:  
   [Download Dataset from Google Drive](http://bit.ly/3Z1pzFJ)

2. **Hourly Weather Dataset(`CBS_2021-2023_Hourly_Weather`)**:
   You can download the weather dataset directly from GitHub.

### How to Use:

- Place both downloaded files in the project directory to use the analysis scripts.

## Tools and Techniques
- **Python** for data analysis and machine learning model development.
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn for data analysis and visualization, Scikit-learn for machine learning, and Folium/Plotly for mapping visualizations.
- **Tableau** for creating dashboards to review station usage and efficiency.
- **Modeling**: Experiment with regression models, time series forecasting, and other machine learning techniques to predict bike demand.

## Project Steps:
1. **Data Exploration & Cleaning**: Analyze the dataset, handle missing data, remove outliers, and engineer relevant features.
2. **Exploratory Data Analysis (EDA)**: Explore relationships between features and bike demand using statistical analysis and visualizations.
3. **Model Building**: Develop machine learning models to predict bike demand. Try different models and evaluate their performance.
4. **Visualization**: Use Tableau to visualize areas of high and low demand, and identify patterns in bike usage across different times and locations.
5. **Insights & Recommendations**: Provide actionable insights to improve operations, increase efficiency, and enhance user experience.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) file for details.