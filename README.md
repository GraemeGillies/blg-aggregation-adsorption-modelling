# Collision efficiency extraction for β‑lactoglobulin aggregation

**Author:** Graeme Gillies  
**Affiliation:** Fonterra Research and Development Centre  
**Contact:** graeme.gillies@fonterra.com  

This notebook reproduces the calculations described in:  
"A kinetic framework for β‑lactoglobulin disappearance in heated milk systems"

> Note: The code is written to follow the associated article closely and is not optimised for runtime.

---

## What this notebook does

This notebook models how β‑lactoglobulin behaves during heating in milk systems.

It combines:
- thermodynamics (protein unfolding)
- aggregation kinetics (cluster formation)
- adsorption (interaction with casein micelles)

The main goal is to:
estimate the **collision efficiency (W)** governing protein aggregation

---

## Who this is for

This notebook is designed for:
- scientists interested in milk protein behaviour
- users with little or no coding experience
- anyone who wants to reproduce or explore the model

You do **not** need to install software or know programming.

---

## How to run this (step-by-step)


1. Open the file: https://github.com/GraemeGillies/blg-aggregation-adsorption-modelling/blob/main/Gillies_2026_IntDairyJ_blg_kinetics.ipynb
2.  click the button 'open in colab', the button is right above the text "Collision efficiency extraction for β‑lactoglobulin aggregation"
3. Click:   **Runtime → Run all**
4. Wait for all cells to execute (this may take a few minutes)

---

## What you will see

The notebook will:

1. Load experimental data from literature  
2. Fit thermodynamic models (protein unfolding)  
3. Simulate aggregation behaviour  
4. Compare model predictions with experimental data  

Outputs include:
- plots of unfolding vs temperature  
- aggregation kinetics vs time  
- adsorption behaviour in milk systems  
- model vs experimental comparisons  
- text download of the adsorption-aggregation model results
---

## How the model works (simple explanation)

The model combines three key processes:

### 1. Unfolding
Protein unfolds as temperature increases  
→ this determines how much reactive protein is available

### 2. Aggregation
Proteins collide and stick together to form clusters  
→ controlled by the **collision efficiency (W)**

### 3. Adsorption (optional)
Proteins bind to casein micelles  
→ reduces protein available in solution

An additional optional pathway includes:
- κ-casein interactions (competitive binding)

---

## Changing inputs (optional)

If you want to explore different conditions:

Look for sections labelled:
- `SELECT DATASET`
- `SELECT CONDITION`
- `CONTROL PANEL`

You can change:
- temperature
- protein concentrations
- collision efficiency parameters
- adsorption behaviour

Then re-run:
**Runtime → Run all**

---

## Notes

- The notebook runs entirely in the cloud (Google Colab)
- No installation is required
- If something breaks, use:
  **Runtime → Restart and run all**

---

## Citation

If you use this work, please cite:

"A kinetic framework for β‑lactoglobulin disappearance in heated milk systems"

---

## Contact

For questions or issues:
graeme.gillies@fonterra.com
