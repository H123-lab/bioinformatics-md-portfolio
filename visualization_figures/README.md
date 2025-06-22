# Structural Visualization Figures (PyMOL / ChimeraX)

This folder contains all **publication-quality structural visualizations** generated for the hERG–drug binding study, including interaction analysis, electrostatic mapping, and binding pose comparison.

---

## 🔬 Tools Used

- **ChimeraX 1.9**
- **PyMOL 2.5**
- **APBS + PDB2PQR** (for electrostatic surface calculations)
- **LigPlot+ / PLIP** (for 2D interaction diagrams)

---

## 🖼️ Included Figures

### 1. hERG–Levofloxacin Complex (Panel C)
- **Pose:** Levofloxacin in binding pocket (green sticks)
- **Details:** Hydrogen bond with Ser624 (yellow dashes), VdW with Tyr652 & Phe656 (orange surface)
- **Surface:** Electrostatics (-5 to +5 kT/e), 50% transparency
- **Tool:** ChimeraX
- **File:** `levofloxacin_pose_hERG.png`

### 2. Redesigned Derivative–hERG Complex (Panel D)
- **Pose:** Derivative (gold sticks), reduced Tyr652 interaction, distance >4.5 Å to Phe656
- **Surface:** Lower positive charge in binding pocket
- **Tool:** ChimeraX
- **File:** `derivative_pose_hERG.png`

### 3. Docking Score Comparison (Figure 3A)
- **Content:** Bar graph of docking scores with chemical structures
- **Includes:** Moxifloxacin, Ciprofloxacin, Levofloxacin, Derivative
- **Tool:** Python (Matplotlib + RDKit), Adobe Illustrator
- **File:** `docking_score_comparison.png`

### 4. MD Snapshot (Figure 4A)
- **Content:** Most stable hERG–derivative binding conformation
- **Includes:** Labelled interactions and ligand positioning
- **Tool:** ChimeraX + GROMACS visualization
- **File:** `md_stable_snapshot.png`

---

## 🧰 Additional Notes

- **Color Coding:**
  - Ligands: Green (Levo), Gold (Derivative)
  - Hydrogen bonds: Yellow dashed lines
  - VdW contacts: Orange surface patches
  - Electrostatics: Blue (+5), Red (–5) in APBS map

- **Rendering Parameters:**
  - Cartoon-style protein
  - Surface transparency: 50%
  - White background
  - All labels for residues and distances included for publication use

---

## 📌 Purpose

This figure suite provides **visual support** for reduced cardiotoxic binding profiles of the redesigned derivative compared to fluoroquinolones in the hERG channel.

