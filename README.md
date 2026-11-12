<!-- Animated Blue Wave Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:021B79,50:0575E6,100:00D2FF&height=220&section=header&text=FWise%20(FoodWise)&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Know%20Before.%20Act%20Before.%20%7C%20Climate-Resilient%20Food%20Intelligence&descAlignY=62&descSize=18" width="100%" />

  <!-- Animated Typing Subtitle -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00A8FF&center=true&vCenter=true&width=780&lines=ASEAN+Data+Science+Explorers+2026+%E2%80%94+Malaysia+National+Finalist;Turning+Climate+Information+into+Food+Security+Resilience;IoT+Field+Stations+%2B+CRIS+Predictive+Decision+Engine" alt="Typing SVG" />
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

Globally, **1 in 4 people (2.5 billion)** went without reliable access to sufficient food in 2025, while across ASEAN, **12.8% of the population (87.6 million people)** experienced moderate or severe food insecurity between 2023 and 2025 (with prevalence reaching **40.0%** in Cambodia, **35.6%** in Lao PDR, **32.9%** in the Philippines, **32.7%** in Myanmar, and **16.7%** in Malaysia).

In Malaysia, climate change acts as a **threat multiplier**—simultaneously activating production, water, supply-chain, and import vulnerabilities:

* 🌾 **Production & Pest Vulnerabilities:** Malaysia's rice Self-Sufficiency Ratio (SSR) fell to **52.9%** in 2024 as paddy output declined **5.3%** (from 2.18M to 2.06M tonnes). Other critical SSR deficits include mutton (**8.5%**), ginger (**15.5%**), beef (**16.8%**), and mango (**20.6%**). Biological threats like Brown Planthopper (up to **60%** rice loss) and Bacterial Panicle Blight (**50%** yield loss across 12,000+ ha) further compound crop risks.
* ❄️ **Post-Harvest & Infrastructure Fragility:** Severe lack of mobile cold-storage facilities, low-temperature warehouses, and temporary storage hubs accelerates post-harvest losses. In 2024, floods caused **RM303.4M** in public infrastructure damage and **RM54.1M** in business premises damage, disrupting food distribution.
* 📦 **Heavy Food Import Dependence:** Food imports jumped **19.1%** in 2024 to **RM93.8 billion**, with extreme Import Dependency Ratios (IDR) in mango (**116.7%**), apple (**100%**), garlic (**100%**), onion (**100%**), shallot (**99.9%**), mutton (**92.1%**), mushroom (**89.3%**), ginger (**86.9%**), and beef (**83.5%**). FAO projects Malaysia's 2026 paddy output at **2.1M tonnes** (-4.5% below the 5-year average), pushing 2026/27 cereal import needs to **7.9M tonnes** (+10% above average).
* ⛈️ **Escalating Flood Losses & Macro Risk:** Flood incidents surged **66.3%** from 2023 to 2024 (809 to 1,345 incidents), raising agricultural losses **53.5%** from **RM120.6M to RM185.2M** (including **RM158.7M** in Kedah paddy losses across 2,047 ha / 57,323 tonnes), followed by **RM52.6M** in 2025 across all states. A 10% food price spike drives **+3.5%** food insecurity and up to **+6.1%** severe child wasting, while the World Bank warns a 1-in-20-year flood could cost Malaysia **4.1% of GDP by 2030**.

### 🔍 Four Systemic Root Causes
1. **Fragmented Information:** Climate, hydrological, and agricultural datasets sit in isolated agency silos without a unified multi-hazard early-warning strategy.
2. **Critical Information Gaps:** **40%** of 143 critical climate and agricultural data items in Malaysia were unavailable, with only **18%** readily accessible.
3. **Prediction-Action Gap:** Existing forecasting struggles to translate raw weather warnings into localized, role-specific operational actions.
4. **Insufficient Resilience:** Weak recovery and adaptation leave the agrofood sector exposed to recurring shocks.

---

## 💡 System Architecture & Workflow

**FWise (FoodWise)** operates on a hybrid architecture combining **Automated Intelligence (CRIS)**, **User-Triggered Simulations**, and **Human Decision & Action**:

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#0077B6', 'primaryTextColor': '#ffffff', 'primaryBorderColor': '#03045E', 'lineColor': '#00B4D8', 'secondaryColor': '#CAF0F8', 'tertiaryColor': '#90E0EF'}}}%%
flowchart LR
    A["📡 FWise IoT Stations<br/>(14-Component AWS Array)"] -->|4G / LoRaWAN / Satellite| B["🔗 Integrated Data Hub<br/>(MET, JPS, MADA, DOA, DOSM)"]
    B --> C["🧠 CRIS AI Engine<br/>(Anomaly & Stress Testing)"]
    C --> D["⚖️ Strategy Planner<br/>(7-Criteria Ranking)"]
    D --> E["📱 Stakeholder App & Portal<br/>(Directives & Evidence Audit)"]
    
    style A fill:#03045E,stroke:#00B4D8,stroke-width:2px,color:#fff
    style B fill:#023E8A,stroke:#00B4D8,stroke-width:2px,color:#fff
    style C fill:#0077B6,stroke:#90E0EF,stroke-width:2px,color:#fff
    style D fill:#0096C7,stroke:#CAF0F8,stroke-width:2px,color:#fff
    style E fill:#00B4D8,stroke:#03045E,stroke-width:2px,color:#000
