# Cryo-EM Data Processing of Cardiac Proteins

This folder documents cryo-electron microscopy (cryo-EM) processing workflows applied to cardiac ion channels and signaling complexes.

## 🗂️ Contents
| File/Subfolder | Description |
|----------------|-------------|
| `relion_project/` | RELION workflow files: motion correction, CTF estimation, particle extraction |
| `cryosparc_sessions/` | CryoSPARC refinement jobs and classification sessions |
| `fsc_plots/` | Fourier Shell Correlation curves for resolution validation |
| `workflow_scripts.md` | Notes and command-line logs for GPU-accelerated runs |

## 🛠️ Tools & Software
- **RELION (v4.0)** — used for motion correction (MotionCor2), CTF estimation (CTFFIND4), auto-picking, 2D/3D classification, and map refinement.  
- **CryoSPARC (v4.2)** — heterogeneous refinement, non-uniform refinement, local resolution maps.  
- **EMRinger & Phenix** — validation of atomic models against maps.  
- **ChimeraX** — visualization of cryo-EM densities and fitted atomic models.

## 🧪 Example Projects
- **RyR2 Cryo-EM Map (3.6Å)** — native channel in closed state.  
- **Nav1.5 β-subunit complex (4.2Å)** — under detergent-free nanodisc prep.  
- **IL-1β neutralizing antibody** — for immunomodulation in cardiac inflammation.

## 📌 Skills Demonstrated
- End-to-end cryo-EM pipeline execution  
- GPU-accelerated reconstruction and model validation  
- Map-to-model fitting and figure generation  
- Documentation of cryo-EM job parameters for reproducibility

