# RFID — UHF Real-Time Location System

Notebook-based investigation of **RFID tag localization** using UHF RSSI measurements.

## Objective

Estimate a tag's 3D coordinates `(x, y, z)` using measurements from **four antennas** across **three transmission powers (24, 27, and 30 dBm)**. The notebook explores feature engineering, predictive targets, model comparisons, late fusion across powers, and error analysis.

## Repository contents

- [RFID_SamyTALEB_SalimKISMA.ipynb](RFID_SamyTALEB_SalimKISMA.ipynb) — experimental analysis and code
- [RFID.pdf](RFID.pdf) — accompanying PDF document

## Methodology

The notebook examines direct coordinate prediction, distance estimation, multi-output regression, spatial error maps, and calibration ideas. Read the notebook's introduction for the full experiment design.

## Reproduction

The notebook was authored with **Google Colab** and references data stored in a Google Drive directory. Those input files and paths must be configured in your own environment before running it. Core Python libraries used include NumPy, pandas, Matplotlib and scikit-learn.

No claims about final localization accuracy are made in this README; consult the notebook and report for experimental results.

## Dataset availability and reproducibility

The **measurement data are not included** in this public repository. The notebook references a Google Colab / Google Drive directory structure, so running all cells requires adapting these paths and obtaining the relevant data through an authorized source. The report and notebook can still be read without those files.

For a fully reproducible public demonstration, a future enhancement would be a small **synthetic sample dataset** (clearly labeled as synthetic), a dependency manifest and documented metrics. Do not upload identifiable raw measurements or restricted datasets.
