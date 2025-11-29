# Home-Assignment

This is a repository of a home assignment for Programming for Psychologists 2025.

**Author:** Mohammadparsa (Parsa)  

**Date:** *29/11/2025*  
  
Neurosynth link: *https://neurosynth.org/analyses/terms/episodic%20memory/*
---

## Project Description
This project analyzes brain activity related to episodic memory using the anatomical and functional maps downloaded from **Neurosynth**. The functional maps are overlaid on anatomical MRI scans to visualize activation distribution and extract voxel intensity information. The goal is to explore activation characteristics, develop reproducible analysis code, and practice proper scientific documentation and version control.

---

## Table of Contents

| Section | Description |
|---------|-------------|
| **Data** | The files that are used for the data -> episodic memory_uniformity-test_z_FDR_0.01.nii.gz and anatomical.nii.gz  |
| **Codes-for-HA.ipynb** | The main notebook that loads, visualizes, and analyzes the MRI data. |
| **README.md** | This file, describing the project and structure. ||



---

## Notebook Content Overview

1. **Imports and setup**  
2. **Automatic file detection**  
3. **Loading MRI data**  
4. **Visualization of functional data ontop of the anatomical scan**
5. **Histogram of Functional Data**  


---

## Python Packages Used

- `nibabel`
- `numpy`
- `matplotlib`
- `glob`
- `os`
- `nilearn`
