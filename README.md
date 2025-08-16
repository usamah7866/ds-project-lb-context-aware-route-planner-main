# Location-Based Context-Aware Route Planner
# Overview
This project proposes a context-aware route planner that integrates air quality data with traditional traffic and distance metrics to recommend healthier and more sustainable travel routes. Instead of simply minimizing travel time, the system balances travel efficiency with environmental health by reducing exposure to air pollutants such as PM2.5 and PM10.

# The system leverages:

Graph-based algorithms: Dijkstra’s Algorithm & Bellman-Ford Algorithm

Geospatial analysis with street network data (NYC)

Air quality monitoring using PM2.5 & PM10 sensor data

Linear Weighting Method to combine distance, pollution levels, and traffic

This project demonstrates how urban mobility can be made healthier by recommending routes that optimize both travel time and pollution exposure.

# Key Features

📍 Location-based routing using NYC street network data

🧮 Shortest path algorithms (Dijkstra, Bellman-Ford)

🌫️ Air quality integration with PM2.5 & PM10 sensor readings

⚖️ Linear weighting scheme to balance multiple factors

🚖 Mobility-aware routing using NYC taxi data for traffic density

📊 Spatial & statistical analysis for route evaluation

🧪 Evaluation with stratified sampling for efficiency vs. accuracy

# Datasets Used

NYCPilot1PM.csv → Air quality sensor data (PM2.5, PM10, timestamps, locations)

nyc1.csv → NYC taxi mobility dataset (pickup/drop-off, fares, trip distance, passengers)

nycpolygon.geojson → NYC street network (road segments, geometries, attributes)

# Methodology

The project is divided into five main tasks:

Data Exploration & Initial Route Planning

Geospatial preprocessing (using OSMNX, spatial joins)

Exploratory Data Analysis (EDA) of air quality data

Refined Route Planning with Air Quality

Development of linear weighting scheme (PM2.5 + traffic + distance)

Prototype integration with taxi data

Evaluation with Stratified Sampling

Route recommendations using sampled datasets

Trajectory similarity metrics for accuracy vs. efficiency

Performance Expansion

Extended evaluation using NYC taxi data

Comparison of pollution-aware vs. distance-only routes

PM2.5 dose reduction analysis

Reporting & Discussion

Documenting findings, trade-offs, and potential improvements

# Future Directions

✅ Incorporate real-time traffic congestion & elevation into routing

✅ Develop a user-friendly interface (mobile/web app)

✅ Extend to other cities with diverse datasets

✅ Introduce advanced health metrics (e.g., PM2.5 dose reduction rate)

✅ Community-driven IoT air quality sensor integration

# Results

Pollution-aware routes significantly reduce PM2.5 exposure compared to shortest-distance routes.

Stratified sampling maintains accuracy while improving computational efficiency.

Demonstrates potential for health-conscious urban route planning in smart cities.
