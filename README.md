#  Engine Knock Detection using MATLAB

An interactive engine knock detection system developed using MATLAB, thermodynamic combustion modeling, and digital signal processing. The project simulates combustion inside a spark-ignition engine, performs frequency-domain analysis using Fast Fourier Transform (FFT), and detects engine knock through the Knock Intensity (KI) Index.

---

# Overview

Engine knock is an abnormal combustion phenomenon that can reduce engine performance and cause mechanical damage. This project models the combustion process, simulates cylinder pressure variations, and detects knock using signal processing techniques inspired by modern Engine Control Units (ECUs).

The dashboard enables users to modify engine parameters and instantly visualize the effect on combustion characteristics and knock detection.

---

# Features

- Interactive Engine Knock Detection Dashboard
- First Law Thermodynamic Pressure Model
- Wiebe Heat Release Function
- Cylinder Pressure Simulation
- FFT-Based Knock Detection
- Knock Intensity (KI) Calculation
- Acoustic Resonance Analysis using Bessel Equation
- Real-Time Engine Parameter Tuning

---

# Technologies Used

- MATLAB
- MATLAB Live Script
- HTML5
- CSS3
- JavaScript
- Chart.js

---

# Mathematical Concepts

- First Law of Thermodynamics
- Isentropic Compression
- Isentropic Expansion
- Wiebe Heat Release Function
- Fast Fourier Transform (FFT)
- Acoustic Wave Equation
- Bessel Functions
- Signal Processing

---

# Dashboard Features

The interactive dashboard allows users to modify:

- Bore
- Stroke
- Compression Ratio
- Engine RPM
- Knock Amplitude

and visualize:

- Cylinder Pressure
- FFT Spectrum
- Knock Ring Signal
- Knock Intensity Ratio
- Knock Detection Status

---

# Project Workflow

```
Input Engine Parameters
            │
            ▼
Cylinder Pressure Simulation
            │
            ▼
Wiebe Heat Release Model
            │
            ▼
FFT Signal Analysis
            │
            ▼
Knock Intensity (KI) Calculation
            │
            ▼
Knock Detection Decision
```

---

# Repository Structure

```
Engine-Knock-Detection/
│
├── index.html
├── Engine_Knock_Detection_MATLAB.zip
├── README.md
└── images/
```

---

# Dashboard Preview

The interactive dashboard provides real-time visualization of engine combustion characteristics and knock detection results.

<img width="282" height="390" alt="Dashboard" src="https://github.com/user-attachments/assets/a58a9e7a-a282-41d2-a7fd-c7be6f45ad03" />

---

# Cylinder Pressure Trace

The cylinder pressure trace is generated using the First Law of Thermodynamics together with the Wiebe Heat Release Model. It represents pressure variation throughout the complete 720° engine cycle.

<img width="1618" height="325" alt="Cylinder Pressure" src="https://github.com/user-attachments/assets/7abdf201-ff37-40a8-a6e9-0bdfef04bfb3" />

---

# FFT Spectrum

Fast Fourier Transform (FFT) is used to identify the dominant knock frequency from the combustion pressure signal. A significant peak near the resonant frequency indicates engine knock.

<img width="813" height="275" alt="FFT Spectrum" src="https://github.com/user-attachments/assets/2718d14d-be8e-4b73-92e7-573403980476" />

---

# Knock Ring Signal

The knock ring signal represents the damped pressure oscillations produced after abnormal combustion. It is modeled as a decaying sinusoidal wave.

<img width="797" height="291" alt="Knock Ring Signal" src="https://github.com/user-attachments/assets/9ec23884-be84-4f85-8c91-ae6886d30933" />

---

# Knock Detection Sensitivity

The Knock Intensity (KI) Ratio is compared against a predefined threshold to determine whether knock is present under different operating conditions.

<img width="1598" height="245" alt="Knock Detection Sensitivity" src="https://github.com/user-attachments/assets/da19bb8b-c019-454b-b9a8-67147cc33342" />

---

# Output

The dashboard computes and displays:

- Peak Cylinder Pressure
- Knock Frequency
- Knock Intensity Ratio
- Peak FFT Frequency
- Signal-to-Noise Ratio (SNR)
- Final Knock Detection Decision

<img width="263" height="413" alt="Output" src="https://github.com/user-attachments/assets/2e8605e1-80ef-4f66-b481-e5758eb56bee" />

---

# Applications

- Engine Combustion Analysis
- Knock Detection Research
- Mechanical Engineering Education
- MATLAB Signal Processing Demonstration
- ECU Algorithm Visualization
- Automotive Engineering Projects

---

# Future Improvements

- Integration with Real Engine Sensor Data
- Simulink-Based Engine Model
- Machine Learning-Based Knock Classification
- Real-Time Embedded ECU Interface
- Real-Time Data Acquisition
- Hardware-in-the-Loop (HIL) Testing

---

# Author

**Sudhishna Ravichandran**

B.Tech Mechanical Engineering

Indian Institute of Technology Indore
