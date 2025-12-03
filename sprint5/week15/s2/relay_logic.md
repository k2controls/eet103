
## ✅ **Part 1: What is a Relay?**

*   **Definition**: A relay is an electromechanical switch that uses a small electrical signal to control a larger one.
*   **Components**:
    *   **Coil**: Energized by a control voltage.
    *   **Contacts**:
        *   **Normally Open (NO)**: Closes when coil is energized.
        *   **Normally Closed (NC)**: Opens when coil is energized.
*   **Why use relays?**
    *   Isolation between control and power circuits.
    *   Ability to control high-current loads with low-current signals.

**Simple Example**:

*   A push button energizes a relay coil.
*   Relay closes NO contacts → turns on a lamp.

***

## ✅ **Part 2: Introduction to Ladder Logic**

*   **What is Ladder Logic?**
    *   A graphical programming language that looks like a ladder.
    *   Two vertical rails (power lines) and horizontal rungs (logic).
*   **Origin**: Derived from relay control diagrams.
*   **Basic Elements**:
    *   **Contacts**: Represent inputs (switches, sensors).
        *   `[ ]` = Normally Open (XIC in PLC)
        *   `[/]` = Normally Closed (XIO in PLC)
    *   **Coils**: Represent outputs (motors, lamps).
        *   `( )` = Output Energize (OTE in PLC)

***

## ✅ **Part 3: Simple Logic Examples**

### **1. OR Logic (Parallel)**

*   **Goal**: Light turns ON if **Switch A OR Switch B** is ON.
*   **Relay Circuit**: Switches in parallel → relay coil → lamp.
*   **Ladder Diagram**:

<!---->

    |----[ ]----|
    |           |----( ) Light
    |----[ ]----|

### **2. AND Logic (Series)**

*   **Goal**: Light turns ON if **Switch A AND Switch B** are ON.
*   **Relay Circuit**: Switches in series → relay coil → lamp.
*   **Ladder Diagram**:

<!---->

    |----[ ]----[ ]----( ) Light

### **3. NOT Logic**

*   **Goal**: Light ON when A is ON and B is OFF.
*   **Ladder Diagram**:

<!---->

    |----[ ]----[/]----( ) Light

***

