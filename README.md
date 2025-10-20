# Molecular Docking Studies in Clinical Drug Design & Structural Bioinformatics

## Overview

This repository compiles comprehensive molecular docking studies performed across multiple research projects in Clinical Drug Design and Structural Bioinformatics. The analyses integrate computational modeling, virtual screening, ligand–protein interaction profiling, and binding affinity estimation for a variety of therapeutic and biological systems.

The primary goal is to explore drug–target interactions, structure–activity relationships, and mechanistic insights into molecular recognition processes — ultimately contributing to rational drug discovery and biological pathway elucidation.

---
## Research Domains
### 1. Clinical Drug Design

Focused on identifying and validating clinically relevant drug candidates using molecular docking and pharmacophore-based approaches.

🔹 Key Highlights

Objective: Discover potential lead compounds for bacterial and viral targets, guided by structure-based design.

Techniques Used:

Protein–ligand docking using AutoDock Vina, PyRx, and Discovery Studio.

Comparative analysis with FDA-approved drugs and phytocompounds.

Binding free energy calculations and interaction profiling (H-bonding, hydrophobic, electrostatic).

Examples of Studies:

Erythromycin and natural analogs docked against quorum-sensing and biofilm-related proteins in Pseudomonas aeruginosa.

Screening of phytochemicals from Premna serratifolia for anti-quorum-sensing activity.

Assessment of ADMET and drug-likeness using SwissADME and ProTox-II.

🧩 Outcome

Identification of promising drug–target pairs with high binding affinity (ΔG < -6 kcal/mol).

Structural rationale for enhanced inhibitory activity against microbial virulence pathways.

---

### 2. Structural Bioinformatics

This component emphasizes protein structure–function relationships, binding site prediction, and molecular recognition.

🔹 Key Highlights

Objective: Characterize the structural determinants governing ligand binding and stability.

Techniques Used:

Homology modeling using SWISS-MODEL and Phyre2.

Protein validation via Ramachandran plots (ProCheck) and ERRAT scores.

Active site prediction using CASTp and FTSite.

Docking simulations with AutoDockTools, PyMOL, and LigPlot+ visualization.

Examples of Studies:

Docking of natural ligands with 3D-modeled quorum-sensing proteins.

Comparative docking between wild-type and mutant protein structures.

Structural dynamics insights through post-docking visualization and interaction maps.

### Outcome

Identification of conserved residues critical for ligand anchoring.

Understanding of molecular conformational changes induced upon binding.

Structure-based refinement of target models for downstream simulations.

---

## ⚙️ Tools & Software Used

| **Category**              | **Software / Platform**                             |
|----------------------------|------------------------------------------------------|
| **Docking**                | AutoDock Vina, PyRx, Discovery Studio               |
| **Visualization**          | PyMOL, Chimera, LigPlot+, BIOVIA Visualizer         |
| **Modeling**               | SWISS-MODEL, Phyre2                                |
| **Binding Site Prediction**| CASTp, FTSite                                       |
| **ADMET Profiling**        | SwissADME, ProTox-II                                |
| **Data Analysis**          | Python, Pandas, Matplotlib, Excel                   |

---

## Methodological Workflow

Target Identification → Literature & PDB screening

Ligand Selection → Natural compounds, clinical drugs, or designed analogs

Protein Preparation → Removal of water, addition of polar hydrogens, and charge assignment

Docking Simulation → Grid box optimization and flexible docking

Result Analysis → Binding energy, inhibition constant, and interaction map generation

ADMET Evaluation → Pharmacokinetic and toxicity profiling
Binding Site Prediction	CASTp, FTSite
ADMET Profiling	SwissADME, ProTox-II
Data Analysis	Python, Pandas, Matplotlib, Excel
