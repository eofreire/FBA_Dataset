# FBA Gesture Elicitation Dataset (CSV)

This repository provides the cleaned and filtered dataset used in:

**Freire et al., “Beyond Agreement: A Functional Framework for Gesture Metrics in Repeated Elicitation Studies,” ACM TOCHI, 2025 (under review).**

The file `FBA_dataset.csv` contains the full set of gesture proposals from the **Frustration-Based Approach (FBA)** elicitation study, formatted to support metric computation and reproducibility.

---

## 📁 File Description

### **`FBA_dataset.csv`**
A comma-separated file with **three columns**, each representing an integer identifier.

| Column        | Meaning |
|---------------|---------|
| **`Referent`** | The referent ID associated with the gesture. This dataset includes *six* referents (IDs 1–6), as described in the paper after filtering out *Pointing*. |
| **`Participant`** | Participant ID (1–72). Each number corresponds to a unique study participant. |
| **`GestureID`** | Identifier of the unique gesture type assigned by expert reviewers. These IDs group multiple gesture proposals into a single canonical gesture class. |

Each row corresponds to a single gesture instance performed by a participant for a specific referent.

---

## ▶️ Processing and Reproducing Our Analyses

The scripts used to compute all **individual-gesture** and **vocabulary-level** metrics (e.g., GOR, VOR, CDR, ORT, AR*, CGR, τ₀) are *not* included here.

They are available in a separate repository:

👉 **https://github.com/eofreire/hri-metrics**

That repository contains:
- the full set of Octave/MATLAB `.m` files  
- the metric implementations  
- the main driver script to compute all outputs  
- instructions for running the analysis

---

## 📚 Citation

If you use this dataset, please cite:

Freire, E. O., Carvalho, J. G. N., Molina, L., Carvalho, E. A. N., Tavares, B. T., Valença, T. S. F., & Givigi, S. N.
Beyond Agreement: A Functional Framework for Gesture Metrics in Repeated Elicitation Studies. ACM TOCHI, 2025 (under review).
