# 📘 Stata Regression Analysis Summary: Panel Data (1993–2023)

This document summarises the econometric analysis performed in **Stata 17** as part of my master’s thesis. The focus was to assess how economic sanctions in 2014 and 2022 affected the cross-border banking exposure of 14 Western countries to Russia, using quarterly panel data from 1993 to 2023.

---

## 🧩 Dataset Structure

- **Panel ID**: `country`
- **Time Variable**: `date` (quarterly)
- **Dependent Variable**: `claims` – Cross-border claims on Russian banks (USD millions)
- **Key Explanatory Variables**:
  - `sanctions_2014`: Dummy variable (1 from 2014 Q1 onwards)
  - `sanctions_2022`: Dummy variable (1 from 2022 Q1 onwards)
  - `inflation`: Country-level inflation rate (control)

---

## 🧪 Modelling Approach

1. **Pooled OLS**
   ```stata
   reg claims inflation sanctions_2014 sanctions_2022
