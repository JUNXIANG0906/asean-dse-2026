# 🌾 FWise (FoodWise) — Know Before. Act Before.

[![Competition](https://img.shields.io/badge/ASEAN%20DSE%202026-Malaysia%20National%20Finalist-gold?style=for-the-badge)](https://aseandse.org/)
[![Team](https://img.shields.io/badge/Team-JJ%20Vision-green?style=for-the-badge)]()
[![Institution](https://img.shields.io/badge/Universiti%20Teknologi%20Malaysia-UTM-maroon?style=for-the-badge)]()
[![Analytics](https://img.shields.io/badge/Powered%20by-SAP%20Analytics%20Cloud-blue?style=for-the-badge)]()

> **"How can we turn climate information into food security resilience?"**  
> A data-driven food security resilience platform bridging fragmented climate data and coordinated multi-stakeholder action across Malaysia and ASEAN.

---

## 🏆 Competition Recognition
* **Event:** ASEAN Data Science Explorers (ASEAN DSE) 2026 *(Organized by ASEAN Foundation & SAP)*
* **Achievement:** 🇲🇾 **Malaysia National Finalist**
* **Team Name:** **JJ Vision** (Universiti Teknologi Malaysia)
  * **Tan Jia Wei**
  * **Wong Jun Xiang**

---

## 🌍 The Problem & Systemic Root Causes

Across ASEAN, **12.8% of the population (87.6 million people)** experienced moderate or severe food insecurity between 2023 and 2025. In Malaysia, climate change acts as a **threat multiplier**—triggering floods, erratic rainfall, and droughts that simultaneously hit an already fragile food system:

1. **Baseline Production Vulnerabilities:** Malaysia's rice Self-Sufficiency Ratio (SSR) dropped to **52.9%** in 2024, while paddy production fell **5.3%** (to 2.06M tonnes).
2. **Import Dependence:** Malaysia spent **RM93.8 billion** on food imports in 2024 (+19.1% YoY), with heavy reliance on imports for staples like onions (100%), garlic (100%), beef (83.5%), and mutton (92.1%).
3. **Escalating Flood Impacts:** Flood incidents rose **66.3%** from 2023 to 2024 (809 to 1,345 incidents), driving agricultural losses up **53.5%** to **RM185.2 million** (including RM158.7M in Kedah paddy losses alone).

### Why Does One Climate Shock Amplify Multiple Vulnerabilities?
* **Fragmented Information:** Hazard, hydrological, and agricultural datasets exist in silos across separate agencies.
* **Information Gaps:** **40%** of 143 critical climate/agricultural data items in Malaysia were unavailable, and only **18%** were readily accessible.
* **Prediction-Action Gap:** Existing early-warning systems struggle to translate raw meteorological forecasts into localized, role-specific directives.
* **Insufficient Resilience:** Delayed responses lead to recurring supply chain bottlenecks and severe economic exposure.

---

## 💡 Proposed Solution: FWise Ecosystem

**FWise (FoodWise)** is an end-to-end intelligence and operational platform built around four core pillars:

1. **📡 IoT Climate Monitoring (FWise Field Stations):** Proprietary solar-powered Automatic Weather Stations (AWS) equipped with anemometers, wind vanes, radiation-shielded temp/RH sensors, tipping-bucket rain gauges, pyranometers, barometers, multi-depth soil moisture/EC probes, and ultrasonic canal water-level sensors transmitting via 4G/LoRaWAN.
2. **🔗 Integrated Data Hub:** Standardizes and unifies ground-truth field telemetry with national datasets from **METMalaysia, JPS, MADA, DOA, NADMA, KPKM, KPDN, and DOSM**.
3. **🧠 CRIS (Food Security & Climate Resilience Intelligence System):** An AI-assisted analytical engine that detects environmental anomalies, runs **Food Security Stress Tests**, simulates disaster scenarios, and ranks multi-agency intervention strategies.
4. **📱 Collaborative Action Network (Web & Mobile Portal):** Dispatches tailored, prioritized action directives to government agencies, agricultural producers, and logistics operators—complete with real-time progress tracking and evidence verification.

---

## 🧮 Mathematical & Analytical Framework (CRIS Engine)

The CRIS decision-support engine evaluates risk and optimizes intervention strategies using multi-criteria modeling:

* **Climate-Risk Scoring Model:**
  $$R_h = \sum_{i=1}^{n} w_{h,i} S_i$$
  *(Weighted aggregation of standardized environmental abnormality scores $S_i$ across hazard types $h$)*

* **Projected Production Loss:**
  $$L_{\text{production loss}} = A_{\text{affected}} \times Y_{\text{baseline}} \times L_{\text{rate}}$$

* **Strategy Resilience Score (Multi-Criteria Optimization):**
  $$RS_s = \sum_{j=1}^{n} W_j N_{j,s}$$
  *(Evaluates candidate strategies across loss avoided $L_{AS}$, implementation cost $C_s$, residual food deficit $RD$, and economic exposure $E_s$)*

---

## 📍 Pilot Validation: Kedah Paddy Granary (MADA)

FWise was modeled and stress-tested on **Kedah**—Malaysia's rice bowl (**228,963 ha** planted area; **947,621 tonnes** annual paddy production)—simulating a severe monsoon deluge and tidal lock event across **9,450 ha** of ripening paddy fields impacting **3,978 farming households**.

### Simulation Impact (Unmitigated Baseline vs. FWise `STRAT-5` Intervention)

| Impact Metric | Without FWise (Unmitigated) | With FWise (`STRAT-5` Action Plan) | Net Improvement |
| :--- | :---: | :---: | :---: |
| **Preparation Lead Time** | Reactive / Late | **4 – 6 Weeks** | Proactive mobilization |
| **Projected Crop Loss** | 21.7% | **7.8%** | **-13.9% loss avoided** |
| **Food Supply Deficit** | 4,500 tonnes | **829 tonnes** | **81.6% deficit reduction** |
| **Economic Exposure** | RM 21.80 Million | **RM 1.41 Million** | **RM 20.39M saved** |

---

## 🌏 Regional Scalability Roadmap (ASEAN Vision 2040)

* **Phase 1 (National Foundation — Malaysia):** Deploy FWise field stations across major granary zones, establish national data governance standards, and validate CRIS forecasting across states.
* **Phase 2 (Cross-Border Integration):** Connect FWise with ASEAN member states via standardized data-sharing protocols and regional disaster/crop monitoring exchanges.
* **Phase 3 (Regional Resilience Network):** Enable multi-country disruption simulations, regional stockpile coordination, and cross-border food logistics rerouting—working toward *"A climate-resilient ASEAN with sufficient, safe, and accessible food for all by 2040."*

---

## 🎯 UN SDGs & Regional Policy Alignment

* **SDG 2 — Zero Hunger** *(Targets 2.1, 2.3, 2.4)*: Safeguarding staple crop yields and smallholder farmer incomes against climate shocks.
* **SDG 11 — Sustainable Cities & Communities** *(Target 11.5)*: Reducing direct economic losses caused by flood and drought disasters.
* **SDG 12 — Responsible Consumption & Production** *(Target 12.3)*: Minimizing pre-harvest and post-harvest food losses across supply chains.
* **SDG 13 — Climate Action** *(Target 13.1)*: Strengthening adaptive capacity and multi-hazard early-warning infrastructure.
* **ASEAN Economic Community (AEC) Blueprint 2025** *(Characteristic 5.3.3)*: Ensuring integrated food security information across ASEAN.

---

## 📂 Repository Structure

```text
├── docs/
│   └── MALAYSIA_JJVISION_Presentation_slide.pdf   # Official ASEAN DSE 2026 Finalist Pitch Deck
├── analytics/
│   └── sac_storyboard_exports/                    # SAP Analytics Cloud (SAC) models & visualizations
├── cris_engine/
│   ├── risk_scoring.py                            # Climate anomaly & hazard risk scoring model
│   └── stress_test_simulator.py                   # Crop loss & multi-criteria strategy optimizer
├── hardware_specs/
│   └── field_station_bom.md                       # IoT Automatic Weather Station (AWS) architecture & BOM
└── README.md
