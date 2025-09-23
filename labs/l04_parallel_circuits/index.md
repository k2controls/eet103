---
layout: default
---

## EET103 Electrical Studies I

### [EET103](../../) - [Labs](../) - Parallel Circuits

Name \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Partner \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

---

#### Objectives

By the end of this lab, you should be able to:

* Successfully wire and verify a three-resistor parallel circuit on a breadboard.
* Interpret and follow a circuit schematic to populate a breadboard layout.
* Confirm resistor nominal values and color codes, and measure their actual resistance with a DMM.
* Accurately measure branch currents, total current, and voltage across each resistor using the DMM.
* Calculate power dissipation in each branch and explain how resistance affects power in parallel circuits.

---

#### Materials

* Digital multimeter (DMM)
* Breadboard
* Resistors: 100 Ω, 220 Ω, 470 Ω (5% tolerance)
* Breadboard power supply module (set to 5 V DC)
* Test leads
* EveryCircuit account (use license key provided in Lab 3)

> ⚠ **Safety Note:** Always confirm power supply voltage before energizing the circuit.

---

### Part 1 – Parallel Circuit Simulation

1. **Investigate Resistors in Parallel**
   Simulate a DC circuit with three resistors connected in parallel using the EveryCircuit simulator.

2. **Select Resistors**
   Use: 100 Ω, 220 Ω, and 470 Ω.

3. **Build the Circuit in EveryCircuit**

   * Use your EveryCircuit account from Lab 3.
   * Create the parallel circuit shown below.
   * Include the ground symbol.
   * Supply voltage: 5 V DC.
   * Ensure both partners use the same resistor values and positions.

   ![parallel circuit](parallel_circuits.png)

4. **Simulate Circuit Operation**

   * Press space bar to run.
   * Observe branch currents and total current.
   * Observe that the voltage across each resistor is the same.

5. **Add Ammeters**
   Place ammeters in series with each resistor to observe branch currents.

   ![parallel circuit with ammeters](parallel_with_ammeters.png)

6. **Record Simulation Results**

| Component | Value | Branch Current (Theoretical) | Branch Current (Measured) | Voltage Drop | Power Dissipation |
| --------- | ----- | ---------------------------- | ------------------------- | ------------ | ----------------- |
| R1        | 100 Ω |                              |                           |              |                   |
| R2        | 220 Ω |                              |                           |              |                   |
| R3        | 470 Ω |                              |                           |              |                   |
| **Total** |       |                              |                           |              |                   |

7. **Intro to Parallel Rules**

   * Voltage is the same across each branch.
   * Total current equals the sum of branch currents.
   * Equivalent resistance is always less than the smallest resistor.

---

### Part 2 – Parallel Circuit Construction and Measurement

1. **Inspect Resistors**

   * Record nominal values, color codes, and measured resistance.

| Component | Nominal Value | Color Code | Measured Value (Ω) |
| --------- | ------------- | ---------- | ------------------ |
| R1        | 100 Ω         |            |                    |
| R2        | 220 Ω         |            |                    |
| R3        | 470 Ω         |            |                    |

2. **Construct the Parallel Circuit**

   * Use your breadboard to build the parallel circuit from Part 1.
   * Refer to schematic and plan layout carefully.
   * Have your partner verify before energizing.

   ![breadboard with parallel resistors](breadboard_parallel.png)

3. **Energize and Measure**

   * Use the DMM to measure total current and each branch current. Remember: current is measured in series with each branch.
   * Measure voltage across each resistor to confirm all are equal.
   * Calculate power dissipation for each branch using P = V × I or P = I² × R.

4. **Record Your Results**

| Component | Value | Branch Current (Theoretical) | Branch Current (Measured) | Voltage Drop | Power Dissipation |
| --------- | ----- | ---------------------------- | ------------------------- | ------------ | ----------------- |
| R1        | 100 Ω |                              |                           |              |                   |
| R2        | 220 Ω |                              |                           |              |                   |
| R3        | 470 Ω |                              |                           |              |                   |
| **Total** |       |                              |                           |              |                   |

---

### Assessment

**Video Demonstration**
Create a video summarizing your work. Include:

* Resistor selection and schematic overview.

* Simulation results from Part 1 (share screen in Zoom).

* Breadboard build, voltage source, and current flow description.

* Measurement results from Part 2 compared to simulation and theoretical values. Show this document with values entered.

* Demonstration that total current equals the sum of branch currents.

* Power dissipation results: which branch dissipated the most power, and why?

* Challenges encountered and lessons learned.

* [Lab 4 Rubric](l04_rubric.md)

# EET103 – Lab 4 Video Checklist

**Parallel Circuits**

Use this checklist to make sure your video includes all required parts.

---

### 1. Resistor Selection & Setup

* [ ] Show the three resistors (100 Ω, 220 Ω, 470 Ω).
* [ ] Identify and explain their color codes.
* [ ] Measure each resistor with the DMM and report the values.

### 2. Simulation (EveryCircuit)

* [ ] Open EveryCircuit with the correct resistor values and 5 V DC source.
* [ ] Run the simulation and show branch currents and total current.
* [ ] Confirm voltage is the same across each branch.
* [ ] Fill in and display the simulation results table.

### 3. Circuit Construction

* [ ] Show your breadboard build clearly before power is applied.
* [ ] Point out how your layout matches the schematic.
* [ ] Confirm that your partner checked your wiring.

### 4. Measurements

* [ ] Measure the current in each branch and the total current.
* [ ] Measure the voltage across each resistor.
* [ ] Calculate power dissipation for each branch.
* [ ] Fill in and display the measurement results table.

### 5. Reflection

* [ ] Describe any challenges you encountered (e.g., wiring issues, measurement errors).
* [ ] Share what you learned about parallel circuits from this lab.

---
