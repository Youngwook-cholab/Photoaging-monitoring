# Photoaging-monitoring

This repository contains raw and processed time-series data, along with analysis code, used for monitoring cellular photoaging via hydrogen peroxide (H₂O₂) signaling. The structure is organized by experimental condition and data type.

# Experimental Data

- **Sensor response under natural UVA**  
  Natural sunlight UVA exposure: Raw & processed time-series sensor signals.

- **Sensor response under strong UVA**  
  Artificial strong UVA exposure experiments.

- **Sensor response with superoxide dismutase treatment**  
  H₂O₂ signal variation with SOD (superoxide dismutase) antioxidant treatment.

- **Sensor response with catalase treatment**  
  Signal suppression by catalase enzyme targeting H₂O₂.

- **Sensor response in ARS measurement**  
  Antioxidant response using:
  - Vitamin C (50 μM, 5 μM, 0.5 μM)
  - Vitamin E (100 μg, 10 μg, 1 μg)
  - FBGE (1,000 ppm, 100 ppm, 10 ppm)

- **Spatiotemporal analysis of H₂O₂**  
  Time-resolved H₂O₂ diffusion and propagation monitoring.

- **High resolution monitoring**  
  x100 magnification sensor data for enhanced spatiotemporal accuracy.

# Analysis Code

- **Code for processing real-time brightness signals**  
  From video brightness to sensor-readable signal processing.

- **Code for log-normal fitting and concentration quantification**  
  Log-normal modeling and calibration for quantitative H₂O₂ analysis.

# Data Format

All `.txt` files represent either raw signal values or processed data.  
