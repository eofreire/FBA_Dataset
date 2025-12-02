# FBA Gesture Elicitation Dataset (CSV)

This repository provides the processed dataset used in the paper:

**Freire, E. O., Carvalho, J. G. N., Molina, L., Carvalho, E. A. N., Tavares, B. T., Valença, T. S. F., & Givigi, S. N. (2025). _Beyond Agreement: A Functional Framework for Gesture Metrics in Repeated Elicitation Studies_ (submitted to ACM TOCHI).**

> NOTE: The CSV available here (`FBA_dataset.csv`) is the cleaned and filtered version used in the 2025 TOCHI submission.  
> It contains **six referents (IDs 1–6)** because the referent *Pointing* was intentionally excluded from the analyses.  
>  
> The dataset was originally created (with seven referents, including *Pointing*) and first published in:

Canuto, C., Freire, E. O., Molina, L., Carvalho, E. A., & Givigi, S. N. (2022).  
*Intuitiveness Level: Frustration-Based Methodology for Human–Robot Interaction Gesture Elicitation.*  
IEEE Access, 10, 17145–17154.

---

## 📁 Files Included

### `FBA_dataset.csv`
Processed dataset used in the TOCHI submission.  
Each row represents *one gesture instance* produced by a participant for a given referent.

### `LICENSE`
Dataset license (CC0-1.0 Universal).

### `README.md`
This documentation file.

---

## 📊 CSV Format (Columns)

| Column | Type | Description |
|--------|------|-------------|
| **Referent** | integer | Referent ID used in the TOCHI analyses (1–6). |
| **Participant** | integer | Participant ID (1–72). Each integer corresponds to one participant. |
| **GestureID** | integer | Canonical gesture class assigned by expert reviewers. |

Each row = a gesture proposal for a referent from a specific participant.

---

## ▶️ Reproducing All Analyses

The scripts used to compute gesture and vocabulary metrics are **not included in this dataset repository**.

They are available here:

👉 https://github.com/eofreire/hri-metrics

That repository contains:
- Octave/MATLAB implementations of all metrics  
- The main driver scripts  
- Supplementary material for both datasets  
- Instructions for reproducing all results from the TOCHI submission  

---

## 🔐 Ethical Use & Privacy Notice

- The original FBA study (with seven referents) was conducted under approved ethical procedures.  
- All participant data in this CSV is **fully anonymized**.  
- No personal identifiers or video data are distributed.  
- Users must follow their institution’s guidelines for secondary data use.

---

## 📚 How to Cite This Dataset

If you use this dataset, **please cite BOTH** the TOCHI submission AND the original FBA study.

### 1. TOCHI submission (dataset version used here)

@article{freire2025beyond,
title = {Beyond Agreement: A Functional Framework for Gesture Metrics in Repeated Elicitation Studies},
author = {Freire, Eduardo O. and Carvalho, Jos{'e} G. N. de and Molina, Lucas and Carvalho, Elyson A. N. and Tavares, Beatriz T. and Valen{\c{c}}a, Thauanne S. F. and Givigi, Sidney N.},
year = {2025},
note = {Manuscript submitted to ACM TOCHI}
}

### 2. Original dataset publication (full 7-referent dataset)

@article{canuto2022intuitiveness,
title = {Intuitiveness Level: Frustration-Based Methodology for Human–Robot Interaction Gesture Elicitation},
author = {Canuto, Clebeson and Freire, Eduardo O. and Molina, Lucas and Carvalho, Elyson A.~N. and Givigi, Sidney N.},
journal = {IEEE Access},
volume = {10},
pages = {17145–17154},
year = {2022},
publisher = {IEEE}
}

---

## 📄 License

This dataset is released under the **CC0 1.0 Universal (Public Domain Dedication)**.  
You may use, modify, and redistribute it freely. Attribution is appreciated but not required.

---

## 📬 Contact

**Eduardo O. Freire**  
Federal University of Sergipe (UFS), Brazil  
Email: efreire@academico.ufs.br