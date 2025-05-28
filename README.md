# 🔋 Multiphysics Simulation and State Estimation of a Prismatic Li-Ion Battery Pack

This project focuses on the design, simulation, and analysis of a 6S1P prismatic lithium-ion battery pack. The work integrates mechanical, thermal, and electrical modeling to assess the structural integrity, thermal efficiency, and battery health metrics like SOC (State of Charge) and SOH (State of Health). The ultimate goal is to create a validated digital twin that supports safer and more efficient battery system designs.

---

## 📌 Project Objectives

- Design and simulate a prismatic Li-ion battery pack and custom PLA holder.
- Validate mechanical performance using static, modal, and drop test simulations.
- Analyze thermal behavior under realistic operating conditions using SolidWorks and ANSYS Fluent.
- Estimate SOC using three different filtering techniques (Coulomb Counting, Kalman Filter, Adaptive Kalman Filter).
- Track SOH degradation and temperature rise using resistance and thermal feedback.
- Develop a simulation-driven foundation for future digital twin integration.

---

## 🛠 Tools & Technologies

- **SolidWorks** – 3D modeling, structural and modal simulations
- **ANSYS Fluent** – CFD-based thermal simulations
- **MATLAB/Simulink** – SOC & SOH estimation models

---

## ⚙️ Methodology

### 🔩 Mechanical Analysis
- Designed the 6S1P battery pack and holder in SolidWorks.
- Performed static load simulations with 1500N to test structural durability.
- Conducted modal analysis to extract natural frequencies (first mode at ~93.5 Hz).
- Simulated drop impact from 1 meter to evaluate structural robustness.

### 🌡️ Thermal Simulation
- Used SolidWorks for transient heat flow with natural convection.
- Developed a detailed Fluent model with airflow domains and boundary conditions.
- Applied realistic heat generation profiles and monitored peak temperatures.

### 🔌 Electrical Estimation
- Implemented three SOC estimation algorithms:
  - Coulomb Counting
  - Kalman Filter
  - Adaptive Kalman Filter
- Modeled SOH via internal resistance growth.
- Simulated and validated battery behavior under variable load conditions.

---

## 📊 Key Results

- **Mechanical Integrity**: Structure remained elastic under load with a minimum FOS > 3.
- **Thermal Analysis**: Peak temperature ~330 K; airflow optimization recommended for hotspots near terminals.
- **State Estimation**: Adaptive Kalman Filter yielded the most accurate SOC predictions; SOH tracked effectively over 4000 cycles.

---

## 🔍 Future Work

- Explore machine learning models for nonlinear SOC/SOH prediction.
- Test alternative battery chemistries and high-current cooling strategies.
- Integrate mechanical, thermal, and electrical models into a unified real-time digital twin.

---

