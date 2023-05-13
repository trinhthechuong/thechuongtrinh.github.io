---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Pharmacy, University of Medicine and Pharmacy at Ho Chi Minh city, 2013-2018
* MSc. in Pharmacy,  University of Medicine and Pharmacy at Ho Chi Minh city, 2020-2022
* Pursing Ph.D position in cheminformatics/machine learning, 2023+

Work experience
======
* 2018 - now: Research Assistant - Organic Chemistry Department
  * **Methodology developemt**
    * *MolUtil*: molecular standardization, featurization, medicinal chemistry filtration, and chemical space visualization (incorporate with RDKit)
    * *mlqsar*: QSAR-machine learning pipeline development incorporate with post hoc Wilcoxon for decision making
    * *MolAD*: applicability domains detection with convex hull 
    * *MoleculeClustering*: molecules clustering with Butina algorithms and diverse subsets selection
    * *MolPh4*: pharmacophore validation, statistical comparison (Wilcoxon); ensemble pharmacophore development
    * *DockingValid*: automated result extraction and validation (retrospective control-ROC plot)
    * *Mol2DSimi*: molecular similarity searching, validation, and comparison between different fingerprints
  * **Application of AI methods in drug discovery**
    * *HIV-1 integrase* (Master thesis): QSAR pipeline for data type selection and model building, pharmacophore modeling with ensemble methods, alphafold2 for protein curation and benchmarking molecular docking packages (Vina, Smina, Qvina2, Vina GPU, Autodock GPU)
    * *SGLT2i*: comparison between MACCs and ECFP4 in QSAR model, pharmacophore optimization by query threshold 
    * *PD-1/PD-L1* immune checkpoint: similarity comparison among MACCs, ECFP4 and RDK5; similarity searching 
  * **Supervisor for undergraduate students' thesis**
    * *Tubulin*: prediction of protein-ligand interaction using graph neural networks; molecular dynamics (Gromacs)
    * *ALK*: ANN model development, 3D-Image-QSAR using CNN with  6 times rotation, GNN with pytorch geometric
    * *VEGF*: QSAR model development integrated into JT-VAE network for molecules optimizaztion
* 2016 - 2018: Research internship - Organic Chemistry Department
  * Duties included:
    *  Experienced *in silico* techniques by collaborating in lab seminars and academic projects.
    *  Collaborated with labmates to conduct 2D-QSAR utilizing MOE software to screen anticancer bioactivities of some isothiocyanate derivates.
    *  Performed FlexX and Autodock Vina for CDK2 protein (PDB ID: 2C4G), interaction analysis.
  * Supervisor: Professor Ngoc Tuyen TRUONG

  
Skills
======
* Programming: Python, C++, Linux, Git, OOP
* Cheminformatics: RDKit, MOE, Pymol, Autodock, Gromacs, VMD
* Data science
  * Data analysis: visualization (seaborn, matplotlib, plotly), linear algebra, calculus, probability and statistics (numpy, pandas)
  * Data mining: data pipeline development including handle low variance features, missing values, univariate and multivariate outliers; conduct statistical test for decision making in model selection using cross-validation
  * Machine learning: scikit-learn, imblearn, XGBoost, CatBoost, optimization (grid search and bayesian search)
  * Deep Learning: Pytorch, Tensorflow, Keras, CNNs, RNNs, GNN.
* Process Automation
* Problem solving, crictical thinking


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
# Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  

References
======
* Assoc.Prof.Truong Ngoc Tuyen, PhD
  * Position: Head of Department of Organic Chemistry, Pharmacy Faculty, University of Medicine and pharmacy at Ho Chi Minh city
  * Email: truongngoctuyen@upm.edu.vn

* Assoc.Prof. Tran Nguyen Minh An, PhD
  * Position: Vice Dean of Chemical Technology Faculty, Industrial University of Ho Chi Minh city
  * Email: trannguyenminhan@iuh.edu.vn




