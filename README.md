🌱 Automatic Plant Irrigation System Using Arduino Uno

📌 Project Overview

The Automatic Plant Irrigation System is an Arduino Uno-based smart irrigation project designed to automatically water plants according to the moisture level of the soil.

A soil moisture sensor continuously monitors the moisture content of the soil. When the soil becomes dry, the Arduino activates a water pump through a relay module. Once sufficient moisture is detected, the pump automatically turns OFF.

This system helps reduce water wastage and provides plants with water when required.

---

🎯 Objectives

- 🌱 Automatically detect soil moisture.
- 💧 Provide water when the soil becomes dry.
- ⚡ Control the water pump automatically using a relay.
- 💦 Reduce unnecessary water consumption.
- 🤖 Minimize manual effort in plant irrigation.
- 🌍 Demonstrate a simple IoT/embedded-system application for smart agriculture.

---

🛠️ Components Used
Arduino Uno
Soil Moisture Sensor
5V Relay Module
DC Water Pump
16×2 I2C LCD Display
Buzzer
DHT11 Sensor
Jumper Wires
Breadboard
Water Supply


⚙️ Working Principle

1. The soil moisture sensor measures the moisture level of the soil.
2. The sensor sends an analog value to Arduino Uno through A0.
3. Arduino compares the sensor value with a predefined threshold.
4. If the soil is dry, Arduino activates the relay.
5. The relay switches ON the water pump.
6. Water is supplied to the plant.
7. When the soil reaches the required moisture level, Arduino switches OFF the relay.
8. The LCD can display the moisture/status information.

🔄 Basic Flow

Soil Moisture Sensor
        ↓
    Arduino Uno
        ↓
   Check Moisture
     ↙       ↘
   Dry       Wet
    ↓          ↓
Relay ON     Relay OFF
    ↓          ↓
Pump ON      Pump OFF
    ↓
Water Plant

---

💻 Software

- Arduino IDE
- Embedded C / Arduino C++
- Required libraries may include:
  - "Wire.h"
  - "LiquidCrystal_I2C.h"
  - "DHT11"
---

🚀 Future Improvements

The project can be further improved by adding:

- 📱 Mobile application for remote monitoring
- 📡 Wi-Fi/IoT connectivity using ESP32
- ☁️ Cloud-based data monitoring
- 🌦️ Weather-based irrigation
- 📊 Real-time moisture graphs
- 🔋 Solar-powered operation
- 🌾 Multiple-zone irrigation
- 🤖 AI-based irrigation scheduling

---

🌍 Applications

- Home gardens
- Agricultural fields
- Greenhouses
- Nurseries
- Terrace gardens
- Smart farming system

⭐ Conclusion

The Automatic Plant Irrigation System provides a simple and efficient method of watering plants based on actual soil moisture conditions. By combining a soil moisture sensor, Arduino Uno, relay module, and water pump, the system automates the irrigation process while helping reduce water wastage and manual effort.
