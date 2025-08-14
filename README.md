# LT_Spice

**Some Cool LTSpice Simulations … Fun with Waveforms**

---

##  Overview

This repository contains a collection of **LTSpice (.asc)** circuit simulation files, log outputs, and waveform data showcasing classic analog and digital circuits. Dive in to explore:

- Basic op-amp circuits (inverting, non­inverting, differentiators)
- 555 timer circuits (astable, monostable, Schmitt trigger configurations)
- Multivibrator circuits (astable, monostable, bistable setups)
- DC motor three-phase semi-controlled speed controller
- Suggestions of waveform analysis and simulation outputs

---

##  What's Inside

| File(s) / Folder | Description |
|------------------|-------------|
| `Q1.asc`, `Q1.log` | Simulation (and log) for Circuit Q1 |
| `Q2 Inverting.asc`, `Q2 NON_INVERTING.asc`, corresponding `.log` files | Inverting and non-inverting op-amp circuits |
| `Q3_Astable.asc`, `Q3_MONOSTABLE.asc`, `Q3_BISTABLE.asc` | Multivibrator (astable, monostable, bistable) circuits |
| `astable 555.asc`, `monostable 555.*`, `scmitt 555.*` | 555 timer circuit examples |
| `OPAMP_Differentiator.asc` | Op-amp configured for differentiation |
| `DC motor 3 phase semi controlled Speed Controller.asc` | Three-phase DC motor drive simulation |
| `3phase.asc`, `.op.raw` files | Three-phase waveform data |
| `report_Aman.pdf` | Summary report or documentation of the simulations |

---

##  Getting Started

1. **Prerequisites**  
   - [LTSpice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) installed.

2. **Running Simulations**  
   - Open any `.asc` file in LTSpice.
   - Press **Run** to generate waveforms.
   - Use **.op** directives or logs to inspect operating points and raw outputs.

3. **Exploration Tips**  
   - Experiment with component values (resistors, capacitors, supply voltages) to see changes in waveforms.
   - Toggle simulation parameters like `.op`, `.tran`, or `.ac` for steady-state, time-domain, or frequency-domain analysis.

---

##  Recommended Enhancements

- Add brief circuit descriptions in comments (within `.asc` files) for quick context.
- Provide snapshots of waveforms or `.raw` data visualizations in this README.
- Structure subfolders for clarity—e.g., `opamp/`, `555_timer/`, `motor_control/`, etc.
- Incorporate a `LICENSE` (e.g., MIT, BSD) so others can reuse or contribute safely.
- Include a `CONTRIBUTING.md` to guide collaborators on how to contribute or suggest improvements.

---

##  License & Contributions

- **License**: TBD (suggest adding an MIT, Apache 2.0, or similar)
- **Contributing**: Pull requests and suggestions are welcome! Please open an issue or pull request detailing your enhancements or feedback.

---

_Enjoy experimenting with LTSpice and uncovering the beauty of waveforms!_

---
