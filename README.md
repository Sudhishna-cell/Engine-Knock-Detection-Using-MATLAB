# Engine Knock Detection using MATLAB

## Overview

This project simulates engine knock detection using thermodynamic combustion modelling and digital signal processing techniques inspired by modern Engine Control Units (ECUs).

The model predicts cylinder pressure, generates knock signals, performs FFT analysis, computes Knock Intensity Index (KI), and determines whether knock is present.

---

## Features

- First Law Thermodynamic Pressure Model
- Wiebe Heat Release Function
- Cylinder Pressure Simulation
- FFT-Based Knock Detection
- Knock Intensity Index (KI)
- Interactive Dashboard
- Engine Parameter Tuning
- Acoustic Resonance (Bessel Equation)

---

## Technologies

- MATLAB
- MATLAB Live Script
- HTML
- JavaScript
- Chart.js

---

## Mathematical Concepts

- First Law of Thermodynamics
- Isentropic Compression
- Isentropic Expansion
- Wiebe Function
- Fast Fourier Transform (FFT)
- Acoustic Wave Equation
- Bessel Functions
- Signal Processing

---

## Interactive Dashboard

The dashboard allows users to change

- Bore
- Stroke
- Compression Ratio
- RPM
- Knock Amplitude

and instantly visualizes

- Cylinder Pressure
- FFT Spectrum
- Knock Ring Signal
- Knock Intensity Ratio

---

## Repository Structure

```
Engine-Knock-Detection/
│
├── engine_knock_detection_portfolio.html
├── full_pipeline.mlx.zip
├── README.md
```

---

## Results

The dashboard predicts

- Peak Cylinder Pressure
- Knock Frequency
- Knock Intensity Ratio
- FFT Peak
- Signal-to-Noise Ratio

and classifies combustion as

- Knock Detected
- No Knock

##Images

 <img width="282" height="390" alt="Screenshot 2026-06-28 175118" src="https://github.com/user-attachments/assets/a58a9e7a-a282-41d2-a7fd-c7be6f45ad03" />

 ## Cylinder Pressure Trace

The cylinder pressure trace is generated using the First Law of Thermodynamics combined with the Wiebe heat release model, showing pressure variation over the complete 720° engine cycle.

 <img width="1618" height="325" alt="Screenshot 2026-06-28 175134" src="https://github.com/user-attachments/assets/7abdf201-ff37-40a8-a6e9-0bdfef04bfb3" />
 <img width="813" height="275" alt="Screenshot 2026-06-28 175141" src="https://github.com/user-attachments/assets/2718d14d-be8e-4b73-92e7-573403980476" />
 <img width="797" height="291" alt="Screenshot 2026-06-28 175154" src="https://github.com/user-attachments/assets/9ec23884-be84-4f85-8c91-ae6886d30933" />
 <img width="1598" height="245" alt="Screenshot 2026-06-28 175206" src="https://github.com/user-attachments/assets/da19bb8b-c019-454b-b9a8-67147cc33342" />
 <img width="263" height="413" alt="Screenshot 2026-06-28 175219" src="https://github.com/user-attachments/assets/2e8605e1-80ef-4f66-b481-e5758eb56bee" />







---

## Future Improvements

- Real Engine Data Integration
- Simulink Model
- Machine Learning Based Knock Classification
- Real-Time ECU Interface

---

## Author

Sudhishna Ravichandran

B.Tech Mechanical Engineering

Indian Institute of Technology Indore
