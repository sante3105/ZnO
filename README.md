# ZnO Dosimetry Analysis

This repository contains the experimental data analysis workflow for zinc oxide, ZnO, and doped ZnO samples studied as potential thermoluminescent materials for radiation dosimetry applications.

The project focuses on organizing, processing, and analyzing characterization data obtained from synthesized ZnO based materials. The main goal is to evaluate how synthesis conditions and dopants affect the structural, optical, morphological, and possible dosimetric properties of the samples.

## Project Description

Zinc oxide is a wide band gap semiconductor with relevant optical, structural, and luminescent properties. In the context of radiation dosimetry, ZnO is interesting because its defect structure can store energy after irradiation and release it as light during thermal stimulation.

This project explores the analysis of ZnO and doped ZnO samples using experimental characterization techniques such as X ray diffraction, Raman spectroscopy, UV Vis absorbance, SEM EDX, and thermoluminescence measurements.

The repository is intended to keep a reproducible and organized workflow for:

* Processing raw experimental data.
* Cleaning and preparing spectra.
* Comparing undoped and doped samples.
* Identifying structural and optical changes.
* Extracting physical parameters from characterization data.
* Generating plots and reports for laboratory documentation.

## Techniques Included

The analysis may include data from the following experimental techniques:

* X ray diffraction, XRD.
* Raman spectroscopy.
* UV Vis absorbance spectroscopy.
* Scanning electron microscopy, SEM.
* Energy dispersive X ray spectroscopy, EDX.
* Thermoluminescence, TL.

## Research Context

The project is motivated by the use of ZnO based materials as possible thermoluminescent dosimeters. Doping can modify the defect structure of ZnO by introducing new trap levels or recombination centers, which may improve the thermoluminescent response, dose linearity, stability, and sensitivity.

In this work, the analysis is oriented toward understanding whether the synthesized samples show structural and optical features compatible with future dosimetric applications.

## Repository Structure

```text
zno-dosimetry-analysis/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── references/
│
├── notebooks/
│   ├── xrd_analysis.ipynb
│   ├── raman_analysis.ipynb
│   ├── uv_vis_analysis.ipynb
│   ├── sem_edx_analysis.ipynb
│   └── tl_analysis.ipynb
│
├── src/
│   ├── data_loading.py
│   ├── preprocessing.py
│   ├── plotting.py
│   ├── xrd_tools.py
│   ├── raman_tools.py
│   ├── uv_vis_tools.py
│   └── tl_tools.py
│
├── results/
│   ├── figures/
│   ├── tables/
│   └── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
