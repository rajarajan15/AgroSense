#  Crop Prediction using IoT

##  Project Overview

This project is an **IoT-based Crop Prediction System** that integrates real-time sensor data with intelligent algorithms to recommend the most suitable crops for farming. It is designed to assist farmers in making data-driven decisions using environmental inputs collected from IoT devices deployed in the field.

Each IoT device is paired with a dedicated application that captures sensor data such as temperature, humidity, soil moisture, and pH. The application then communicates with a backend prediction model to determine the ideal crop for current conditions.

---

##  Technologies Used

###  Frontend / Applications
- React – For web dashboard (optional)

###  Backend & Machine Learning
- Python (with Pandas, NumPy, Scikit-learn)
- Flask – For serving the ML model API
- Trained ML models (Knn, pkl)

###  IoT & Sensors
- Arduino / ESP32 microcontrollers
- DHT11 / DHT22 – Temperature & Humidity sensors
- Soil Moisture Sensor
- pH Sensor
- NPK Sensor
- Wi-Fi Module for data transmission

###  Cloud / Storage
- ThingSpeak

---

##  Features

-  Real-time crop prediction based on:
  - Soil Moisture
  - Temperature
  - Humidity
  - pH
-  Application interface for farmers to view predictions
-  Sensor-based automation and decision support
-  Continuous data updates and learning
-  Trained ML model with high accuracy
-  Analytics dashboard for historical data 

---

##  How it Works

1. **Sensor Deployment**: Place IoT sensors in the field to continuously collect environmental parameters.
2. **Data Collection**: Sensor data is transmitted via ESP32 to a backend system in real time.
3. **Model Processing**: The backend ML model processes the incoming data and returns crop recommendations.
4. **User Interface**: Recommendations are shown to farmers through the mobile app interface.

---

##  Results

- Achieved over **90% accuracy** in crop prediction using Random Forest model.
- Enabled **real-time monitoring** and **instant decision making**.
- Increased farmer awareness of ideal environmental conditions for different crops.

---

##  Future Improvements

- Add fertilizer and water recommendation system
- Implement weather forecast integration
- Enable multilingual support in the app
- Add alert system for unfavorable conditions

---
