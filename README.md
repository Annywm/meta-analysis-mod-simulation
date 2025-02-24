# 🧪 Meta-Analysis Missing Outcome Data (MOD) Simulation

This repository contains R code to simulate the impact of **Missing Outcome Data (MOD)** in meta-analyses. The simulations explore how different MOD assumptions affect intervention effect estimates, using **Available Case Analysis (ACA)** and various **Sensitivity Analyses**.

---

## 📌 Overview

Missing outcome data in **randomized controlled trials (RCTs)** can bias meta-analysis results, especially when data are **Missing Not At Random (MNAR)**. This simulation study replicates key findings from the paper *Harris et al. (2021)* on lifestyle interventions during pregnancy and their effects on **postpartum weight retention (PPWR)**.

### **🛠 Methods**
1. **ACA (Available Case Analysis)**  
   - Assumes **Missing at Random (MAR)**.
   - Uses only complete cases to estimate intervention effects.

2. **Sensitivity Analyses:**
   - **Sensitivity I**: Assumes no difference between MOD and non-MOD participants.
   - **Sensitivity II**: Assumes **worse outcomes** for MOD participants in the intervention group.
   - **Sensitivity III**: Assumes **worse outcomes** for MOD participants in the control group.


