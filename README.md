<!-- Animated Blue Wave Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:021B79,50:0575E6,100:00D2FF&height=220&section=header&text=FWise%20(FoodWise)&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Know%20Before.%20Act%20Before.%20%7C%20Climate-Resilient%20Food%20Intelligence&descAlignY=62&descSize=18" width="100%" />

  <!-- Animated Typing Subtitle -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00A8FF&center=true&vCenter=true&width=750&lines=ASEAN+Data+Science+Explorers+2026+%E2%80%94+Malaysia+National+Finalist;Turning+Climate+Information+into+Food+Security+Resilience;IoT+Field+Stations+%2B+CRIS+Predictive+Decision+Engine" alt="Typing SVG" />
  </a>

  <br/>

  <!-- Blue-Themed Badges -->
  <p>
    <img src="https://img.shields.io/badge/ASEAN_DSE_2026-Malaysia_National_Finalist-0052CC?style=for-the-badge&logo=sap&logoColor=white" alt="ASEAN DSE 2026" />
    <img src="https://img.shields.io/badge/Team-JJ_Vision-0077B6?style=for-the-badge&logo=microsoftteams&logoColor=white" alt="Team JJ Vision" />
    <img src="https://img.shields.io/badge/UTM-Universiti_Teknologi_Malaysia-03045E?style=for-the-badge" alt="UTM" />
    <img src="https://img.shields.io/badge/Powered_By-SAP_Analytics_Cloud-00B4D8?style=for-the-badge&logo=sap&logoColor=white" alt="SAC" />
  </p>
</div>

---

## 🏆 Competition Recognition

<table>
  <tr>
    <td width="50%">
      <h3>🇲🇾 Malaysia National Finalist</h3>
      <b>Event:</b> ASEAN Data Science Explorers (ASEAN DSE) 2026<br/>
      <b>Organizers:</b> ASEAN Foundation & SAP<br/>
      <b>Institution:</b> Universiti Teknologi Malaysia (UTM)
    </td>
    <td width="50%">
      <h3>👥 Team JJ Vision</h3>
      <ul>
        <li><b>Tan Jia Wei</b></li>
        <li><b>Wong Jun Xiang</b></li>
      </ul>
      <i>"How can we turn climate information into food security resilience?"</i>
    </td>
  </tr>
</table>

---

## 🌊 The Problem & Systemic Root Causes

Across ASEAN, **12.8% of the population (87.6 million people)** experienced moderate or severe food insecurity between 2023 and 2025[cite: 3]. In Malaysia, climate change acts as a **threat multiplier**—triggering floods, erratic rainfall, and droughts that simultaneously disrupt an already vulnerable food system[cite: 9]:

* 🌾 **Baseline Production Vulnerabilities:** Malaysia's rice Self-Sufficiency Ratio (SSR) dropped to **52.9%** in 2024, while paddy production fell **5.3%** (to 2.06M tonnes)[cite: 6].
* 📦 **High Import Dependence:** Malaysia spent **RM93.8 billion** on food imports in 2024 (+19.1% YoY), with heavy reliance on imports for staples like onions (100%), garlic (100%), beef (83.5%), and mutton (92.1%)[cite: 8].
* ⛈️ **Escalating Flood Impacts:** Flood incidents surged **66.3%** from 2023 to 2024 (809 to 1,345 incidents), driving agricultural losses up **53.5%** to **RM185.2 million** (including RM158.7M in Kedah paddy losses alone)[cite: 13, 58].

### 🔍 Four Systemic Root Causes
1. **Fragmented Information:** Hazard, hydrological, and agricultural datasets exist in isolated agency silos[cite: 14].
2. **Critical Information Gaps:** **40%** of 143 essential climate/agricultural data items in Malaysia were unavailable, with only **18%** readily accessible[cite: 17].
3. **Prediction-Action Gap:** Existing early-warning systems fail to translate raw meteorological alerts into localized, role-specific operational steps[cite: 15].
4. **Insufficient Resilience:** Delayed coordination creates recurring supply chain bottlenecks and severe economic exposure[cite: 16].

---

## 💡 System Architecture & Workflow

**FWise (FoodWise)** connects ground-level IoT telemetry with multi-agency decision intelligence[cite: 20, 40]:

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#0077B6', 'primaryTextColor': '#ffffff', 'primaryBorderColor': '#03045E', 'lineColor': '#00B4D8', 'secondaryColor': '#CAF0F8', 'tertiaryColor': '#90E0EF'}}}%%
flowchart LR
    A["📡 FWise IoT Stations<br/>(Weather, Soil, Water Level)"] -->|4G / LoRaWAN| B["🔗 Integrated Data Hub<br/>(MET, JPS, MADA, DOA, DOSM)"]
    B --> C["🧠 CRIS AI Engine<br/>(Anomaly Detection & Stress Test)"]
    C --> D["⚖️ Strategy Optimizer<br/>(Multi-Criteria Ranking)"]
    D --> E["📱 Stakeholder Portal<br/>(Directives & Evidence Tracking)"]
    
    style A fill:#03045E,stroke:#00B4D8,stroke-width:2px,color:#fff
    style B fill:#023E8A,stroke:#00B4D8,stroke-width:2px,color:#fff
    style C fill:#0077B6,stroke:#90E0EF,stroke-width:2px,color:#fff
    style D fill:#0096C7,stroke:#CAF0F8,stroke-width:2px,color:#fff
    style E fill:#00B4D8,stroke:#03045E,stroke-width:2px,color:#000
