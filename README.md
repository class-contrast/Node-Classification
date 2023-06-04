# TDA-Node-Classification
This repository contains the code for topologicla data analysis for node classificaton task .
The following files contain different codes used for the experiment in this paper. Three small datasets (CORA, CITESEER, and PUBMED) and three OGBN-datasets (ARXIV, MAG, and PROTIEN) have been used in this experiment.
# Feature_protiens.ipynb
This file contains the code for extracting spatial feature vector for OGBN-PROTIEN dataset. These vectors are later used on "OGBN_Node_Classification.ipynb"  
# Node_classification(1).ipynb
This file contains the code for extracting both the spatial and domain feature vector for the CORA, CITESEER, PUBMED, and OGBN-MAG datasets including all meachine learning related works for example train-test-split, evaluating accuracy, XGBoost, etc.
# OGBN_Node_Classification.ipynb
This file contains the code for loading dataset, extracting both spatial and domain feature vector, and other meachine learing works for other OGBN-datasets.
