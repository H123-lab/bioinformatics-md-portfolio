# MD_simulations_hERG: Input Files

This folder contains input files required to run molecular dynamics (MD) simulations of the hERG potassium channel using **GROMACS**.

## 📂 File Descriptions

- `topol.top` – Topology file for the hERG-ligand complex
- `system.gro` – Initial coordinate file of the solvated system
- `ions.tpr` – Pre-processed input binary for ion replacement
- `minim.mdp` – Parameters for energy minimization
- `nvt.mdp` – Parameters for constant volume equilibration
- `npt.mdp` – Parameters for constant pressure equilibration
- `md.mdp` – Parameters for production MD run
- `posre.itp` – Position restraints for protein
- `index.ndx` – Index file for groups (e.g., protein, ligand, solvent)
- `ligand.itp` – Topology for the bound ligand

## 💡 Notes

- Ligand topology generated using **ACPYPE** or **CGenFF** depending on the derivative.
- Protein structure modeled using **AlphaFold2**, refined in **ChimeraX**.
- Protonation states optimized using **PDB2PQR** and **PROPKA** before simulation setup.
- System solvated in TIP3P water model, neutralized with Na⁺ and Cl⁻ ions.

## 🧪 Objective

These files enable the simulation of drug binding stability, electrostatics, and flexibility for hERG-drug complexes in your project on fluoroquinolone derivatives and cardiotoxicity.

This folder contains input files (e.g., topology, .gro, .mdp) for GROMACS MD simulation of hERG-drug complexes.
