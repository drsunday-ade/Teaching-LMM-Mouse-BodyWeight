# Teaching-LMM-Mouse-BodyWeight
# Teaching Longitudinal Linear Mixed Models End-to-End:
## A Reproducible Case Study in Mouse Body-Weight Growth

**Author:** Sunday Adetunji (drsunday-ade)  
**Core language:** R  
**Keywords:** linear mixed models, longitudinal data, teaching, reproducible analysis

---

## Overview

This repository contains a complete, reproducible teaching example for **longitudinal linear mixed models (LMMs)** using a classic **mouse body-weight growth** experiment.

It is designed so that:

- An **instructor** can walk through the analysis live in class.
- A **student** can clone the repo and re-run everything from **raw data → models → figures → tables** with a single R session.
- A **methods reader** can see a clean, fully transparent implementation of random-intercept LMMs, model comparison, contrasts, diagnostics, and sensitivity analyses.

The accompanying manuscript is titled:

> **“Teaching Longitudinal Linear Mixed Models End-to-End:  
> A Reproducible Case Study in Mouse Body-Weight Growth.”**

---

## Repository structure

```text
.
├─ data/
│  └─ BodyWeightData.xlsx
│
├─ R/
│  ├─ LMM_mouse_weight.R
│  ├─ LMM_mouse_weight_diagnostics.R
│  └─ LMM_mouse_weight_sensitivity.R
│
├─ analysis/
│  └─ LMM_mouse_weight_teaching.Rmd
│
├─ figs/
│  ├─ Figure1_profiles_means.png
│  ├─ Figure2_means_fitted.png
│  ├─ Figure3_differences_over_time.png
│  ├─ Figure4_12week_gain.png
│  ├─ Figure5a_resid_vs_fitted.png
│  ├─ Figure5b_resid_vs_time.png
│  ├─ Figure6a_qqplot_resid.png
│  └─ Figure6b_qqplot_random_intercepts.png
│
├─ tables/
│  ├─ Table1_fixed_effects.csv
│  ├─ TableA1_model_comparison.csv
│  ├─ TableA2_weekly_differences.csv
│  └─ TableA3_12week_gains.csv
│
├─ manuscript/
│  ├─ Teaching_LMM_Mouse_BodyWeight_manuscript.docx
│  └─ Supplementary_Materials.docx
│
├─ README.md
├─ LICENSE
├─ CITATION.cff
└─ Teaching-LMM-Mouse-BodyWeight.Rproj
