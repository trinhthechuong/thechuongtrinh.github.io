---
title: "Molecular Docking"
collection: teaching
type: "Internal training"
permalink: /teaching/2023-MolecularDocking-labhhc
venue: "University of Medicine and Pharmacy at Ho Chi Minh city, Department of Organic Chemistry"
date: 2023-06-02
location: "City, Country"
---

This is a set of two (2+) tutorials on basic information of molecular docking incoporating python framework, using the **Google Colab** free cloud-computing environment in **Fall 2022**.



## Introduction

These tutorials were created between Aug-Dec 2022 as part of the **MedAI Training Session 2** for full execution over Google Colab and remote accesibility via web browsers.
Each tutorial includes a brief introduction of the activities to be performed, installation instructions of the open-source software to be used in each session and several programming, visualization and data analysis activities to be achieved during the tutorial. 

After this training session, you will know:
- Install virtual environment con google colab with Miniconda
- Install fundamental packages for simple docking
- Get protein from RSCB and split ligand
- Visualization with py3dmol
- Add hydrogen and gasteiger to protein and ligand
- Conduct molecular docking using smina and quick vina 2
- Advance docking: blind docking, flexible docking and customize scoring functions
- Docking results analysis: indentify interaction and calculate RMSD (redocking)
- Retrospective control analysis (update...)

## Description of the Tutorials

The following is a brief description of each tutorial, along with the open-source software used for each task:

| Tutorial | Description                           | Software                                                        |
|--------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Lab.01 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TieuLongPhan/TieuLongPhan.github.io/blob/master/_teaching/Material/Molecular%20Docking/lab01-Basic_docking.ipynb) | Install software, ligand and receptor reparation, simple docking                         |    Miniconda, Obabel, py3dmol, RDKit, smina, qvina2, mgltools 1.5.7                                                                                                      |
| Lab.02 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TieuLongPhan/TieuLongPhan.github.io/blob/master/_teaching/Material/Molecular%20Docking/lab02-Advance_docking.ipynb) | Docking Analysis and advance docking including blind docking, flexible docking and scoring function optimization                         |    Miniconda, Obabel, py3dmol, RDKit, smina, qvina2, mgltools 1.5.7                                                                                                      |


