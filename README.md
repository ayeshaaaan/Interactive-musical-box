# Interactive Musical Box: A Bluetooth-Enabled Mechanical Music Experience

## 📌 Project Overview
* **Course:** ME 224 – Kinematics of Machinery
* **Project Type:** Interdisciplinary Design Project (Mechanical + Electronics)[cite: 1]
* **Team Members:** Shinjini Ghosh, Ayeshan Raza[cite: 1]
* **Tools Used:** SolidWorks, SolidWorks Motion Analysis, Bluetooth DC Motors[cite: 1]

This repository contains the complete design, kinematic synthesis, and simulation validation for an **Interactive Musical Box**[cite: 1]. The project modernizes the traditional 18th-century fixed-song pin-and-comb mechanism by integrating wireless smartphone audio streaming with synchronised, motor-driven figurine choreography driven by custom cam profiles and four-bar linkages[cite: 1].

---

## 🛠️ Mechanical Design & Kinematics Archetype

### 1. Cam-Driven Figurine Animation
Three unique cam profiles were synthesized mathematically to convert continuous rotary motor input into distinct, repeatable figurine gestures[cite: 1]:
* **Eccentric / Disc Cam:** Chosen for smooth, continuous sinusoidal rise-and-fall motion to drive a bobbing torso synchronized to rhythmic audio[cite: 1].
* **Pear-Shaped Cam:** Engineered with a flat dwell section to keep a follower elevated for a defined arc of rotation, creating a natural pause in an arm gesture[cite: 1].
* **Snail / Spiral Cam:** Designed for progressive, stepped displacement with an instantaneous reset to index orientation between musical phrases[cite: 1].

### 2. Four-Bar Crank-Rocker Linkage (Guitar Arm)
Instead of a cam, a classic four-bar linkage was engineered to produce a natural, low-friction oscillating strumming motion for the guitar figurine[cite: 1]. 

The linkage parameters were synthesized and verified against the **Grashof Condition** to ensure continuous $360^\circ$ rotation of the input crank[cite: 1]:
$$s + l \le p + q$$[cite: 1]

---

## 📊 Simulation & Validation
Using **SolidWorks Motion Analysis**, the assembly was dynamically tested at an input speed of `[e.g., 60 RPM]` to verify[cite: 1]:
1. **Kinematic Profile Accuracy:** Follower displacement matched theoretical lift curves exactly[cite: 1].
2. **Collision Interference Checks:** Confirmed zero mechanical interference within the tight chassis tolerances[cite: 1].
3. **No Follower Jump:** Verified consistent cam-follower contact throughout the cycle[cite: 1].

*Note: You can view the full simulation plots and CAD configurations in the `📂 CAD-Models` and `📂 Simulation-Data` directories[cite: 1].*

---

## 🚀 Future Roadmap & Scalability
The mechanical foundation is designed modularly to support a 4-phase electronics integration roadmap[cite: 1]:
* **Phase 1 (MIDI Integration):** Mapping individual figurine motors to discrete MIDI channels for note-by-note choreography[cite: 1].
* **Phase 2 (Arduino Layer):** Centralizing real-time motor control via PWM signals on an Arduino Mega[cite: 1].
* **Phase 3 (IoT App):** Deploying an ESP32 Wi-Fi module for wireless MIDI file uploads and remote adjustments[cite: 1].
* **Phase 4 (AI Choreography):** Employing a machine learning model to auto-generate figurine movement scripts directly from raw audio waveforms[cite: 1].

---

## 📄 Documentation
* For the full engineering depth, equations, and literature background, read the [Interactive_Musical_Box_Report.pdf][cite: 1].
