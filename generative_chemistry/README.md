# Generative Chemistry for Drug Discovery

This folder includes workflows and outputs from using AI-based models to generate novel compounds targeting cardiac proteins.

## 🧪 Tools Used
- **DeepChem** — Compound generation and activity prediction
- **RDKit** — Molecule structure generation, fingerprinting
- **AutoDock Vina** — Docking generated ligands to hERG/Nav1.5
- **MolGAN / ChemProp (planned)** — Testing graph-based generative models

## 🧾 Contents
| File/Subfolder | Description |
|----------------|-------------|
| `generated_ligands/` | SMILES + 3D conformers of AI-designed compounds |
| `toxicity_screening/` | Filtering via hERG, Lipinski, ADMET tools |
| `docking_scores.csv` | Comparative binding energy |
| `scripts/` | Python-based generation + scoring workflows |

## 💡 Skills Demonstrated
- AI-based compound design
- Integration with docking pipelines
- Toxicity filtering and ligand selection
