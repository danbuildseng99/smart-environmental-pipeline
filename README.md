# Smart Environmental Data Pipeline (Mechatronics Framework)

## Project Overview
This project models an industrial climate monitoring framework engineered to safeguard temperature-sensitive electronics. It establishes an end-to-end data pipeline by pairing a simulated micro-controller network layer with a remote cloud data analytics suite to track thermal stability.

## Core Architectural Modules
1. **The Edge Layer (Arduino Core):** A simulated Arduino Uno interfaces with a digital DHT22 atmospheric module. It samples data metrics, evaluates payload packages, and formats data frames for a serial data bus.
2. **The Cloud Analytics Layer (Python Engine):** A custom Python data engineering block runs via cloud runtime to ingest raw text data streams, unpack parameters, extract critical structural statistics, and map out telemetry curves.

## Technical Skills Applied
* **Embedded Hardware Architecture:** Virtual pin layout optimization and circuit wiring loops.
* **C++ Programming:** Library dependency configuration (`DHTesp.h`), conditional event loops, and serial protocol output streams.
* **Python Data Science:** String array slicing, algorithmic calculation loops, and structural plotting logic (`matplotlib`).
* **Systems Engineering Mindset:** Designing an integrated system where hardware architecture feeds directly into software solutions.

## Live Assets & System Links
* **Interactive Circuit Simulator:** [PASTE YOUR WOKWI URL HERE]
* **Cloud Analytics Execution Script:** [PASTE YOUR GOOGLE COLAB URL HERE]

---

### Sample Hardware Stream Data (Ingested)
```text
24.0,40.0
24.0,40.0
24.0,40.0
25.5,41.2
27.8,43.5
```

### Derived Pipeline Diagnostics Output
* **Total System Data Packets Managed:** 15 Elements 
* **Calculated Baseline Temperature Mean:** 24.58°C
* **Peak Measured Thermal Disruption Spike:** 27.80°C
