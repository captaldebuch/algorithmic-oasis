<p align="center">
  <img src="logo_suad.png" width="60" />
  <img src="logo_safir.jpg" width="60" />
  <img src="logo_scai.jpg" width="60" />
</p>

#  Algorithmic Oasis — Eco-Autonomous Intelligence
**Project Portal:** [captaldebuch.github.io/algorithmic-oasis/](https://captaldebuch.github.io/algorithmic-oasis/)  
**SAFIR Research Centers:**
- **Artificial Intelligence and Digital Policies** (Primary)
- **Environment and Sustainable Development** (Primary)
- **Applied Mathematics, Statistics and Data Science** (Secondary)

---

## 1. Abstract
The **Algorithmic Oasis** project develops a smart, self-sustaining irrigation system that captures water directly from the air using Atmospheric Water Generation (AWG) technology. Managed and monitored by AI, the system autonomously waters the plants in the campus garden based on real-time environmental data. This "Living Laboratory" at Sorbonne University Abu Dhabi involves interdisciplinary student teams (Mathematics, Physics, Ecology) who lead the research and maintenance, demonstrating how autonomous technology can support urban sustainability in hyper-arid climates.

## 2. Scientific Context, Motivation & Economic Positioning
Abu Dhabi faces extreme heat and chronic water scarcity. While urban areas rely on desalinated municipal water, Atmospheric Water Generation (AWG) uses 20 to 80 times more energy per liter. Consequently, this project targets **off-grid ecological restoration phases (18-36 months)**—such as mangrove nurseries or desert afforestation—where the alternative is expensive trucked water (20-60 AED/m³). The system is designed to be highly portable, moving between sites once the flora is established. 

Instead of relying on the grid or trucks, the project harvests water from the atmosphere and power from the sun. The core research focus is on developing algorithms that predict when plants need water and manage energy storage effectively, ensuring survival during sandstorms or low-sunlight periods. Students gain hands-on experience in building and governing these resilient, AI-driven ecological systems.

## 3. Research Pillars
- **Pillar A: Predictive Metabolic Control (Physical & AI):** Establishing a robust physical baseline using continuous gravimetric mini-lysimetry (load cells) and the FAO-56 Penman-Monteith model to accurately measure Evapotranspiration (ET). Only once this physical truth is established will Reinforcement Learning (RL) models be deployed to optimize irrigation and minimize water "waste".
- **Pillar B: Autonomous Resource Orchestration & The Value Cascade:** Engineering a decision-making agent that operates on an "Order of Merit" scheduler: prioritizing passive HVAC Condensate, deploying AWG only when psychrometrics allow, and using municipal water only as a last resort. The architecture physically links these systems, recovering the 3-5 kWth rejected heat from the GEN-M1 AWG to regenerate the solar sorption bench.
- **Pillar C: Agentic Pedagogy & Interdisciplinary Methodology:** Evaluating the efficacy of "Oasis Squads" — transdisciplinary student teams (Mathematics, Physics, Ecology) — in accelerating the deployment of complex, real-world eco-autonomous systems.

## 4. Methodology & Technical Architecture
The research is executed across two experimental phases:

### Phase 1: Physical Baseline, "OASIS Alpha" & P0 Sorption Bench (Year 1)
Focused on establishing the experimental ground truth. Key activities include deploying ESP32-S3 nodes with 50kg load cells to create continuous gravimetric mini-lysimeters. Simultaneously, we will run the **P0 Sorption Matrix Selection**, testing CaCl₂ on 5 matrices (Cellulose, Alginate, Vermiculite, Foam, Silica) using 1kg load cells (TAL221) under two airflow regimes. 

The core scientific innovation is a **three-way AWG comparison**: evaluating Compression (GEN-M1), Solar Sorption (P1 closed cycle), and HVAC Condensate under a single, unified psychrometric record and gravimetric metrology. This replaces highly-variable capacitive sensors as the primary measurement tool and introduces strict baselines (e.g., fixed-timer irrigation controls).

### Phase 2: Arid-Field Deployment & Thermal Optimization (Year 2)
Transposing the calibrated system to a 10-15m² testbed in the SUAD campus garden. This phase utilizes the **Ma Hawa Mobile Box** (350W-480W) operating on a short-cycle (4-5 hours/night) to match battery limitations. The physical design of the Oasis is strictly dictated by thermodynamics: ensuring low, shaded air intakes and unobstructed high exhausts to dissipate the 3-5 kWth rejected heat, preventing the AWG from suffocating on its own recirculated dry air.

## 5. Expected Scholarly Impact
- **Algorithmic Contribution:** An open-source RL framework for arid-climate resource optimization.
- **Empirical Dataset:** A longitudinal atlas of AWG performance and soil-ambient metrics in Abu Dhabi.
- **Pedagogical Framework:** A validated model for interdisciplinary "Agentic Research" training.

## 6. Selected References (2024–2026)
1. **Rahul S G, et al. (2026).** *Sustainable Agriculture through IoT-Driven Smart Irrigation with Explainable AI.* Frontiers in AI.
2. **Rahima Nouasse, et al. (2026).** *AI-Driven LoRaWAN-Based Smart Irrigation System for Arid Regions.* Materials Research Proceedings.
3. **M. S. M. Rafi, et al. (2025).** *Reliable and cost-efficient IoT connectivity for smart agriculture.* arXiv:2503.11162.
4. **Uma Maheshwari, R., et al. (2025).** *Edge–Enabled Smart Irrigation System Using Multi-Sensor IoT Networks.* CompSci Advances.

## 7. Project Coordination & Leadership

- **Dr. Xavier Fresquet**: Head of Sorbonne Center for Artificial Intelligence (SCAI), Abu Dhabi — Paris (xavier.fresquet@sorbonne.ae).
- **Safaa El Sayed**: Assistant Professor of Mathematics, Sciences and Engineering Department (safaa.elsayed@sorbonne.ae).
- **Dr. Beatriz Garcia**: Sustainability Officer and Associate Professor, Sorbonne University Abu Dhabi (PhD in International Law).


---
*Prepared by CAPTAL-LAB for the SAFIR Lab Research Committee and SCAI (June 2026).*
