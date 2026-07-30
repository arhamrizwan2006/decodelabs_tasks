# 🏠 DecodeLabs IoT Internship Projects

> Four cutting-edge embedded systems solutions from my IoT internship at **DecodeLabs** (Jul–Aug 2026)

![Badge](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![Badge](https://img.shields.io/badge/Internship-DecodeLabs-blue?style=for-the-badge)
![Badge](https://img.shields.io/badge/IoT-Embedded%20Systems-orange?style=for-the-badge)
![Badge](https://img.shields.io/badge/Arduino-ESP32-inactive?style=for-the-badge)

---

## 📋 Projects at a Glance

| # | Project | Tech Stack | Status |
|---|---------|-----------|--------|
| 1️⃣ | **Environmental Monitor System** | DHT11, I2C LCD, Arduino Uno | ✅ Complete |
| 2️⃣ | **Automated Irrigation Controller** | Soil Sensor, Relay, Buzzer | ✅ Complete |
| 3️⃣ | **Cloud-Connected Security Node** | ESP32, HC-SR04, MQTT | ✅ Complete |
| 4️⃣ | **Smart Home Safety System** | PIR, MQ-2 Gas Sensor | ✅ Complete |

---

## 🎯 Project Breakdown

### 1️⃣ Environmental Monitor System
**Real-time temperature & humidity monitoring at your fingertips**

```
DHT11 Sensor → Arduino Uno → I2C LCD Display
     ↓
Live readings updated every 2 seconds
```

- 📊 Live temperature and humidity display
- 🔄 Real-time sensor updates
- 📦 Complete wiring diagrams included
- 📝 Troubleshooting guide for common issues

**Folder:** `Week-1-Environmental-Monitor-System/`

---

### 2️⃣ Automated Irrigation Controller
**Smart watering system that learns your garden**

```
Soil Moisture Sensor → Arduino Uno → Relay Control
           ↓
   Buzzer Alert + LCD Status
```

- 💧 Soil moisture threshold-based watering
- 🔔 Buzzer alerts when water level is low
- 📱 I2C LCD interface for real-time status
- 🌱 Perfect for automated plant care
- 🛠️ Troubleshooting & calibration guide

**Folder:** `Week-2-Automated-Irrigation-Controller/`

---

### 3️⃣ Cloud-Connected Security Node
**Distance sensing meets cloud intelligence**

```
HC-SR04 (Distance) → ESP32 → Adafruit IO (MQTT)
           ↓
Real-time data visualization in the cloud
```

- 📡 ESP32 microcontroller with WiFi
- 📏 HC-SR04 ultrasonic sensor for distance measurement
- ☁️ MQTT protocol streaming to Adafruit IO
- 📊 Live graphs and historical data tracking
- 🔐 Secure credential management (secrets.h)

**Folder:** `Week-3-ESP32-Distance-Sensor-MQTT/`

---

### 4️⃣ Smart Home Safety System
**Motion detection + gas safety = peace of mind**

```
PIR Sensor (Motion) → Arduino → Safety Logic
       ↓
MQ-2 (Gas Detector) → Cut Power if Hazardous
```

- 🚨 PIR motion detection with interrupt-driven logic
- 💨 MQ-2 gas sensor for real-time air quality
- ⚡ Automatic power cut-off when gas detected
- 🎥 Demo video included
- 📸 Setup & fault-state photographs

**Folder:** `Week-4-Smart-Home-Safety-System/`

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td><strong>Microcontrollers</strong></td>
    <td>Arduino Uno, ESP32</td>
  </tr>
  <tr>
    <td><strong>Sensors</strong></td>
    <td>DHT11, Soil Moisture, HC-SR04, PIR, MQ-2</td>
  </tr>
  <tr>
    <td><strong>Communication</strong></td>
    <td>I2C, MQTT, WiFi</td>
  </tr>
  <tr>
    <td><strong>IDE & Tools</strong></td>
    <td>Arduino IDE, Adafruit IO</td>
  </tr>
  <tr>
    <td><strong>Languages</strong></td>
    <td>Embedded C, Arduino Sketch</td>
  </tr>
</table>

---

## 📁 Repository Structure

```
decodelabs_tasks/
│
├── Week-1-Environmental-Monitor-System/
│   ├── code/
│   │   └── environmental_monitor_system.ino
│   ├── docs/
│   │   └── wiring_connections.md
│   ├── images/
│   │   ├── lcd_readings.jpeg
│   │   └── setup_photo.jpeg
│   └── README.md
│
├── Week-2-Automated-Irrigation-Controller/
│   ├── code/
│   │   └── automated_irrigation_controller.ino
│   ├── docs/
│   │   ├── wiring_connections.md
│   │   └── troubleshooting.md
│   ├── media/
│   └── README.md
│
├── Week-3-ESP32-Distance-Sensor-MQTT/
│   ├── code/
│   │   ├── distance_sensor_mqtt.ino
│   │   └── secrets.h.example
│   ├── docs/
│   │   ├── wiring_connections.md
│   │   └── troubleshooting.md
│   ├── images/
│   │   ├── adafruit_graph.jpeg
│   │   └── setup_photo.jpeg
│   └── README.md
│
├── Week-4-Smart-Home-Safety-System/
│   ├── code/
│   │   └── safety_system.ino
│   ├── docs/
│   │   ├── wiring_connections.md
│   │   └── troubleshooting.md
│   ├── images/
│   │   ├── demo-video.mp4
│   │   ├── setup-normal-status.jpg
│   │   └── fault-locked-status.jpg
│   └── README.md
│
└── README.md (this file)
```

---

## 🚀 Quick Start

### Prerequisites
- Arduino IDE installed
- USB cable for programming (Micro-USB for ESP32, Standard for Arduino Uno)
- Basic soldering skills (optional for sensor connections)

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/arhamrizwan2006/decodelabs_tasks.git
   cd decodelabs_tasks
   ```

2. **Pick a project folder**
   ```bash
   cd Week-1-Environmental-Monitor-System
   ```

3. **Read the documentation**
   - Check `docs/wiring_connections.md` for hardware setup
   - Check `docs/troubleshooting.md` for common issues

4. **Upload the code**
   - Open `.ino` file in Arduino IDE
   - Select your board and COM port
   - Click Upload

5. **Verify & Test**
   - Open Serial Monitor (9600 baud) to debug
   - Check LCD/sensor output

---

## 💡 Key Learnings

✅ **Sensor Integration** — Working with multiple sensor protocols (DHT11, ultrasonic, PIR, gas sensors)  
✅ **Interrupt-Driven Logic** — Real-time response to events without polling  
✅ **Cloud Connectivity** — MQTT for IoT data streaming and visualization  
✅ **Safety & Automation** — Designing fail-safe systems for home automation  
✅ **Debugging Embedded Systems** — Serial debugging, wiring validation, sensor calibration  

---

## 🔗 Links & Resources

- 📚 [Arduino Official Documentation](https://docs.arduino.cc/)
- 🌐 [Adafruit IO Dashboard](https://io.adafruit.com/)
- 📖 [MQTT Protocol Guide](https://mqtt.org/)
- 🛠️ [ESP32 Development](https://www.espressif.com/)

---

## 📧 Questions?

Each project folder includes comprehensive documentation. If you get stuck:
1. Check the **troubleshooting.md** file
2. Review the **wiring_connections.md** diagram
3. Enable serial debugging in the code

---

**Internship:** DecodeLabs IoT Track | **Duration:** Jul–Aug 2026 | **Status:** ✅ Complete

*Building the future of IoT, one project at a time.* 🚀
