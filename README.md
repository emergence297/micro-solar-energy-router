# 🌞 Solar Router 1.0

**Solar Router 1.0** is an Arduino-based energy routing system using an ESP32. It's designed to manage and monitor solar power generation, consumption, and routing in real-time.

---

## 🚀 Features

- 📊 Real-time monitoring of energy production and consumption
- 🌐 Wi-Fi-enabled with web server interface
- 🧠 Smart control of energy routing via dimmer
- 🕒 Accurate time sync with NTP
- 💡 OLED screen display for local feedback

---

## 🛠️ Hardware Requirements

- ESP32 board  
- OLED display (SSD1306 128x64)  
- Voltage/current sensor (e.g., INA219, SCT-013)
- Triac-based dimmer circuit (for dynamic load control)
- Wi-Fi connectivity
- Optional: External RTC for redundancy

---

## 🔌 Libraries Used

- `WiFi.h` / `WiFiClientSecure.h`
- `WebServer.h`
- `ESPAsyncWebServer.h` *(if available)*
- `NTPClient.h`
- `Adafruit_SSD1306.h`
- `ESP-Google-Sheet-Client` *(for data sync)*
- `EEPROM.h`
- `ArduinoJson.h`

---


## 🧪 To Do

- [ ] Enable push alerts for critical thresholds  
- [ ] Improve UI on the web interface  
- [ ] Add real-time charting (e.g., Chart.js)
- [ ] - 📋 Hourly data logging to Google Sheets

---


## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** License.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

**Under the following terms:**
- Attribution — You must give appropriate credit.
- NonCommercial — You may not use the material for commercial purposes.

See the [LICENSE](LICENSE) file for full details.

