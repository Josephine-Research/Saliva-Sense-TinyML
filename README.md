# Saliva Sense: Non-Invasive Glucose Monitoring 🧬

Saliva Sense is an innovative, non-invasive health-tech solution designed to monitor glucose levels using saliva samples instead of traditional blood-based methods. This project leverages **TinyML (Machine Learning on the Edge)** and **Electrochemical Sensing** to provide real-time, accurate analytics.

## 🚀 Key Features
* **Non-Invasive:** Uses Screen Printed Electrodes (SPE) to detect glucose in saliva.
* **TinyML Powered:** Runs optimized regression models on ESP32 for real-time prediction.
* **Low Power:** Designed for portable, battery-operated healthcare monitoring.
* **High Precision:** Uses 16-bit ADS1115 ADC for ultra-accurate signal processing.

## 🛠️ Hardware Stack
* **Microcontroller:** ESP32 Dev Module
* **ADC:** ADS1115 (16-bit External ADC)
* **Electrodes:** ZP HyperValue Carbon Screen Printed Electrodes (SPE)
* **Power:** 3.7V Li-Po Battery with TP4056 Charging Module

## 📊 Methodology
The system captures electrochemical signals from the saliva sample through the SPE. These analog signals are converted to digital by the ADS1115 and processed by a TinyML model deployed on the ESP32 to predict glucose concentration.



## 📂 Repository Structure
* Code : Arduino/C++ source code for ESP32.
* Model: TinyML model files and training scripts.
* Diagrams: Circuit schematics and connection guides.
---
*Developed by Josephine | Aiming for a future in Biomedical Innovation.*
