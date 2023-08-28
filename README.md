# TDA-Node-Classification
This repository contains the code for topologicla data analysis for node classificaton task .
The following files contain different codes used for the experiment in this paper. Three small datasets (CORA, CITESEER, and PUBMED) and two OGBN-datasets (ARXIV and MAG) have been used in this experiment.

# "Dataset name"_inductive.ipynb
This file contains the code for extracting spatial feature vector and domain feature vectors for the corresponding dataset in inductive setting. All meachine learing related works are also inculed in this file.

# PUBMED_transductive-AS.ipynb
This file encompasses the code for extracting spatial feature vectors, domain feature vectors, and performing various machine learning tasks within a transductive setting for the PUBMED dataset. 

# Node_classification(1).ipynb
This file contains the code for extracting both the spatial and domain feature vector for the CORA, CITESEER, PUBMED, and OGBN-MAG datasets including all meachine learning related works for example train-test-split, evaluating accuracy, XGBoost, etc.
# OGBN_Node_Classification.ipynb
This file contains the code for loading dataset, extracting both spatial and domain feature vector, and other meachine learing works for other OGBN-datasets.

# Feature_protiens.ipynb
This file contains the code for extracting spatial feature vector for OGBN-PROTIEN dataset. These vectors are later used on "OGBN_Node_Classification.ipynb"  
