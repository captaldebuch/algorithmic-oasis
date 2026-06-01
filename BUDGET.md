# Project Budget — Algorithmic Oasis
**SUAD AI Research Garden · 2026–2028**  
**Affiliations:** SAFIR Lab · SCAI · Sorbonne University Abu Dhabi

> All figures in **UAE Dirhams (AED)**. Conversion rate applied: 1 EUR ≈ 4.00 AED (indicative rate, June 2026).

> This project achieves exceptional research leverage: **18,400 AED** in existing institutional assets underwrites a two-year programme requiring only **13,900 AED in new funding** — a 1.3:1 asset-to-investment ratio. Total new funding sought is modest relative to the scope of publications, prototypes, and student impact targeted.

---

## Section 1 — Existing Infrastructure (Inventory Assets)

*All items below are already available in the SUAD lab and garden. Listed at estimated inventory value.*

| Item | Description | Est. Value (AED) | Status |
| :--- | :--- | :--- | :--- |
| **Ma Hawa GENNY** | Atmospheric Water Generator — Indoor (up to 30L/day) | 10,000 | In-situ |
| **Ma Hawa Mobile Box** | AWG — Outdoor/Mobile (up to 25L/day, 350W) | 7,200 | In-situ |
| **APKLVSR Sensors** | 5-pack capacitive soil moisture sensors (corrosion-resistant) | 100 | In-situ |
| **BigBlue 28W Solar** | Foldable solar charger — USB-C/A, 25.4% efficiency | 280 | In-situ |
| **ELECOM Nestout** | 15,000 mAh power bank — IP67, 32W USB-C fast charge | 240 | In-situ |
| **JUOVI / Nobis** | Additional 20,000 mAh power banks (65W USB-C) | 400 | In-situ |
| **Ruwshuuk Sensor** | Wireless soil humidity & temperature sensor | 180 | In-situ |
| **Total Inventory Value** | | **18,400** | |

---

## Section 2 — Year 1 New Funding: Foundation & Digital Metabolism (2026–2027)

*Focus: indoor automation, data acquisition pipeline, and interdisciplinary research setup.*

| Item | Specification | Total (AED) |
| :--- | :--- | :--- |
| **Microcontrollers** | 5× ESP32-S3 (hardware AI accelerator, analog-capable, 5V) | 300 |
| **Actuators** | 12V solenoid valves, micro-pumps, relay modules | 400 |
| **Enclosures** | Custom 3D-printed / acrylic IP-rated housings | 200 |
| **Plants, Seeds, Soil & Pots** | Specimen plants (succulents, aromatic herbs, native desert flora), propagation seeds, well-draining substrate, and pots of varying sizes optimized for sensor placement | 2,400 |
| **Solar Panel (Lab)** | 1× compact 50W rigid panel + MPPT charge controller for lab window/balcony — powering sensors and microcontrollers independently from mains | 500 |
| **Outdoor Battery Pack** | 1× IP65-rated 20,000–30,000 mAh LiFePO4 battery enclosure — field-deployable, tolerates 50°C, powers the sensor node array overnight | 600 |
| **Drip Irrigation System** | Modular drip-by-drip delivery kit — main reservoir, distribution manifold, adjustable drippers (1 per pot), food-grade tubing, and solenoid valve integration harness | 800 |
| **Maker Tools & Small Equipment** | Wire spools, heat-shrink tubing, project boxes, cable ties, cutters, pliers, soldering iron & supplies, multimeter, cable management materials | 600 |
| **Dedicated Project Computer** | Mini-PC or laptop assigned permanently to the Oasis lab station — for continuous data logging, model training, dashboard hosting, and student coding sessions | 2,000 |
| **Workshop Materials** | Cross-domain sprint supplies, student documentation kits | 300 |
| **Consumables** | Calibration media, breadboard prototyping supplies, replacement connectors | 400 |
| **Year 1 Total** | | **8,500** |

---

## Section 3 — Year 2 New Funding: Resilience & The Autonomous Chorus (2027–2028)

*Focus: outdoor deployment at SUAD campus, solar expansion, public installation.*

| Item | Specification | Total (AED) |
| :--- | :--- | :--- |
| **Solar Expansion** | 200W rigid panels + MPPT charge controller | 1,600 |
| **Deep Cycle Battery** | 100Ah LiFePO4 — buffers Ma Hawa Mobile Box (350W peaks) | 2,000 |
| **Public Display** | Weatherproof outdoor screen for campus data dashboard | 800 |
| **Connectivity** | 4G/LTE IoT gateway + 24-month SIM data plan | 600 |
| **Maintenance Reserve** | Replacement sensors, cleaning kits, dust protection | 400 |
| **Year 2 Total** | | **5,400** |

---

## Section 4 — Summary

| Phase | Category | Cost (AED) |
| :--- | :--- | :--- |
| **Phase 0** | Existing Inventory (leverage, no new spend) | (18,400) |
| **Phase 1** | New Equipment — Year 1 (2026–2027) | 8,500 |
| **Phase 2** | New Equipment — Year 2 (2027–2028) | 5,400 |
| **Total New Funding Required** | | **13,900** |

---

## Technical Notes

- **Plants & substrate:** Species selected for minimal water consumption and tolerance of Abu Dhabi temperature ranges. The AI system will be trained on these specific specimens, making species selection a scientific variable, not only an aesthetic one.
- **Drip irrigation:** Drip-by-drip delivery is the correct architecture for this system — it allows per-pot precision dosing controlled by the PT algorithm, minimizes waste, and produces clean sensor feedback loops. Each dripper is independently addressable via the solenoid valve harness.
- **ESP32-S3 over Raspberry Pi:** APKLVSR capacitive sensors require stable 5V power for the NE555 timer circuit. The ESP32-S3 provides native 5V compatibility, hardware AI acceleration for TinyML, and native analog inputs — making it the correct platform for this project.
- **LiFePO4 for outdoor buffer:** Required to handle the Ma Hawa Mobile Box's 350W average draw (480W peak) during outdoor deployment in Year 2. The 100Ah LiFePO4 chemistry is chosen for thermal stability at Abu Dhabi temperatures.
- **Budget excludes:** Student stipends, travel to conferences, and university overhead costs, which are handled separately through institutional channels.

---

*Document Version: 3.0 (June 2026)*  
*Prepared for: SAFIR Lab Research Committee*
