# CIS600--Assignment-3
CIS600 Internet of Things: Application Development_Spring 2025- Assignment 3
# 🌐 IoT Environmental Monitoring System (CIS600 Assignment 3)

This project simulates an IoT environmental station that collects data from virtual sensors and sends it to the cloud using the MQTT protocol via ThingSpeak.

---

## 📡 What It Does

- Simulates **3 virtual sensors**:
  - Temperature (°C): -50 to 50
  - Humidity (%): 0 to 100
  - CO2 (ppm): 300 to 2000
- Publishes data to **ThingSpeak** every 15 seconds
- Uses the **MQTT protocol** for lightweight communication to ThingSpeak dashboards

---

## 🧰 Tech Stack

- 🐍 Python 3.12+
- 📦 [paho-mqtt](https://pypi.org/project/paho-mqtt/)
- ☁️ [ThingSpeak IoT Cloud](https://thingspeak.com/)
- 💻 Terminal / Command-line

---

## 🚀 How to Run

1. Clone this repo:
    ```bash
    git clone https://github.com/YOUR_USERNAME/IoT-Assignment-3.git
    cd IoT-Assignment-3
    ```

2. Install dependencies:
    ```bash
    pip install paho-mqtt
    ```

3. Run the script:
    ```bash
    python sensor_station.py
    ```

Make sure to replace the `MQTT_USERNAME`, `CHANNEL_ID`, and `CLIENT_ID` with your own ThingSpeak MQTT credentials.

---

## 📸 Screenshots

![Terminal Output](screenshots/terminal_output.png)  
![ThingSpeak Graphs](screenshots/thingspeak_graph.png)

---

## 🔗 ThingSpeak Channel

> [Click here to view live data on ThingSpeak](https://thingspeak.com/channels/2889190)

---

## 🧠 Reflection

See the full reflection in the report or below 👇
