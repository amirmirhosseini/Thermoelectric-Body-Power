# Bio-Thermoelectric Power Generation (Body Heat Energy Harvesting)

An Engineering Project focused on harvesting human body heat using the Seebeck Effect and Thermopiles to generate clean, sustainable electrical energy for low-power wearable devices and IoT applications.

## Project Overview
With the rapid growth of the Internet of Things (IoT) and wearable electronics, finding sustainable, dynamic, and continuous power sources is a major challenge. This project investigates the potential of converting the temperature differential between the human body and the surrounding environment into usable electrical energy. 

By designing a localized system integrated into wearable accessories (such as a wristwatch), this device leverages solid-state thermodynamic phenomena to provide a reliable battery-free power alternative, reducing reliance on fossil fuels and chemical batteries.

## Key Features
* **Sustainable Energy Source:** Utilizes continuous and dynamic human metabolic heat dissipation.
* **Seebeck Effect Implementation:** Explores solid-state conversion of temperature gradients ($\Delta T$) into electrical voltage.
* **Thermopile Integration:** Implements micro-machined thermoelectric modules (TEGs) optimized for compact wearable form factors.
* **Battery-Free Operation:** Designed to directly power or trickle-charge ultra-low-power devices like medical sensors or smartwatches.

---

## Technical Specifications & Mechanism

### 1. The Seebeck Effect
The core operating principle relies on the Seebeck Effect, where a temperature difference between two dissimilar electrical conductors or semiconductors produces a voltage difference.

$$\Delta V = \alpha \cdot \Delta T$$

Where:
* $\Delta V$ is the generated thermoelectric voltage.
* $\alpha$ is the Seebeck coefficient of the material.
* $\Delta T$ is the temperature difference between the skin surface (hot junction) and ambient air (cold junction).

### 2. System Architecture
The device consists of the following key components:
* **Thermal Interface:** Optimizes heat transfer from human skin to the thermoelectric module.
* **Thermopile Arrays:** Multiple pairs of thermocouples connected electrically in series and thermally in parallel to amplify the output voltage.
* **Power Management Circuitry:** Implements step-up (boost) converters to elevate the low-millivolt output to standard operational voltage levels (e.g., 1.8V - 3.3V) and stores excess energy in a supercapacitor or rechargeable micro-battery.

---

## Project Structure
The repository is organized based on the project deliverables and milestones:
* `/Docs`
  * `hw1.pdf`: Initial feasibility study and analysis of sustainable electrical energy potential from human physical activities.
  * `hw2.pdf`: Comprehensive technical report focusing on thermoelectric methods and system scaling.
  * `hw4.pdf`: Final project poster and summarized technical brief.
* `/Presentation`
  * `hw3.pptx`: Official presentation slides detailing the history of clean energy, system schematics, and performance analysis.

---

## Performance Analysis & Evaluation

### Pros:
* **Completely Autonomous:** Eliminates the need for external charging docks or frequent battery replacements.
* **Compact & Lightweight:** Micro-mechanics enable integration without adding bulky or heavy components to wearable garments.
* **Eco-Friendly:** Zero emissions, zero hazardous chemical waste from disposable batteries.

### Cons & Challenges:
* **Ambient Dependence:** Performance highly relies on specific ambient temperature thresholds to maintain a stable gradient.
* **Thermal Path Voltage Drops:** Micro-losses and thermal resistance across material interfaces can degrade overall efficiency.
* **Low Initial Power Output:** The raw power generated from standard skin-to-air gradients is limited, demanding high-efficiency power management circuits.

---

## Future Enhancements
1. **Advanced Thermoelectric Materials:** Incorporating materials with a higher Figure of Merit ($ZT$) to enhance conversion efficiency.
2. **Flexible TEGs:** Utilizing flexible polymers to better conform to body contours, reducing thermal contact resistance.
3. **Hybrid Energy Harvesting:** Combining thermoelectric modules with flexible piezoelectric cells to capture kinetic energy from body movements simultaneously.

## Authors
* **Ali Fotouhi**
* **Amirmohammad Mirhosseini** - [GitHub Profile](https://github.com/your-amir-profile) / [University Email](mailto:amir.mirhosseini@ut.ac.ir)

*School of Mechanical Engineering, College of Engineering, University of Tehran*
