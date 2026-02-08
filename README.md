# Voxel-based ADC Analysis for Outcome Prediction in Status Epilepticus

This repository contains the data and R code used in the study:

"Automated whole-brain voxel-based apparent diffusion coefficient (ADC) analysis for outcome prediction in status epilepticus."

The purpose of this repository is to enhance transparency, reproducibility, and methodological clarity of the analyses presented in the manuscript.

---

## Contents

- R scripts for:
  - Calculation of whole-brain voxel-based ADC metrics
  - Classification of DWI/ADC voxel patterns
- A de-identified clinical dataset provided in Excel format

---

## File Structure

---

## Data Description

The Excel file (`raw_data_up.xlsx`) contains fully de-identified clinical and imaging-derived variables used in the analysis, including:

- Demographic variables (e.g., age, sex)
- Clinical characteristics (e.g., GCS, EEG severity, seizure semiology, etiology)
- Imaging-derived metrics (e.g., normal ADC ratio)
- Outcome variables

All patient identifiers have been removed, and no information permitting re-identification is included.

---

## Reproducibility

All analyses reported in the manuscript can be reproduced using the provided R code and dataset.  
The main analysis pipeline is described in the R script file and follows the methodology outlined in the manuscript.

---

## Ethical Considerations

Due to ethical and privacy considerations, only de-identified data are shared.  
No raw neuroimaging files (e.g., DICOM or NIfTI) are included in this repository.

---

## Contact

For questions regarding the code or analysis, please contact the corresponding author.
