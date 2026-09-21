# Mobility Project 3: BMS State of Charge (SOC) Estimation

This repository contains research and implementation code for estimating the **State of Charge (SOC)** of Lithium-Ion batteries used in Electric Vehicles (EVs), as part of the **Daegu RISE Project - Innovation Academy (대구 RISE사업 혁신 아카데미)**.

---

## 📌 Project Overview

Accurate Battery State of Charge (SOC) estimation is critical for modern Battery Management Systems (BMS) in Electric Vehicles to prevent overcharging/overdischarging, optimize energy management, and ensure operational safety. 

Because internal battery states cannot be directly measured using physical sensors, SOC must be inferred from measurable electrical signals like voltage, current, and temperature. This project focuses on evaluating Coulomb Counting (Ah-counting) alongside model-based SOC estimation techniques to compensate for sensor noise, initial SOC errors, and battery non-linearities.

---

## 📑 Contents & Key Sections

The project documentation (`혁신아카데미 BMS SOC 추정 보고서.pdf`) covers the following topics:

1. **SOC Estimation Overview (SOC 추정 개요)**
   - **Necessity of SOC Estimation:** Overview of Coulomb Counting vs. Model-based estimation techniques.
   - **Equivalent Circuit Models (ECM):** Parameter comparison between 1RC vs. 3RC equivalent circuit models.

2. **Battery Modeling & Parameter Extraction**
   - Parameter determination based on Open Circuit Voltage (OCV) curves and dynamic load responses.

3. **SOC Estimation Algorithms**
   - **Coulomb Counting (Ah-Counting):** Performance and cumulative error limitations under sensor noise.
   - **Model-Based Observer / Filter Design:** Implementation of state estimation to compensate for modeling uncertainties and non-linear dynamics.

4. **Performance Evaluation & Results**
   - Estimation accuracy, convergence performance, and error analysis under dynamic operating conditions.

---

## 🛠️ Requirements & Installation

- Python 3.8+ (or MATLAB / Simulink depending on your simulation setup)
- Common dependencies:
  ```bash
  pip install numpy scipy matplotlib pandas

---

## 📜 Report Reference

- **Document:** `혁신아카데미 BMS SOC 추정 보고서.pdf`
- **Program:** Daegu RISE Project - Innovation Academy (대구 RISE사업 혁신 아카데미)
- **Date:** December 16, 2025

---

## 👤 Author

- 👤 Authors: 강현우, 구교웅, 김소영, 박세리, Agaliu Enrik, 황진영
- **Repository Owner:** [EnrikAgalliu](https://github.com/EnrikAgalliu)
