# GATES-REALISATION-FROM-NMOS-PMOS-CMOS
# Logic Gate Realization using PMOS, NMOS, and CMOS in LTspice 🔌

This repository contains the design and simulation of **NOT**, **OR**, **AND**, **NAND**, and **NOR** logic gates using **PMOS**, **NMOS**, and **CMOS** transistors in **LTspice XVII**.  
It demonstrates how basic and universal logic gates can be implemented at the transistor level.

## Overview 📘

The project consists of:

1. **NOT Gate (Inverter)**
   - Realized using CMOS (1 PMOS + 1 NMOS)
   - Demonstrates voltage inversion with minimal static power consumption

2. **OR Gate**
   - Implemented using PMOS pull-up and NMOS pull-down network
   - Verified logical OR truth table through simulation

3. **AND Gate**
   - Implemented using NMOS series pull-down and PMOS parallel pull-up configuration
   - Verified AND truth table through simulation

4. **NAND Gate**
   - CMOS implementation using series NMOS in pull-down and parallel PMOS in pull-up
   - Demonstrated as a universal logic gate

5. **NOR Gate**
   - CMOS implementation using parallel NMOS in pull-down and series PMOS in pull-up
   - Verified as another universal logic gate

## Tools Used 🛠️

- **LTspice XVII** – Analog/digital circuit simulation
- **PMOS/NMOS Theory** – Digital electronics fundamentals
- **SPICE Models** – For transistor behavior simulation

## Key Highlights ✅

- Realized fundamental and universal logic gates using MOSFET transistor-level design
- Verified gate functionality via transient simulations
- Analyzed voltage transfer characteristics and switching behavior

## How to Run 🚀

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/ltspice-logic-gates.git
