# SKY130A CMOS Inverter Design and Physical Verification

## 📌 Project Overview

This project demonstrates the design and verification of a CMOS inverter using the **SKY130A open-source Process Design Kit (PDK)**. It covers schematic design, circuit simulation, layout design, Design Rule Check (DRC), and Layout Versus Schematic (LVS) verification using open-source VLSI design tools.

## 🎯 Objectives

- Design a CMOS inverter using PMOS and NMOS transistors.
- Create and inspect the transistor-level schematic.
- Simulate the inverter's input and output voltage waveforms.
- Design the physical layout using the SKY130A technology.
- Perform DRC to check layout design-rule compliance.
- Perform LVS to verify that the extracted layout circuit matches the schematic.

## 🛠️ Tools and Technologies

- **Operating System:** Ubuntu Linux
- **Virtualization:** Oracle VirtualBox
- **PDK:** SKY130A
- **Schematic Editor:** Xschem
- **Layout Editor:** Magic VLSI
- **Circuit Simulation:** Ngspice
- **Physical Verification:** Magic DRC and Netgen LVS

## ⚙️ Project Workflow

1. **Schematic Design:** Create the CMOS inverter schematic using PMOS and NMOS transistors.
2. **Circuit Simulation:** Apply an input signal and observe the inverted output waveform using Ngspice.
3. **Layout Design:** Create the physical layout according to the SKY130A technology rules.
4. **Design Rule Check (DRC):** Check the layout for design-rule violations.
5. **Layout Versus Schematic (LVS):** Compare the layout-extracted circuit with the schematic netlist.

## 📸 Project Results

The following screenshots document the design and verification process.

| Screenshot | Description |
|---|---|
| `inverter_schematic.png` | CMOS inverter transistor-level schematic |
| `layout.png` | Physical layout of the CMOS inverter |
| `waveform.png` | Simulated input and output voltage waveforms |
| `drc_result.png` | Design Rule Check result |
| `lvs_result.png` | Layout Versus Schematic verification result |

*Note: The screenshot filenames above are descriptive examples. Update them to match the actual filenames in this repository.*

## ✅ Verification Summary

- **Schematic:** CMOS inverter design documented.
- **Simulation:** Input and output waveforms captured.
- **DRC:** The reported result was zero design-rule errors.
- **LVS:** The report indicated that the netlists matched uniquely.

## 📚 Key Learnings

- CMOS inverter operation and transistor-level design.
- Schematic capture and circuit simulation.
- Physical layout creation using an open-source VLSI toolchain.
- Design-rule verification and layout-to-schematic comparison.
- Using open-source tools for basic custom IC design.

## 🚀 Future Improvements

- Refine the layout and transistor dimensions.
- Analyze propagation delay, rise time, and fall time.
- Evaluate power consumption and switching behavior.
- Explore post-layout simulation and parasitic effects.

## 👩‍💻 Author

**Sai Ramya Gandham**

Electronics and Communication Engineering (ECE)

Interested in VLSI Design, Digital Design, and Semiconductor Technologies.

## 📄 License

This project is intended for educational and learning purposes. Refer to the respective tool and PDK licenses for their usage terms.
