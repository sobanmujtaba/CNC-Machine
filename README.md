# CNC-Based Two-Dimensional Cutter

[![University](https://img.shields.io/badge/COMSATS-University-blue)](https://www.comsats.edu.pk/)
[![Degree](https://img.shields.io/badge/BS-Electrical_Engineering-green)](https://atc.comsats.edu.pk/)

A precision Computer Numerical Control (CNC) system designed for automated two-dimensional cutting and engraving. This project focuses on minimizing production time and costs while maintaining high manufacturing quality.

## Project Overview
In modern industry, high-quality production with time and cost efficiency is vital. This project implements a microprocessor-controlled mechanical framework that translates digital designs into physical cuts with high precision.

### Key Features
- **High Precision:** Automated 2D plotting and engraving.
- **Time Efficient:** Drastically reduces manual labor in the production process.
- **Scalable Architecture:** Modular electronic system integrated onto a mechanical framework.

## System Architecture
The system is divided into three challenging aspects: Mechanical Design, Electronic Wiring, and Software Integration.

### Hardware Components 
- **Controller:** Arduino Uno
- **Expansion:** CNC Shield V3.0
- **Motor Drivers:** A4988 Stepper Drivers
- **Actuators:** Stepper Motors for X and Y axes

### Software Stack 
- **Firmware:** GRBL (High-performance G-code parser)
- **Development:** Arduino IDE
- **Design Tools:** CAD/CAM Software for G-code generation
- **Interface:** Universal Gcode Sender (Gateway)

## Getting Started
1. **Calibration:** Ensure the mechanical work-bed is leveled and belts are tensioned.
2. **Firmware:** Flash the GRBL firmware to the Arduino using the Arduino IDE.
3. **Wiring:** Connect the CNC Shield and motor drivers as per the electrical system diagram.
4. **Execution:** Upload your G-code via the Gateway software to start the cutting process.

## The Team
- **Soban Mujtaba** (FA18-BEE-011)
- **Temoor Hussain Shah** (FA18-BEE-017) 
- [cite_start]**Zia Masood** (FA18-BEE-019)

**Supervisor:** Dr. Atta Ur Rehman
