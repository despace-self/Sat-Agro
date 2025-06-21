# Sat-Agro
Satellite-Powered Environmental Data Pipeline for Agriculture 
Here’s a clean and professional `README.md` template for your GitHub repository:

---

# Satellite-Powered Environmental Data Pipeline for Agriculture (v0.0)

This repository contains the **initial version** of a research-oriented data pipeline that integrates publicly available environmental datasets from spaceborne and terrestrial sources to support **precision agriculture and climate-aware decision making**.

---

## Overview

This project fetches, processes, and displays environmental variables critical for agriculture, using **open APIs and remote sensing data** from:

* 🛰 **NASA Earthdata (SMAP, MODIS, GPM, etc.)** – Soil moisture, land surface temperature, vegetation indices, and more
* **Google Earth Engine** – Vegetation health metrics, historical climate records
* **OpenWeatherMap API** – Real-time weather observations (temperature, humidity, wind, etc.)
* **Open-Meteo API** – Forecast data and radiation estimates

---

## Functionality

* Retrieve **real-time and forecasted data** using GPS coordinates or bounding boxes
* Extract **soil moisture values** from SMAP `.h5` granules with spatial nearest-neighbor mapping
* Access **weather codes, precipitation, wind, solar radiation, cloud cover**
* Query **MODIS vegetation indices (NDVI, EVI)** through Google Earth Engine
* Modular structure designed to support:

  * Daily batch pulls
  * Real-time insights
  * Integration with ML-based crop monitoring models *(future plan)*

---

## 🔍 Use Cases (Research Phase)

* Precision agriculture analysis
* Environmental modeling
* Crop planning, irrigation optimization
* Drought monitoring
* Climate-smart farming studies

---

## Status

**This is Version 0.0** — the initial research phase.

> The pipeline is under active development and will be expanded with:

* Data visualization modules
* Model training and analysis tools
* Mobile/backend integration support

---

## Structure (Will Evolve)

```
.
├── nasa_smap_soil_moisture.py
├── modis_ndvi_fetcher.py
├── openmeteo_forecast.py
├── openweathermap_current.py
├── earthengine_init.py
├── utils/
└── notebooks/
```

---

## 🔑 Prerequisites

* NASA Earthdata account [Register here](https://urs.earthdata.nasa.gov/)
* Google Earth Engine access [Request here](https://earthengine.google.com/)
* API keys for OpenWeatherMap

---

## 🙌 Contributions

Feedback, issues, and pull requests are welcome!
This is an open research pipeline, and collaboration is encouraged.

---

## 📜 License

MIT License 

---

Let me know if you'd like a `requirements.txt` or starter `.ipynb` file included too!
