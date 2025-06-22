# Molecular Dynamics Analysis Results for hERG-Ligand Complexes

This folder contains post-simulation analyses of MD trajectories performed using **GROMACS**. These results provide insight into the stability, flexibility, and interactions of ligand-hERG complexes.

## 📊 Included Analyses

### 1. Root Mean Square Deviation (RMSD)
- **File:** `rmsd.xvg`
- Used to assess structural stability of the protein-ligand complex over time.

### 2. Root Mean Square Fluctuation (RMSF)
- **File:** `rmsf.xvg`
- Indicates residue-level flexibility throughout the simulation.

### 3. Radius of Gyration (Rg)
- **File:** `rgyr.xvg`
- Measures the compactness of the protein structure.

### 4. Hydrogen Bond Analysis
- **File:** `hbnum.xvg`
- Number of hydrogen bonds between ligand and hERG during simulation.

### 5. Interaction Energy Profiles
- **File:** `interaction_energy.xvg`
- Non-bonded interaction energy (Coulomb + LJ) between ligand and protein.

### 6. Stability Snapshots
- **Images:** `snapshot_0ns.png`, `snapshot_20ns.png`, `snapshot_50ns.png`
- Key structural states visualized using PyMOL/ChimeraX.

---

## 🧬 Tools & Scripts Used

- `gmx rms`, `gmx rmsf`, `gmx gyrate`, `gmx hbond`, `gmx energy`
- Plotting performed using **Grace**, **Matplotlib**, and **Seaborn**

---

## 🔍 Objective

These analyses validate the binding stability and interaction profile of the redesigned derivative versus fluoroquinolones in the hERG pocket, supporting reduced cardiotoxic potential.

