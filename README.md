# DC Microgrid Power Distribution Simulation

A simulation-based project demonstrating the operation of a small-scale DC microgrid using **LTspice**. The system integrates a DC source, battery storage, a PWM-controlled DC–DC converter, and multiple DC loads to study power distribution, voltage regulation, and transient response.

---

## Project Overview

This project models a DC microgrid capable of supplying multiple DC loads while maintaining a stable DC bus. The simulation analyzes system behavior during startup and steady-state operation and demonstrates power flow between the source, battery, and connected loads.

---

## Features

- 24 V DC source
- PWM-controlled DC–DC converter
- Battery energy storage
- Multiple DC resistive loads
- DC bus voltage regulation
- Startup transient analysis
- Steady-state performance evaluation

---

## Components Used

| Component | Value |
|-----------|-------|
| DC Source | 24 V |
| Battery | 12 V |
| Battery Internal Resistance | 0.1 Ω |
| MOSFET | IRLHM620 |
| Diode | 1N5819 |
| Inductor | 100 µH |
| Capacitor | 470 µF |
| Load 1 | 10 Ω |
| Load 2 | 20 Ω |
| Load 3 | 30 Ω |
| PWM Signal | PULSE(0 5 0 1u 1u 20u 40u) |

---

## Results

The following analyses were performed:

- DC bus voltage response
- Inductor current
- Battery current
- Load current distribution
- PWM gate signal
- Startup transient response

### Key Observations

- The DC bus voltage increased smoothly from startup and reached a stable steady-state value.
- The PWM switching controlled power delivery to the DC bus.
- Lower resistance loads drew higher current compared to higher resistance loads.
- The LC filter reduced output voltage ripple.
- The system demonstrated stable transient and steady-state performance.

---

## Applications

- DC Microgrids
- Renewable Energy Systems
- Battery Energy Storage Systems (BESS)
- Electric Vehicle Power Systems
- Power Electronics Education
- Smart Grid Research

---
