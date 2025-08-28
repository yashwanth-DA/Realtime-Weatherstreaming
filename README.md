# 🌦️ Azure Weather Streaming Project  

A real-time streaming pipeline that collects, processes, and visualizes weather data for a city, using Azure services.  

---

## 🔍 Overview  
- **Goal**: Capture and analyze City’s weather conditions (temperature, humidity, UV index) along with 3-day forecasts.  
- **Source**: [WeatherAPI.com](https://www.weatherapi.com/) (JSON API).  
- **Tech Stack**: Azure Databricks, Azure Event Hubs, Microsoft Fabric (Eventstream + KQL Database), and Power BI.  

---

## 🏗️ Architecture  
1. **Databricks** → Fetches weather data via API and streams it as JSON into Event Hubs.  
2. **Event Hubs** → Acts as the event ingestion layer for real-time data.  
3. **Microsoft Fabric** → Eventstream ingests data and writes it into a KQL database table.  
4. **Power BI** → Provides live dashboards showing current weather, historical trends and forecasts.
5. **Data Activator** → To send real time alerts using KQL Query set Alert mechanism.
   
![architecture](https://github.com/user-attachments/assets/705867c5-6edd-4c40-8f8b-442807a9c34c)



---

##  Eventsteam Set Up

![eventstream](https://github.com/user-attachments/assets/bf24b7bf-332e-4265-b929-bcd7c6438b42)

![eventhousestreamtable](https://github.com/user-attachments/assets/841d542a-287c-4a40-9ddc-8b15c8b83467)

##  Real time Alerts 

![alert query ](https://github.com/user-attachments/assets/efb5da0d-5dac-4828-8add-75a05b09793c)

![alert set up](https://github.com/user-attachments/assets/ee0eae31-0753-4680-98f9-4e13fee97a26)










