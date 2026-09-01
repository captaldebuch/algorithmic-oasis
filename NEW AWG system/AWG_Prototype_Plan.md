# Prototype Idea: The "Multi-Pipe Solar AWG" (Atmospheric Water Generator)
**Project:** AI Garden @ Sorbonne Abu Dhabi (SUAD)  
**Target:** Student-led "Bricolage" for sustainable desert technology.

---

## 1. Concept: Multi-Channel Thermoelectric Condensation
The system uses multiple vertical pipes to create a modular, scalable water collection unit. Each pipe acts as an independent condensation chamber.

### How it works:
1.  **Automation:** An **Arduino/ESP32** monitors a **DHT22** humidity sensor.
2.  **Trigger:** When relative humidity (RH) crosses a threshold (e.g., > 65%, typically at night in Abu Dhabi), the system wakes up.
3.  **Airflow:** Small **12V fans** at the top of each pipe pull humid air into the column.
4.  **Collection ("With What??"):** Inside each pipe is a **Cold Core** powered by a **Peltier tile (TEC)**. The humid air hits the cold heatsink, reaches the dew point, and condenses into droplets.
5.  **Storage:** Gravity pulls the water down the pipe walls/fins into a **Drip Tray** and finally into a central **UV-protected Tank**.

---

## 2. Materials List (for a 4-Pipe Prototype)

### Housing & Structure
-   **PVC Pipes (4x):** 110mm diameter, 50cm length.
-   **T-Junctions/Caps:** For connecting pipes to the water tank.
-   **Mounting Frame:** Wood or Aluminum profile (sturdy enough for wind/sand).

### Thermal Components
-   **Peltier Tiles (4x):** TEC1-12706 (standard 12V 60W).
-   **Internal Heatsinks (4x):** Small aluminum finned heatsinks (must fit inside the pipe).
-   **External Heatsinks (4x):** Large CPU-style heatsinks with fans (mounted on the outside of the pipe to shed heat).
-   **Thermal Paste:** High-quality compound to bridge the TEC to the heatsinks.

### Electronics & IoT
-   **Microcontroller:** Arduino Uno or ESP32 (for WiFi/Dashboard logging).
-   **Sensor:** DHT22 (Temperature + Humidity).
-   **Power Control:** 4-Channel Relay Module or MOSFETs (to switch the 12V current).
-   **Power Source:** 
    -   100W-200W Solar Panel.
    -   Solar Charge Controller (MPPT preferred).
    -   12V Deep Cycle Battery (to run the system during high-humidity night hours).

### Environmental Protection (Abu Dhabi Specific)
-   **Sand Filters:** Fine mesh or active carbon filters at air intakes.
-   **Reflective Paint:** White or "Cool Roof" coating for the exterior to minimize solar heating of the pipes.

---

## 3. Engineering Challenges & Student Tasks

### Challenge A: The "Hot Side" Problem
**Problem:** Peltier tiles create intense heat on one side. If not cooled, the cold side won't work and the tile will burn out.
**Task:** Students must design the "thermal bridge" so the hot side is outside the pipe, cooled by a large fan, while the cold side is inside.

### Challenge B: Sand & Dust
**Problem:** Abu Dhabi sand will clog fans and coat condensation fins (reducing efficiency).
**Task:** Implementation of a "Pre-filter box" and a monthly "Self-clean" cycle (reversing fans to blow dust out).

### Challenge C: Efficiency Calculation
**Task:** Using the `Fujairah_weather_1990_today.csv` data (or local SUAD logs), students should calculate the **Theoretical vs. Actual Yield** (Liters per kWh).

---

## 4. Integration with CAPTAL-LAB Projects

-   **AI Garden / Cern of AI:** This hardware acts as a "Data Node". Students can use the local AI (Ollama/Llama) to analyze the humidity patterns and optimize the start/stop times.
-   **Digital Humanities:** This is a "remédiation" of ancient dew-collection techniques (like the Chilean *Atrapanieblas* or ancient Persian *Qanats*) using modern "bricolage" (Peltier/Arduino).
-   **Musicology/Sound:** Add a piezoelectric sensor to the drip tray. The "clink" of each drop can be mapped to a MIDI note, creating a "Generative Soundscape of Water" for the garden.

---

## 5. Implementation Plan

1.  **Phase 1 (Week 1):** Bench test a single Peltier tile. Measure the temperature drop.
2.  **Phase 2 (Week 2):** Build the "Condensation Column" (Pipe + Heatsink + Fan).
3.  **Phase 3 (Week 3):** Automation. Code the Arduino to trigger only when RH > 65%.
4.  **Phase 4 (Week 4):** Solar Integration. Connect the panel and battery.
5.  **Phase 5 (Week 5):** Outside Deployment. Monitor yield and sand accumulation.
