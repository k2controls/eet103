Awesome—here are three ready-to-teach **series-circuit** examples with concrete values, clean talking points, and quick calculations you can put on the board.

# 1) “Flashlight”: cells in series + lamp (with internal resistance)

**Why it’s useful:** Models a real flashlight and lets you talk about how batteries dim as they discharge (rising internal resistance).

```
  (+) ──[ AA 1.5 V ]─[ AA 1.5 V ]─[ AA 1.5 V ]───[ r_int=0.2Ω each ]───[ Lamp ≈ 20Ω ]── (−)
                                   (total r_int = 0.6Ω)
```

* Source: 3×AA ≈ **4.5 V**
* Lamp: **20 Ω** (incandescent or “equivalent” resistive load)
* Internal resistance: **0.2 Ω per cell → 0.6 Ω total**
* Total series resistance: **R\_T = 20 + 0.6 = 20.6 Ω**
* Current: **I = 4.5 / 20.6 ≈ 0.218 A (218 mA)**
* Voltage across lamp: **V\_lamp = I·20 ≈ 0.218·20 ≈ 4.37 V**
* Power in lamp: **P\_lamp ≈ I²·R = (0.218)²·20 ≈ 0.95 W**
* Power lost in cells (internal): **P\_int ≈ I²·0.6 ≈ 0.029 W**

**Talking points**

* As cells age, **r\_int↑ ⇒ I↓ ⇒ V\_lamp↓ ⇒ dimmer**.
* Great setup to practice **KVL** and **power distribution** in a series chain.
* Ask students: *“If internal resistance doubles, what happens to current and lamp brightness?”*

---

# 2) Classic **Voltage Divider**: scaling 12 V down to \~3.3 V for an ADC

**Why it’s useful:** The go-to real application—reading a higher-voltage signal (e.g., car battery) with a microcontroller/ADC that tolerates only 3.3 V.

```
  12 V ──[ R1 = 26.7 kΩ ]────o────[ R2 = 10 kΩ ]── 0 V
                             |
                           Vout  (~3.27 V from 12 V)
```

* Choose **R2 = 10 kΩ**, **R1 = 26.7 kΩ** (E24)
* Divider ratio: **Vout = Vin · R2/(R1+R2) = 12 · 10k/(26.7k+10k) ≈ 3.27 V**
* Divider current: **I\_div = 12 / (36.7 kΩ) ≈ 0.327 mA**

**Talking points**

* **Loading caution:** The ADC input must be high impedance; otherwise Vout will sag.
  (Rule of thumb: input impedance ≫ 100× divider’s Thevenin resistance.)
* Add a **buffer (op-amp follower)** or choose smaller resistors if loading is an issue.
* Easy extension: **Map 9–15 V battery range** to a safe ADC span; have students compute Vout at 9 V and 15 V.

**Quick board questions**

* *“What’s Vout if Vin = 14.4 V?”*
  $V_{out} \approx 14.4 \cdot \frac{10}{36.7} \approx 3.93 \text{ V}$ → too high for 3.3 V ADC; discuss protection (zener clamp/TVS, buffer, larger ratio).

---

# 3) **Two LEDs in Series + One Resistor** from a 9 V source

**Why it’s useful:** Super visual, reinforces why we prefer series strings for matched current in LEDs.

```
  9 V ──[ R ]──|>|──|>|── 0 V
               D1   D2   (red LEDs, Vf ≈ 2.0 V @ ~15 mA)
```

* Target LED current: **I ≈ 15 mA**
* LED drops: **\~2.0 V + 2.0 V = 4.0 V**
* Resistor: **R = (9 − 4) / 0.015 = 333 Ω → pick 330 Ω (E12)**
* Actual current: **I ≈ (9 − 4)/330 ≈ 15.15 mA**
* Resistor power: **P\_R ≈ I²·R ≈ (0.01515)²·330 ≈ 0.076 W** → **¼ W** resistor is comfy.

**Talking points**

* In **series**, **current is identical** through both LEDs—colors match more consistently.
  In **parallel**, each LED needs **its own resistor** to avoid current hogging.
* **Supply sag example:** If the battery drops to **7 V**, current becomes (7−4)/330 ≈ **9.1 mA** → visibly dimmer.
* Temperature and **Vf variation**: why a constant-current driver is better for long strings.

**Quick board questions**

* *“If we swap to two blue LEDs (Vf≈3.0 V each), does this still work from 9 V with 330 Ω?”*
  (9 − 6)/330 ≈ **9.1 mA** → dimmer; adjust R to get 15 mA (R ≈ (9−6)/0.015 = **200 Ω**).

---

If you want, I can package these into a **1-page handout** with space for student calculations and a mini “what-if” section for each.
