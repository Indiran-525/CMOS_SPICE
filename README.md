# CMOS SPICE Simulations

This repository contains **SPICE simulations of NMOS, PMOS, and CMOS inverters** using various device models.  
It is designed to help students, researchers, and enthusiasts understand **MOSFET device behavior, CMOS inverter characteristics, and circuit robustness** under different operating conditions.

The simulations explore both **DC and transient behaviors**, considering **parameter variations, device sizing, and supply voltage effects**. 

---

## Workflow

### 1. NMOS Device Study
- Understand the **structure and operation** of NMOS transistors.
- Study **threshold voltage**, channel voltage distribution, and **operation regions**: Cutoff, Linear (Triode), and Saturation.
- Observe how **drain current (Id)** varies with **drain-source voltage (Vds)** and **gate-source voltage (Vgs)**.

### 2. Introduction to SPICE Simulations
- Learn the **importance of SPICE** in circuit design and verification.
- Get familiar with **SPICE deck components**:
  - **Parameters**: process constants that are necessary ( body effect coefficient, thershold voltage, etc).
  - **Netlist**: textual representation of the circuit and wiring.
  - **Models**: definitions describing the behavior of devices / formulas.

### 3. NMOS Characterization
- Simulate **Id-Vds characteristics** for different gate voltages.
- Study **velocity saturation effects** in short-channel MOSFETs using Id-Vgs curves.

### 4. CMOS Inverter Study
- Understand the **structure and operation** of CMOS inverters.
- Derive **Voltage Transfer Characteristics (VTC)** from load curves.
- Simulate **transient response** to input transitions using SPICE.

### 5. CMOS Inverter Robustness Analysis
- Analyze **switching threshold variations** due to device sizing.
- Evaluate **noise margins**: `VIL`, `VIH`, `VOL`, `VOH`.
- Study the effect of **PMOS sizing on inverter switching threshold**.
- Investigate how **supply voltage variation and device parameter variations** affect the VTC.

---

## Simulation Conditions

- All simulations are performed under **typical-typical (TT) corner conditions**.
- Ambient temperature for simulations: **27°C**.
- Parameters are set to study **device behavior and inverter robustness** realistically.

---

## Repository Highlights

- **Parameterized SPICE decks** for NMOS, PMOS, and CMOS inverters.
- **Device models** for realistic transistor behavior.
- **Transient and DC analyses** for voltage transfer curves, IV characteristics, and noise margins.
- **Robustness study** of CMOS inverters against device sizing and supply variations.
- **Learning-focused** repository: ideal for students, hobbyists, and researchers.

---

## Getting Started

1. Open the desired SPICE deck (`.sp` or `.cir` file) in your preferred SPICE simulator (LTspice, NGSPICE, PSpice, etc.).
2. Run **DC, AC, or transient simulations** as specified in the netlist.
3. Analyze the results for **Id-Vds, Id-Vgs, and VTC curves**.
4. Modify parameters to observe **device or inverter behavior under different conditions**.

---

This repository is a reflection of my **hands-on learning experience** for understanding CMOS circuit design and MOSFET behavior through **NGSPICE** (CMOS SPICE SIMULATION - VSD).
