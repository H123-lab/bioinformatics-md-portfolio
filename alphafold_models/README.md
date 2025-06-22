# AlphaFold & RoseTTAFold Models of Cardiac Ion Channels

This folder hosts structure predictions and validation reports for cardiac ion-channel proteins and disease variants relevant to arrhythmia and cardiotoxicity research.

## 🗂️ Contents
| File / Subfolder | Description |
|------------------|-------------|
| `Kv11.1_AF2.pdb` | AlphaFold2 model of the hERG (Kv11.1) pore domain |
| `Nav1.5_variant_Q356P.pdb` | RoseTTAFold model of a pathogenic SCN5A variant |
| `model_quality/` | *plDDT* plots, predicted aligned error (PAE) heat-maps |
| `workflow_notes.md` | Command lines and parameters for local AlphaFold2 runs |

## 🛠️ Tools & Methods
- **AlphaFold2 (v2.3.2, GPU)** — full-length predictions with Amber relaxation.  
- **RoseTTAFold** — fast screening of >50 disease variants.  
- **ColabFold Batch** — for smaller subunits or quick iterations.  
- **QA Metrics:** plDDT, pTM, PAE; visual inspection in ChimeraX.

## 📌 Purpose
These models support mutation mapping, docking grid definition, and MD system preparation for cardiotoxicity studies. They also demonstrate my proficiency in state-of-the-art structure-prediction pipelines.

