# ⚙️ EAF Digital Twin (Mass & Energy Model)

A simplified **Electric Arc Furnace (EAF) digital twin** built to model and analyze  
mass flows, energy consumption, and process performance in steelmaking.

---

## 🚀 Overview

This model combines **first-principles thermodynamics** with **industrial operating assumptions** to simulate:

- Mass balance (steel, slag, dust, losses)
- Energy balance (sensible, latent, net energy)
- Off-gas energy and recovery potential
- Time-based furnace power profile
- Scenario analysis for process optimization

---

## 🧠 Key Features

- 🔹 **Mass Balance**
  - Scrap → Steel, Slag, Dust, Losses  
  - Zn in dust, FeO in slag tracking  

- 🔹 **Energy Model**
  - Sensible + latent heat calculations  
  - Electrical efficiency & oxygen credit  
  - Net energy (E_net) estimation  

- 🔹 **Dynamic Heat Profile**
  - Time-dependent power (melting, refining, final heating)  
  - Energy-consistent via normalization  

- 🔹 **Scenario Analysis**
  - Base case vs improved efficiency  
  - Scrap preheating  
  - Dust reduction impact  

- 🔹 **KPIs**
  - Specific Energy Consumption (SEC)  
  - Power demand (MW)  
  - Cost per heat (€)  
  - CO₂ emissions  
  - Steel yield (%)  

---

## 📊 Model Validation

Model outputs are benchmarked against industrial EAF ranges:

| Parameter | Typical Range |
|----------|--------------|
| SEC | 350–450 kWh/t |
| Slag | 100–150 kg/t |
| Dust | 10–20 kg/t |
| Yield | 90–95% |

The model results fall within these ranges, indicating realistic furnace behavior.

---

## ⚡ Core Concept

The model enforces:

- Mass conservation  
- Energy balance  
- Time-integrated power consistency  

\[
E = \int P(t)\,dt
\]

---

## 🛠️ Tech Stack

- Python  
- NumPy  
- Pandas  
- Plotly (Sankey visualization)

---

## 📌 Notes

- This is a **Level 1 digital twin** (lumped parameter model)  
- Designed for:
  - Process understanding  
  - Scenario comparison  
  - Educational / portfolio use  

---

## 📚 References

- AIST – Electric Arc Furnace Efficiency  
- Sameeeksha – COMPENDIUM- ENERGY EFFICIENT, TECHNOLOGY PACKAGES FOR ELECTRIC ARC FURNACE

