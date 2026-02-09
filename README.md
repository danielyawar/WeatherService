This project is a Java-based REST API built with Spring Boot that provides a clean, frontend-ready weather overview for a given city. Instead of returning raw third-party API data, the service restructures and formats the response into logical sections suitable for UI consumption.

The API fetches live weather data from an external provider, extracts relevant fields such as temperature, conditions, humidity, and wind speed, and returns them in a structured JSON format. It also generates simple outfit recommendations based on current weather conditions (e.g., suggesting warm clothing in cold temperatures).

Example Endpoint

GET /api/weather/{city}


Example Response Features

Location summary (city and country)

Current temperature and “feels like” temperature

Weather conditions and description

Atmospheric details (humidity, wind)

Clothing recommendations based on weather logic

Example Output:

<img width="1463" height="692" alt="image" src="https://github.com/user-attachments/assets/1c2d510d-cff6-4a21-b895-bf9cf0ea9375" />


<img width="452" height="833" alt="image" src="https://github.com/user-attachments/assets/c44b619b-e806-4321-8326-7b97817cebaa" />
