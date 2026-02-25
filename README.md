# 🚗 ABS Wheel Speed Sensor Signal Processing
![Python](https://img.shields.io/badge/Python-3.13-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Project Overview
This project simulates an automotive wheel speed sensor signal with realistic road vibration and electrical noise. A Butterworth low-pass filter is applied to remove high-frequency disturbances. FFT analysis is performed to identify dominant frequency components and justify filter cutoff selection. A deceleration-based logic is implemented to detect potential ABS activation conditions.

---

## 🔧 Features
- Realistic wheel speed signal simulation
- Road vibration noise modeling (5 Hz component)
- Electrical Gaussian noise modeling
- 3rd Order Butterworth Low-pass filtering
- FFT-based frequency spectrum analysis
- ABS braking detection using deceleration threshold

---

## 🛠 Tools & Technologies
- Python
- NumPy
- SciPy
- Matplotlib

---

## 📊 Engineering Concepts Used
- Signal Processing (Time & Frequency Domain)
- Butterworth Filter Design
- Frequency Spectrum Analysis (FFT)
- Vehicle Dynamics
- ABS Control Logic

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:
   pip install numpy scipy matplotlib
3. Run the script:
   python abs_signal_processing.py

---

## 📈 Output
- Time-domain noisy vs filtered signal comparison
- Frequency spectrum analysis plot
- ABS activation detection message in terminal

---

## 🎯 Author
Automotive Data & Signal Processing Enthusiast

---

## Output Results
![Wheel Deceleration Profile](images/deceleration.png)
https://github.com/Lucky-3663/Automotive-ABS-Signal-Processing/blob/main/deceleration.png?raw=true

---

## 🧠 Analysis
The Graph represents the wheel deceleration profile during ABS activation.
It shows how braking force varies with time to prevent wheel lock-up.
The smooth deceleration curve indicates controlled braking, which improves vehicle stability and reduces stopping distance.

---

## ⚖️ ABS vs Normal Braking
![ABS Comparison](images/comparison.png)
https://github.com/Lucky-3663/Automotive-ABS-Signal-Processing/blob/main/comparison.png?raw=true
