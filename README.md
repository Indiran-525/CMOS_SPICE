# CMOS SPICE Simulations

This repository contains **SPICE simulations of NMOS, PMOS, and CMOS inverters** using various device models.  
It is designed to help understand **device behavior, inverter characteristics, and robustness analysis** under different operating conditions.

---

## Workflow

1. **NMOS Device Study**
   - Structure and operation
   - Threshold voltage, channel voltage
   - Operation regions: Cutoff, Linear, Saturation

2. **Introduction to SPICE Simulations**
   - Purpose and advantages of SPICE
   - Understanding the SPICE deck: parameters, netlist, and models

3. **NMOS Characterization**
   - IV characteristics: `Id` vs `Vds`
   - Velocity saturation effects in short-channel MOSFETs: `Id` vs `Vgs`

4. **CMOS Inverter Study**
   - Structure and operation
   - Voltage Transfer Characteristics (VTC) from load curves
   - SPICE simulation of CMOS inverter VTC

5. **CMOS Inverter Robustness Analysis**
   - Switching threshold variations
   - Noise margin evaluation: `VIL`, `VIH`, `VOL`, `VOH`
   - Effect of PMOS sizing on switching threshold
   - Impact of supply voltage and device variations on VTC

---

## Simulation Conditions

All simulations were performed under **typical-typical (TT) corner conditions** at **27°C**.

---

## Repository Highlights

- SPICE decks for NMOS, PMOS, and CMOS inverters
- Parameterized netlists for easy experimentation
- Model-based device simulations
- Analysis of inverter robustness and noise margins
