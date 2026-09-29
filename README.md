# 📊 Smart Environmental Data Pipeline

A practical project exploring how data flows from physical hardware into software scripts for analysis.

## 💡 The Motivation
In modern manufacturing, machines don't operate in a vacuum—they generate data that engineers use to check system health. I built this project to teach myself the fundamentals of data acquisition, linking an Arduino simulation to a Python script to see how raw readings turn into usable diagnostics.

## 🛠️ How the System Works
1. **The Hardware Layer (Wokwi):** A simulated Arduino Uno reads temperature and humidity data from a digital DHT22 sensor and formats the readings into clean text packages.
2. **The Software Layer (Google Colab):** A Python script takes that raw data stream, splits the text, calculates average temperatures, and plots the results on a simple chart.

## 🔗 Live Interactive Links
* **Interactive Circuit Simulator:** [Launch the Wokwi Simulation](https://wokwi.com/projects/475859811328167937)
* **Cloud Analytics Execution Script:** [Open the Google Colab Notebook](https://colab.research.google.com/drive/1GBcP7zYmNdFHBF1zuY5Ae53dF2K2jZ0w?usp=sharing)

## 🧠 What I Learned & Practised
* **Data Formatting**: Learned how to format raw inputs from sensors into simple strings (`Temperature,Humidity`) that other software can easily read.
* **C++ Programming**: Managed sensor library dependencies, mapped pin layouts, and controlled data printing intervals.
* **Python Data Handling**: Practised array parsing, mathematical calculation loops (like finding averages), and basic data plotting using `matplotlib`.
* **System Integration**: Experienced the logic of building an end-to-end project where the software directly depends on the hardware output.

---

### 📥 Raw Hardware Data Example
```text
24.0,40.0
24.0,40.0
25.5,41.2
27.8,43.5
```

### 📤 Python Script Output Example
* **Total Packets Read:** 15 Elements 
* **Average Temperature:** 24.58°C
* **Highest Temperature Spike:** 27.80°C
