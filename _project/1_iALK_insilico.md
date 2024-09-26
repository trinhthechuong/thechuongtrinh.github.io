---
title: "Development and integration of advanced Artificial intelligence including machine learning, ANN, GNN in conjunction with consensus molecular docking for the prediction of potent Anaplastic Lymphoma Kinase inhibitors."
excerpt: "This is a repository containing my graduation thesis, which is currently under review by the BBA - Molecular Basis of Disease Journal. <br/><img src='/images/Thesis/Graphical_abs.pdf'>"
collection: project
---


# Abstract
This study addresses the urgent need for novel Anaplastic lymphoma kinase (ALK) inhibitors in Non-Small Cell Lung Cancer (NSCLC) treatment, focusing on the ALK positive mutation variant (5% of the cases). As only five Food and Drug Administration (FDA)-approved ALK inhibitors are on the market, the demand for effective drugs persists. Leveraging the power of Artificial Intelligence (AI) including machine learning (ML), and deep learning, our research aimed to expedite the screening of novel ALK inhibitors. Notably, the machine learning-based XGBoost algorithm exhibited compelling results with an external validation (EV)-f1 score of 0.921, and an EV Average Precision (AP) of 0.961, alongside a cross-validation (CV)-f1 score of 0.888±0.039 and a CV-AP of 0.939±0.032. Besides, the deep learning-based Artificial Neural Network (ANN) model demonstrated excellent performance with an EV-f1 score of 0.930 and an EV-AP of 0.955, complemented by a CV-f1 score of 0.891±0.037 and a CV-AP of 0.934±0.040. The present study undertook a comparative analysis between the traditional ML models, the ANN model, and the Graph Neural Network (GNN) model, which is a product of our recent research endeavors. The findings reveal that, despite the advancements in neural network models, traditional machine learning models exhibited superior performance over the GNN model. During this research, these models were employed in conjunction with a consensus molecular docking model to screen a total of 120,571 compounds virtually, leading to the identification of three promising ALK inhibitors: CHEMBL1689515, CHEMBL2380351, and CHEMBL102714. The study recommends further molecular dynamic simulations, in vitro tests, target-specific experimental data acquisition for active learning, and application of advanced AI models like geometric interaction GNN and generative AI for molecular optimization.

## Method and Results
The raw dataset consists of 26.168 substances tested for their ALK receptor inhibitory potential, collected from the Reaxys database. The study successfully utilized 1.664 substances to construct and evaluate a series of ALK inhibitor classification models.
- Employing data-centric **machine learning** methodologies to ascertain the most effective molecular representation.
<a href="https://trinhthechuong.github.io/images/Thesis/QSAR.png"><img src="/images/Thesis/QSAR.png" target="_blank" alt="QSAR" class="center" style="width:700px"></a>

- Executing an Artificial Neural Network model that leverages the identified optimal molecular representation. 
<a href="https://trinhthechuong.github.io/images/Thesis/ANN_process.png"><img src="/images/Thesis/ANN_process.png" target="_blank" alt="ANN_process" class="center" style="width:700px"></a>
- Integrating consensus docking models, including Autodock-GPU, Vina-GPU-2.0, GNINA, and XGBoost algorithm.
<a href="https://trinhthechuong.github.io/images/Thesis/Consensus_docking.png"><img src="/images/Thesis/Consensus_docking.png" target="_blank" alt="Consensus_docking" class="center" style="width:700px"></a>

- These AI models were employed in conjunction with a consensus docking model to screen a total of 120,571 compounds virtually, leading to the identification of three promising ALK inhibitors: **CHEMBL1689515, CHEMBL2380351, and CHEMBL102714**.
<a href="https://trinhthechuong.github.io/images/Thesis/Candidates.png"><img src="/images/Thesis/Candidates.png" target="_blank" alt="Candidates" class="center" style="width:700px"></a>


## Note
For more detailed information, please visit:
1. Our preprint is [here](https://chemrxiv.org/engage/chemrxiv/article-details/66d84cd051558a15ef046443), which is currently under review by the BBA - Molecular Basis of Disease Journal.
2. My dissertation presentation [here](https://trinhthechuong.github.io/files/thesis_slide.pdf).
<a href="https://trinhthechuong.github.io/files/thesis_slide.pdf"><img src="/images/Thesis/Graphical_abs.pdf" target="_blank" alt="thesis slide" class="center" style="width:700px"></a>




## Contributing

Please visit the [this repository on Github.](https://github.com/trinhthechuong/ML-ANN-GNN-for-Screening-potential-iALKs)

