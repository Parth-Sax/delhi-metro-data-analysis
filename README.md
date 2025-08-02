# 🚇 Delhi Metro Network Optimization & Passenger Load Analysis

## 📌 Overview
This project analyzes the **Delhi Metro network** using **DMRC GTFS datasets** and passenger load data to:
- Understand the **distribution of metro lines**
- Map **station locations & routes**
- Analyze **passenger load patterns**
- Simulate **schedule optimizations** to improve service during peak hours

It combines **data visualization**, **geospatial mapping**, and **statistical analysis** to explore operational improvements for the Delhi Metro.

---

## 📂 Dataset Sources

1. **Delhi Metro GTFS Data (DMRC)** – Official Open Data Feed  
   🔗 [https://data.gov.in/catalog/general-transit-feed-specification-gtfs-delhi-metro](https://data.gov.in/catalog/general-transit-feed-specification-gtfs-delhi-metro)  
   Included Files:  
   - `agency.txt` → Metro agency details  
   - `calendar.txt` → Service schedule  
   - `routes.txt` → Metro line details  
   - `shapes.txt` → GPS coordinates of route paths  
   - `stop_times.txt` → Timings of trains at stations  
   - `stops.txt` → Station names & coordinates  
   - `trips.txt` → Individual scheduled train journeys  

2. **Delhi Metro Station Data**  
   🔗 [https://data.gov.in/resources/delhi-metro-stations](https://data.gov.in/resources/delhi-metro-stations)  

3. **Passenger Load Data (2022)**  
   *Provided as an Excel file in `/data/`* — contains passengers per km for each metro line.

---

## ✨ Features
- **Metro Line Distribution Analysis** – Pie chart showing station distribution per line.
- **Interactive Metro Map** – Folium map of all stations with GPS coordinates.
- **Distance Analysis** – Histogram of distances from first station.
- **Passenger Load Analysis** – Histograms & trends of passengers per km per line.
- **Route Frequency Mapping** – Scatter plot showing how many routes serve each stop.
- **Train Interval Analysis** – Average time gap between trains by part of day.
- **Demand-Based Trip Adjustments** – Simulation of increased/decreased trips during peak/off-peak hours.

---

## 📊 Visualizations

### 1️⃣ Metro Line Distribution
![Metro Line Distribution](images/metro_line_distribution.png)

### 2️⃣ Interactive Station Map
![Metro Station Map](images/metro_station_map.png)

### 3️⃣ Passenger Load Trends
![Passenger Load](images/passengers_load.png)

### 4️⃣ Routes Per Stop
![Routes per Stop](images/routes_per_stop.png)

### 5️⃣ Average Train Intervals
![Train Intervals](images/train_intervals.png)

### 6️⃣ Trip Adjustment Simulation
![Trip Adjustment](images/trip_adjustments.png)

*(All images are generated from the Jupyter Notebook and saved in `/images/`.)*
