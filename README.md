# Zuber_Rides

You are working as an analyst for Zuber, a new ride-sharing company that is launching in Chicago. Your task is to find patterns in the available data. You want to understand rider preferences and the impact of external factors on rides.

## Working with a database, you will analyze competitor data and test a hypothesis about the impact of weather on ride frequency - File .txt 
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

### Passo 1. Escreva um código para analisar os dados sobre o clima em Chicago em novembro de 2017 no site:
https://practicum-content.s3.us-west-1.amazonaws.com/data-analyst-eng/moved_chicago_weather_2017.html
### Passo 2. Análise Exploratória de Dados
### Passo 3. Teste a hipótese de que a duração das corridas do Loop até ao Aeroporto Internacional O'Hare muda em sábados chuvosos.
### Passo 4. Análise exploratória de dados (Python)

## In addition to the data retrieved in the previous tasks, you received a second file. You now have these two CSVs:
Dataframe 1) project_sql_result_01.csv. It contains the following data:
• company_name: The name of the taxi company
• trips_amount: The number of trips for each taxi company from November 15 to 16, 2017.

Dataframe 2) project_sql_result_04.csv. It contains the following data:
• dropoff_location_name: Chicago neighborhoods where trips ended
• average_trips: The average number of trips that ended in each neighborhood in November 2017.

### Step 5. Testing hypotheses (Python): "The average ride length from the Loop to O'Hare International Airport changes on rainy Saturdays."
Dataframe 3) project_sql_result_07.csv 
• start_ts — date and time the ride started
• weather_conditions — weather conditions at the time the ride started
• duration_seconds — trip duration in seconds
