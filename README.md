# ⚙️ EAF Digital Twin (Mass & Energy Model)

A simplified **Electric Arc Furnace (EAF) digital twin** built to model and analyze  
mass flows, energy consumption, and process performance in steelmaking.

---

## 🚀 Overview

This model combines **first principles thermodynamics** with **industrial operating assumptions** to simulate:

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
  - Energy consistent via normalization  

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
- -  Electric arc furnace slag as natural aggregate replacement in concrete production. Saveria Monosi, Maria Letizia Ruello*, Daniela Sani.
- The potential of industrial waste: Electric arc furnace slag (EAF) as recycled road construction materials. Patimapon Sukmak a, Gampanart Sukmak a, Pre DeSilva b, Suksun Horpibulsuk.
- A critical analysis of electric arc furnace (EAF) slag for sustainable geopolymer concrete production. Kamal Kishore , M. Neaz Sheikh , Muhammad N.S. Hadi
- A Review of Electric arc Furnace Dust (EAFD) Reuse and Recycle Methods. Zahra Khebri1,2 · Zahra Razavi3 · Fatemeh Sadeghian2 · Fahimeh Faqhihi2 ·
- Pyrometallurgical recovery of zinc and valuable metals from electric arc furnace dust. Jie Wang a, Yingyi Zhang a, b, *, Kunkun Cui a, Tao Fu a, Jianjun Gao c, Shahid Hussain.
- Hydrometallurgical Processes for the Recovery of Metals from Steel Industry By‑Products. Koen Binnemans1 · Peter Tom Jones2 · Álvaro Manjón Fernández3, Victoria Masaguer Torres3.
- Waste heat recovery technologies and applications. Hussam Jouhara⁎, Navid Khordehgah, Sulaiman Almahmoud
- Heat recovery from EAF off-gas for steam generation. K. Gandt, T. Meier, T. Echterhof∗ and H. Pfeifer.
- Off-Gas Waste Heat Recovery for Electric Arc Furnace Steelmaking Using Calcium Hydroxide (Ca(OH)2) Dehydration. Georg Hartfuß,* Max Schmid, and Günter Scheffknecht.

