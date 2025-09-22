# CMOS SPICE Simulations ⚡

This repository contains **SPICE simulations of NMOS, PMOS, and CMOS inverters** using various device models.  
It is designed to help students, researchers, and enthusiasts understand **MOSFET device behavior, CMOS inverter characteristics, and circuit robustness** under different operating conditions.  

The simulations explore both **DC and transient behaviors**, considering **parameter variations, device sizing, and supply voltage effects**. 🔍

---

## Workflow 🛠️

### 1. NMOS Device Study 🟦
- Understand the **structure and operation** of NMOS transistors.
- Study **threshold voltage**, channel voltage distribution, and **operation regions**: Cutoff, Linear (Triode), and Saturation.
- Observe how **drain current (Id)** varies with **drain-source voltage (Vds)** and **gate-source voltage (Vgs)**.

### 2. Introduction to SPICE Simulations 📊
- Learn the **importance of SPICE** in circuit design and verification.
- Get familiar with **SPICE deck components**:
  - **Parameters**: process constants that are necessary (body effect coefficient, threshold voltage, etc.) ⚙️
  - **Netlist**: textual representation of the circuit and wiring 📝
  - **Models**: definitions describing the behavior of devices / formulas 📐

### 3. NMOS Characterization 🔬
- Simulate **Id-Vds characteristics** for different gate voltages - [DAY1](https://github.com/Indiran-525/CMOS_SPICE/tree/main/DAY1).
- Study **velocity saturation effects** in short-channel MOSFETs using Id-Vgs curves - [DAY2](https://github.com/Indiran-525/CMOS_SPICE/tree/main/DAY2).


### 4. CMOS Inverter Study 🟩
- Understand the **structure and operation** of CMOS inverters.
- Derive **Voltage Transfer Characteristics (VTC)** from load curves.
- Simulate **transient response** to input transitions using SPICE.

### 5. CMOS Inverter Robustness Analysis 🛡️
- Analyze **switching threshold variations** due to device sizing- [DAY3](https://github.com/Indiran-525/CMOS_SPICE/tree/main/DAY3).
- Evaluate **noise margins**: `VIL`, `VIH`, `VOL`, `VOH` 🔊 - [DAY4](https://github.com/Indiran-525/CMOS_SPICE/tree/main/DAY4)
- Study the effect of **PMOS sizing on inverter switching threshold**.
- Investigate how **supply voltage variation and device parameter variations** affect the VTC- [DAY5](https://github.com/Indiran-525/CMOS_SPICE/tree/main/DAY5).

---

## Simulation Conditions 🌡️

- All simulations are performed under **typical-typical (TT) corner conditions**.
- Ambient temperature for simulations: **27°C** 🌞
- Parameters are set to study **device behavior and inverter robustness** realistically.

---

This repository is a reflection of my **hands-on learning experience** for understanding CMOS circuit design and MOSFET behavior through **NGSPICE** (CMOS SPICE SIMULATION - VSD) ⚡
