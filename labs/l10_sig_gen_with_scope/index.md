Here’s the revised version of **Lab 10** with all point references and the total score removed:

---

### EET103 Electrical Studies I

### [EET103](../../) - [Labs](../) - **Alternating Current & Oscilloscopes**

### Lab 10: Alternating Current & Oscilloscopes (with XR2206 Function Generator)

**Name:** _____________________________

---

**Objective:**

- **Observe the frequency range of a signal generator.**  
- **Observe AC signals on an oscilloscope.**  
- **Build a basic AC circuit and measure power.**  
- **Apply Ohm’s Law to AC circuits to calculate voltage, current, and power.**

---

#### Materials: 
- XR2206 Precise Function Signal Generator 
- Multimeter  
- Oscilloscope
- Scope probes
- Breadboard
- Resistors - 1K (x2)
- Speaker
- Passive buzzer  

### **Part 1: Signal Generator**

1. In your own words, what is a signal generator (or function generator)?  
2. Determine the frequency range of the XR2206 Precise Function Signal Generator and note the following:
   - Minimum frequency:  
   - Maximum frequency:  
3. What is the maximum amplitude produced by the function generator? Is this a peak voltage, peak-to-peak voltage, or RMS voltage?  
4. Connect the function generator to a speaker:
   - Set the amplitude to minimum and the frequency to 1 kHz.  
   - Gradually increase the amplitude and note at what voltage level you can hear the signal.  
   - Vary the frequency and observe how the sound changes with frequency.  
   - Can you hear a 60 Hz signal?  
   - What is the maximum frequency you can hear?  
5. Connect your passive buzzer to the output.
    - Adjust the frequency and amplitude of the signal generator.
    - How is this device similar to a speaker. How is it different?

---

### **Part 2: Oscilloscopes**

1. Describe what an oscilloscope is in your own words.  
2. Explain what is meant by the setting “volts/division.”  
3. Does changing the “volts/division” setting change the amplitude of the displayed signal?  
4. Define what is meant by the setting “seconds/division.”  
5. Record the make and model of the oscilloscope you are using.  
6. Connect the function generator to the oscilloscope:
   - Set the frequency to 1000 Hz (1 kHz) and the amplitude to a peak voltage of 1 volt.  
   - Sketch a rough diagram of the displayed waveform below:  

   ![Oscilloscope Screenshot](scope_display.png)

7. Record the following measurements from the oscilloscope:

    
    | Setting/Measurement | Value | Units |
    |--------|--------|------|
    | Volts/division | |   |  
    | Peak voltage| |   |   
    | Peak-to-peak voltage:| |   |   
    | Time Base| |   |   
    | Period| |   |

8. Calculate the RMS voltage.  
9. Adjust your function generator jumpers and/or connections to display square and triangular waves on your scope. Describe what changes in the waveform and what remains the same.  

---

### **Part 3: Basic AC Circuit**

#### Circuit Diagram:

![AC Circuit](ac_circuit.png)

- **R1:** 1 kΩ  
- **R2:** 1 kΩ  
- **Signal:** 2 V peak, 1 kHz  

1. Construct the circuit as shown above. Set the signal to 2 volts peak and 1 kHz.  
2. Is this a series or parallel circuit?  
3. Calculate the peak voltage across **R2**.  
4. Calculate the RMS voltage across **R2**.  
5. Using your oscilloscope:
   - Connect one channel to display the input voltage and the other to display the voltage across **R2**.  
   - *Ensure both channels share a common ground and adjust the display so that both channels use the same zero voltage reference.*  
6. Measure and record the peak voltage across **R2** using the oscilloscope.  
7. Measure and record the RMS voltage across **R2** using the oscilloscope.  
8. Use your DMM to measure the frequency.  
9. Measure the AC voltage across **R2** using your DMM. Does the DMM display peak or RMS voltage?  
10. Calculate the RMS current through the circuit.  
11. Calculate the power dissipated by **R2** using the RMS voltage and RMS current.  

---

### **Part 4: Post-Lab Questions**

1. What was the most challenging part of using the oscilloscope and function generator?  
2. Why is it important to use RMS values of voltage and current when calculating power in an AC circuit?  
3. Do Kirchhoff’s voltage and current laws apply to AC circuits? Justify your answer.

