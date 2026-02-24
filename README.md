# Earth System Analysis
## Overview
Designed and implemented Python-based data processing pipelines to analyze large-scale time-series datasets related to climate and solar activity. Developed modular scripts for data ingestion, cleaning, transformation, and visualization, enabling reproducible analysis workflows. Applied algorithmic techniques such as Fast Fourier Transform (FFT), harmonic decomposition, and windowed signal analysis to extract meaningful patterns from raw data. Focused on code maintainability, performance, and clarity while translating domain-specific requirements into scalable analytical solutions.

## Features
- Saturation water vapor density modeling and absolute/relative humidity analysis from atmospheric sensor data
- Planetary Boundary Layer (PBL) characterization using statistical methods including correlation and covariance analysis
- Harmonic decomposition of long-term precipitation records to identify seasonal and cyclic patterns
- El Niño Southern Oscillation (ENSO) analysis across multiple Pacific weather stations with geospatial visualization
- Atmospheric CO₂ trend analysis with time-series modeling and anomaly detection
- Sunspot cycle analysis using Short-Time Fourier Transform (STFT) to detect solar flux periodicity
- Tidal aliasing investigation via FFT on sea level height data to identify sampling artifacts

## Tech Stack
- **Language:** Python
- **Frameworks / Libraries:** NumPy, Matplotlib, SciPy (FFT, signal processing), Cartopy (geospatial mapping), dateutil
- **Tools:** Jupyter Notebook, CSV/NetCDF data formats, NOAA sea level and solar flux datasets
