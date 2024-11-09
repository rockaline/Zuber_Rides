# Zuber_Rides

You are working as an analyst for Zuber, a new ride-sharing company that is launching in Chicago. Your task is to find patterns in the available data. You want to understand rider preferences and the impact of external factors on rides.

## Part 1) Working with a database, it was analysed competitor data and tested a hypothesis about the impact of weather on ride frequency (See File "Part 1) SQL") 
Data description
A database with information about taxi rides in Chicago:
Table 1) neighborhoods table: data about the city's neighborhoods
• name: neighborhood name
• neighborhood_id: neighborhood code

Table 2) cabs table: data about taxis
• cab_id: vehicle code
• vehicle_id: vehicle's technical identification
• company_name: company that owns the vehicle

Table 3) trips table: data about rides
• trip_id: trip code
• cab_id: code of the vehicle that operates the ride
• start_ts: date and time of the start of the ride (time rounded to the nearest hour)
• end_ts: date and time of the end of the ride (time rounded to the nearest hour)
• duration_seconds: duration of the ride in seconds
• distance_miles: distance traveled in miles
• pickup_location_id: pickup location code
• dropoff_location_id: dropoff location code

Table 4) weather_records table: data about the weather
• record_id: weather record code
• ts: record date and time (time rounded to the nearest hour)
• temperature: temperature when the recording was made
• description: brief description of the weather conditions, e.g. "light rain" or "scattered clouds"

### Step 1. Write code to analyze Chicago weather data for November 2017 from the website:
https://practicum-content.s3.us-west-1.amazonaws.com/data-analyst-eng/moved_chicago_weather_2017.html
### Step 2. Exploratory Data Analysis
### Step 3. Test the hypothesis that the duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.
### Step 4. Exploratory Data Analysis (Python)

## Part 2) In addition to the data retrieved in the previous section, it was carried out an analysis in Python
Dataframe 1) project_sql_result_01.csv. It contains the following data:
• company_name: The name of the taxi company
• trips_amount: The number of trips for each taxi company from November 15 to 16, 2017.

Dataframe 2) project_sql_result_04.csv. It contains the following data:
• dropoff_location_name: Chicago neighborhoods where trips ended
• average_trips: The average number of trips that ended in each neighborhood in November 2017.

### Step 5. Exploratory Data Analysis
### Step 6. Testing hypotheses (Python): "The average ride length from the Loop to O'Hare International Airport changes on rainy Saturdays."
Dataframe 3) project_sql_result_07.csv 
• start_ts — date and time the ride started
• weather_conditions — weather conditions at the time the ride started
• duration_seconds — trip duration in seconds
