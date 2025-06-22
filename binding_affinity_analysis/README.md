# Binding Affinity Analysis

This folder includes data and scripts for analyzing and comparing ligand binding affinities across docking and MD methods.

## 🔬 Techniques Applied
- **AutoDock Vina scores** — Estimated binding energy from docking.
- **MM-PBSA (GROMACS g_mmpbsa)** — Post-MD binding free energy calculations.
- **Interaction Energy Decomposition** — van der Waals, electrostatics, solvation.

## 📁 Contents
| File/Subfolder | Description |
|----------------|-------------|
| `vina_docking_scores.csv` | Binding energy for each ligand |
| `mm_pbsa/` | Scripts + outputs from g_mmpbsa analysis |
| `energy_vs_time/` | RMSD-aligned ΔG vs simulation time plots |
| `replicates_summary/` | Mean ± SD of binding energies across repeats |

## 📊 Output Highlights
- Better binding predicted for derivative over fluoroquinolones
- Stability correlation from MD confirmed via MM-PBSA

## 💡 Skills Demonstrated
- Energy decomposition and analysis
- Time-resolved binding stability assessment
- Plotting and interpretation of affinity trends
