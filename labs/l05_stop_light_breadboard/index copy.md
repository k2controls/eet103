Here's a draft for Lab 4 on parallel circuits based on the format of Lab 3. This version emphasizes parallel resistance, branch currents, and power dissipation calculations.

---

## EET103 Electrical Studies I

### [EET103](../../) - [Labs](../) - Stop Light Control Project

Name _____________________________

Partner ____________________________

#### Objectives: 
Your objectives are clear and well-structured, emphasizing both technical and professional skills. Here are some suggestions for improvements and extensions:

### Revised Objectives:
1. Investigate the voltage drop and current requirements of Light Emitting Diodes (LEDs).**
2. Construct a series-parallel circuit on a breadboard using LEDs, resistors, and switches to simulate Stop Light control.**
3. Demonstrate professional-level breadboarding skills with organized component layout, trimmed leads for secure insertion, flat wiring, and appropriate color coding for power, ground, and signal.**
4. Validate the functionality of the Stop Light circuit, ensuring correct operation of switches and LEDs.**
5. Conduct a peer review by assessing your build and a teammate’s build using the provided rubric, focusing on circuit functionality and professional presentation.**
6. Transfer your breadboarded prototype to a perforated board, positioning components logically for optimized circuit flow.**
7. Complete the final circuit assembly using point-to-point soldering techniques as demonstrated by the instructor, ensuring durable and reliable connections.**
8. Evaluate the performance of your circuit and complete troubleshooting actions by measuring voltages and currents at key points to confirm expected behavior.


#### Materials: 
- Digital multimeter (DMM)
- Breadboard with integrated power supply
- SPDT toggle switch
- Momemtary pushbutton switch (x3)
- White LED
- Red, Yellow, and Green LEDs
- Current limiting resistors (x4)

#### Procedure

### Part 1 - Circuit Introduction

1. **Investigate the Circuit in EveryCircuit**:
   - Use your EveryCircuit link below to investigate the Stop Light project. 
   
   https://everycircuit.com/circuit/5026351740092416

   - What is the purpose of S1 and D1?
   - Using current vs voltage graph for the LED below to investigate this nonlinear device. 
   - If you assume the voltage drop across the LED when it is lit is 1.5V then how much current is flowing in each branch when the pushbutton is depressed.
   - Is your calculated value for LED current validated by the EveryCircuit simulation?
   
5. **Simulate Circuit Operation**:
   - Press the space bar to run the simulation and observe current flow and voltage levels.
   - Use the pause and rewind buttons to stop and edit the circuit.

6. **Add Ammeters**: Add ammeters in series with each resistor to observe the branch currents.

    ![parallel circuit with ammeters](parallel_with_ammeters.png)

7. **Record Simulation Results**: Document the current through each branch, the total current, and voltage across each resistor in the table below.

| Component | Value | Branch Current | Voltage Drop |
|-----------|-------|----------------|--------------|
| R1        |       |                |              |
| R2        |       |                |              |
| R3        |       |                |              |
| Total     |       |                |              |

8. **Calculate Power Dissipation**:
   - Use the formula ( P = I<super>2</super> x R ) for each branch to calculate power dissipation and record the values.

| Component | Branch Current | Resistance | Power Dissipation |
|-----------|----------------|------------|-------------------|
| R1        |                |            |                   |
| R2        |                |            |                   |
| R3        |                |            |                   |

### Part 2 - Parallel Circuit Construction and Measurement

1. **Inspect Resistors**: Examine the three resistors selected in Part 1.
   - Record their nominal values.
   - Use an AI prompt or manual reference to determine the color code for each resistor.
   - Measure the actual resistance using the DMM.

| Component | Nominal Value | Color Code | Measured Value |
|-----------|---------------|------------|----------------|
| R1        |               |            |                |
| R2        |               |            |                |
| R3        |               |            |                |

3. **Construct the Parallel Circuit**:
   - Use your knowledge of "breadboarding" from the pior lab to build the parallel circuit from Part 1 on a breadboard. Refer to the schematic and plan component layout carefully. Have your partner review prior to energizing your circuit

    ![breadboard with parallel resistors](breadboard_parallel.png)

5. **Energize and Measure**:
   - Use the DMM to measure the circuit’s total current and the branch currents through each resistor. Measure voltage across each resistor to confirm they are the same.
   - Measure power dissipation by calculating P = I<super>2</super> x R or using the  P = V x I formula for each branch.

6. **Record Your Results**:

| Component | Value | Branch Current | Voltage Drop | Power Dissipation |
|-----------|-------|----------------|--------------|-------------------|
| R1        |       |                |              |                   |
| R2        |       |                |              |                   |
| R3        |       |                |              |                   |
| Total     |       |                |              |                   |

### Assessment

1. **Video Demonstration**:
   - Create a video summarizing your lab activity. Include the following points:
     - Resistor selection and schematic overview.
     - Simulation results from Part 1 (screen-sharing the EveryCircuit app is encouraged).
     - Breadboard circuit build and description of voltage source and current flow.
     - Discussion of your measurements from Part 2, comparing them to the simulation results. Show this document with values entered.
     - Power dissipation calculations and discussion of the relationship between current and power in each branch. Which values of resistance dissipated the most power?
     - Challenges encountered during the lab and lessons learned.

