# Home-Assignment

This is a repository of a home assignment for Programming for Psychologists 2025.

**Author:** Mohammadparsa (Parsa)  

**Date:** *29/11/2025*  
  

---

## Project Description
This project analyzes brain activity related to episodic memory using the anatomical and functional maps downloaded from **Neurosynth**. The functional maps are overlaid on anatomical MRI scans to visualize activation distribution and extract voxel intensity information. The goal is to explore activation characteristics, develop reproducible analysis code, and practice proper scientific documentation and version control.

---

## Table of Contents

| Section | Description |
|---------|-------------|
| **data** | An automated meta-analysis of 332 episodic memory studies conducted from Neurosynth: *https://neurosynth.org/analyses/terms/episodic%20memory/* |
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
