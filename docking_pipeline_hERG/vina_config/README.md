# AutoDock Vina Docking Configuration for hERG-Ligand Complexes

This folder contains configuration files and settings used for performing molecular docking of fluoroquinolones and derivative compounds to the hERG channel using **AutoDock Vina**.

## 📂 File Descriptions

- `vina_config.txt` – Vina configuration file with grid center and box dimensions
- `ligand.pdbqt` – Ligand files (moxifloxacin, ciprofloxacin, levofloxacin, redesigned derivative)
- `receptor.pdbqt` – hERG channel prepared for docking
- `vina_run.sh` – Bash script to automate docking across ligands

## ⚙️ Configuration Highlights

- **Grid Center:** X=25.0, Y=17.2, Z=−4.5  
- **Box Size:** X=20, Y=20, Z=20  
- **Exhaustiveness:** 16  
- **Energy Range:** 3 kcal/mol  
- **Num Modes:** 10  

## 🔄 Workflow

1. Ligand structures optimized using **Avogadro** and converted with **OpenBabel**
2. Protein preparation done using **AutoDock Tools**
3. Docking run using the provided `.sh` script
4. Best scoring poses analyzed in **PyMOL** and **ChimeraX**

## 🧪 Objective

This pipeline enables comparison of docking affinities and interaction profiles between standard and redesigned fluoroquinolones in the hERG binding site.
