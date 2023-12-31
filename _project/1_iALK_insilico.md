---
title: "Development and integration of advanced Artificial intelligence including machine learning, ANN, GNN in conjunction with consensus molecular docking for the prediction of potent Anaplastic Lymphoma Kinase inhibitors."
excerpt: "This is a repository containing my graduation thesis, which is currently under review by the Scientific Reports Journal. <br/><img src='/images/Thesis/Summary_SR.png'>"
collection: project
---


# Abstract
This study addresses the urgent need for new Anaplastic lymphoma kinase (ALK) inhibitors in Non-Small Cell Lung Cancer (NSCLC), focusing on the ALK-positive mutation variant (5% of cases). Despite only five FDA-approved inhibitors, the demand for effective drugs persists. Leveraging the power of AI, machine learning, and deep learning, our research expedites novel ALK inhibitor screening. The dataset includes 26,168 substances tested for ALK inhibition potential from scientific papers. Notably, the XGBoost machine learning model exhibited compelling results with an external validation (EV) f1 score of 0.921 and an EV-AP of 0.961, along with a cross-validation (CV) f1 score of 0.888±0.039 and a CV-AP of 0.939±0.032. Besides, the ANN demonstrated excellence with an EV-f1 score of 0.930 and an EV-AP of 0.955, complemented by a CV-f1 score of 0.891±0.037 and a CV-AP of 0.934±0.040. The present study undertakes a meticulous comparative analysis between traditional machine learning models and a Graph Neural Network (GNN) model, the latter being a product of our recent research endeavors. The findings reveal that, despite the advancements in neural network models, traditional machine learning models exhibit superior performance over the GNN model. During this research, these models were employed in conjunction with a consensus docking model to screen a total of 120,571 compounds virtually, leading to the identification of three promising ALK inhibitors: CHEMBL1689515, CHEMBL2380351, and CHEMBL102714. The study recommends further dynamic simulations, in vitro tests, and exploration of advanced AI models like CNN and RNN for molecular optimization.

## Method and Results
The raw dataset consists of 26.168 substances tested for their ALK receptor inhibitory potential, collected from the Reaxys database. The study successfully utilized 1.664 substances to construct and evaluate a series of ALK inhibitor classification models.
- Employing data-centric **machine learning** methodologies to ascertain the most effective molecular representation.
<a href="https://trinhthechuong.github.io/images/Thesis/QSAR.png"><img src="/images/Thesis/QSAR.png" target="_blank" alt="thesis slide" class="center" style="width:700px"></a>

- Executing an Artificial Neural Network model that leverages the identified optimal molecular representation. 
<a href="https://trinhthechuong.github.io/images/Thesis/ANN_process.png"><img src="/images/Thesis/ANN_process.png" target="_blank" alt="thesis slide" class="center" style="width:700px"></a>
- Integrating consensus docking models, including Autodock-GPU, Vina-GPU-2.0, GNINA, and XGBoost algorithm.
<a href="https://trinhthechuong.github.io/images/Thesis/Consensus_docking.png"><img src="/images/Thesis/Consensus_docking.png" target="_blank" alt="thesis slide" class="center" style="width:700px"></a>

- These AI models were employed in conjunction with a consensus docking model to screen a total of 120,571 compounds virtually, leading to the identification of three promising ALK inhibitors: **CHEMBL1689515, CHEMBL2380351, and CHEMBL102714**.
<a href="https://trinhthechuong.github.io/images/Thesis/Candidates.png"><img src="/images/Thesis/Candidates.png" target="_blank" alt="thesis slide" class="center" style="width:700px"></a>

## Thesis slide
For more detailed information, please visit the slides from my dissertation presentation [here](https://tieulongphan.github.io/files/thesis_slide.pdf).
<a href="https://tieulongphan.github.io/files/thesis_slide.pdf"><img src="/images/Thesis/Summary_SR.png" target="_blank" alt="thesis slide" class="center" style="width:700px"></a>
## Requirements

This module requires the following modules:

- scikit-learn (1.3.0)
- imbalanced-learn (0.11.0)
- PyTorch (2.0)
- Optuna (3.2.0)
- Open-Source PyMOL
- RDKit
- Mordred
- PaDEL-Descriptor (2.21)
- Cats2d, Map4
- Plotly, Matplotlib, Seaborn
- Pandas, SciPy
- MLflow
- Autodock-GPU, Vina-GPU-2.0, GNINA, MGLTools, Autodock Tools 1.5.7 rc



## Note
This is a repository containing my graduation thesis, which is currently under review by the Scientific Reports Journal.



## Contributing

Please visit the [this repository on Github.](https://github.com/trinhthechuong/ML-ANN-GNN-for-Screening-potential-iALKs)

