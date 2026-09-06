# Yeti_SAT1
# YetiSat1 🛰️

A 21-gram suborbital satellite prototype built with an ESP32-C3 and miniature sensors.

## 🎥 Project Video

# YetiSat1 🛰️

> A 21-gram suborbital satellite prototype built with an ESP32-C3 and miniature sensors.

## 🎥 Project Video

[![YetiSat — 21g Suborbital Satellite Prototype](https://img.youtube.com/vi/v4_hDTrrimE/maxresdefault.jpg)](https://www.youtube.com/watch?v=v4_hDTrrimE)

*Watch the full build and testing process on YouTube.*

---

## 📡 About YetiSat

YetiSat is a **21-gram suborbital satellite prototype** designed to explore how much functionality can be packed into an extremely small and lightweight platform.

The project is inspired by **KalamSat** and its approach to building highly compact satellite systems using accessible, commercially available electronics.

YetiSat uses an **ESP32-C3** as its main controller along with miniature sensors for collecting environmental and motion-related data.

## 🚀 Mission Concept

YetiSat is **not designed to be placed into orbit or sent into outer space**.

Instead, it is designed as a **recoverable suborbital experimental platform** that can potentially be carried to a predetermined altitude using a suitable **drone, high-altitude platform, or rocket**, depending on the experiment and applicable safety regulations.

During a flight, YetiSat can collect sensor data such as environmental conditions and motion. After the experiment, the system can be **recovered**, allowing the recorded data to be retrieved and analyzed through a **data dashboard**.

The basic mission concept is:

**Launch → Collect Data → Recover → Download Data → Analyze**

## 🔧 Hardware

* **ESP32-C3** — Main microcontroller
* **Environmental sensors** — Temperature, humidity, and other environmental measurements
* **Motion sensor** — Motion and orientation data
* **Compact power system**
* **Lightweight custom structure**
* Miniature electronic components
   
## 🔌 Connections

| Component           | Connection      |
| ------------------- | --------------- |
| BME680              | I2C - SDA / SCL |
| BMI323              | I2C - SDA / SCL |
| Battery             | 3V3 / GND       |
| ESP32-C3 Super Mini | Main Controller |


## 📊 Data

Depending on the current hardware configuration, YetiSat can collect:

* 🌡️ Temperature
* 💧 Humidity
* 📐 Motion / orientation
* 🌍 Environmental conditions

The sensor configuration may change as the project develops.

## ⚖️ Weight

**Total prototype weight: ~21 grams**

One of the main goals of YetiSat is to minimize size and weight while retaining useful sensing and data-logging capabilities.

## 🛰️ Inspiration

YetiSat is heavily inspired by **KalamSat**, particularly the concept of creating an extremely lightweight satellite using accessible electronics.

This project is an independent implementation with its own hardware, firmware, mechanical design, and experimental approach.

## 🎯 Goals

* Explore lightweight satellite engineering
* Learn about spacecraft electronics and sensor systems
* Experiment with compact embedded systems
* Collect environmental and motion data
* Develop a recoverable suborbital experimental platform
* Analyze flight data through a dashboard
* Explore how small and lightweight a functional satellite prototype can become


## ⚠️ Disclaimer

YetiSat is an **experimental prototype, not an orbital spacecraft**.

Any future flight testing or launch would be performed only using appropriate platforms, permissions, safety procedures, and applicable regulations.

