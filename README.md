# LabVIEW-Motor-Speed-Monitoring-DAQ
# LabVIEW AC Motor Speed Monitoring & DAQ System

## 📌 About the Project
This repository contains a LabVIEW Virtual Instrument (VI) designed to simulate, monitor, and log the rotational speed (RPM) of an AC motor. Developed with industrial automation and testing in mind, the project features a complete control panel for reference value input, real-time disturbance simulation, and an automated safety protection system. 

This project demonstrates practical skills in Data Acquisition (DAQ), signal conditioning, and building HMI (Human-Machine Interfaces) for hardware testing.

## ⚙️ Core Features
* **Real-Time Monitoring:** Visualizes the motor's RPM using gauge meters and real-time amplitude-time waveform charts.
* **Disturbance Simulation:** Integrates a manual load/disturbance slider and a random noise generator to simulate real-world operating conditions and test system robustness.
* **Automated Warning & Safety System:** * Compares the measured speed against the reference value.
  * Triggers visual LED warnings if the speed deviates by ±2%.
  * Implements an automatic safety cutoff (Protection) that halts the process if the motor exceeds the critical threshold of 3000 RPM.
* **Data Logging:** Utilizes the "Write To Measurement File" function to continuously log signal data for post-processing and analysis.
* **Hardware Integration:** Configured with a DAQ Assistant block for seamless integration with National Instruments (NI) data acquisition hardware.

## 🛠️ Tech Stack & Concepts
* **Environment:** NI LabVIEW
* **Concepts:** Data Acquisition (DAQ), Hardware-in-the-Loop (HIL) concepts, Signal Routing, Error Handling, System Safety Thresholds.

## 📁 Repository Structure
* `Motor_Monitoring.vi` - The main LabVIEW Virtual Instrument containing both the Front Panel (UI) and the Block Diagram logic.
