# Molecular Docking & Computational Drug Repurposing for Alzheimer's Disease

## 📌 Project Overview
Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder characterized by abnormal protein aggregation, neurofibrillary tangle formation, and neuronal cell death.

This repository contains the computational workflow, structural data, and docking analysis evaluating the drug repurposing potential of **EF24** (a synthetic curcumin analog) against key target proteins in Alzheimer's disease: **Beta-Secretase 1 (BACE1)** and **Tau Protein**.

---

## 🎯 Target Proteins & Candidate Molecule
* **Target 1:** BACE1 (Beta-site APP Cleaving Enzyme 1)
* **Target 2:** Tau Protein (Microtubule-Associated Protein Tau)
* **Candidate Drug:** EF24 (Curcumin Analog)

---

## 🔬 Computational Methodology & Pipeline

```text
  [Biological Databases]
 (RCSB PDB, PubChem, DrugBank)
             │
             ▼
   [Structure Retrieval] ────────► Target Preparation (Clean PDB, remove waters)
             │
             ▼
   [Blind Molecular Docking] ───► Auto-pocket identification & energy score (CB-Dock)
             │
             ▼
   [Interaction Analysis] ────► 3D Conformation, Hydrogen Bonding & Residue Mapping (PyMOL)
