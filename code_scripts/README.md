# Code Scripts for MD Analysis & Docking Automation

This folder contains key scripts used throughout the project to automate tasks, run analyses, and generate plots related to MD simulations, docking, and structural bioinformatics.

---

## 🧪 MD Analysis Scripts (GROMACS + Python)

### 1. `rmsd_plot.py`
- **Description:** Plots RMSD of ligand and protein backbone over time
- **Input:** `.xvg` files from `gmx rms`
- **Output:** `rmsd_plot.png`
- **Libraries:** matplotlib, pandas

### 2. `rmsf_analysis.py`
- **Description:** Residue-level fluctuation plot (RMSF)
- **Input:** `.xvg` from `gmx rmsf`
- **Output:** `rmsf_plot.png`

### 3. `hbond_analysis.sh`
- **Description:** Bash script for extracting H-bond time series
- **Tool:** `gmx hbond`
- **Output:** `hbnum.xvg`, `hbmap.xpm`

---

## 🔁 Docking Automation Scripts

### 4. `vina_batch_docking.py`
- **Description:** Automates AutoDock Vina docking for multiple ligands
- **Inputs:** Ligand folder, receptor PDBQT, `config.txt`
- **Output:** Binding scores + poses (`out.pdbqt`)
- **Toolkits:** AutoDockTools, Open Babel

---

## 🧬 Structure Preparation

### 5. `pdb_cleaner.py`
- **Purpose:** Removes water, ions, and fixes missing atoms before docking/MD
- **Input:** Raw PDB
- **Output:** Cleaned PDB for modeling

### 6. `generate_topology.sh`
- **Tool:** GROMACS
- **Function:** Automates ligand topology generation with `acpype`

---

## 🖼️ Visualization Helpers

### 7. `plot_energy_terms.py`
- Plots potential energy, temperature, pressure over time
- Input: GROMACS energy `.xvg` files
- Output: Summary plot for system stability

---

## 💡 Notes

- **Languages Used:** Python, Bash
- **Dependencies:** BioPython, MDTraj, Matplotlib, NumPy, Pandas, GROMACS tools
- **Execution:** All Python scripts tested in conda env `bio-md`, Bash scripts in Ubuntu 22.04

---

## 📌 Purpose

This folder ensures reproducibility and supports open-access methodology by providing source code used in the study.

