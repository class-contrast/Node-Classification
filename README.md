# TDA-Node-Classification (Edited)
This repository contains the code for topologicla data analysis for node classificaton task .
The following files contain different codes used for the experiment in this paper. Three small datasets (CORA, CITESEER, and PUBMED) and two OGBN-datasets (ARXIV and MAG) have been used in this experiment.

# "Dataset name"_inductive.ipynb
This file contains the code for extracting spatial feature vector and domain feature vectors for the corresponding dataset in inductive setting. All meachine learing related works are also inculed in this file.

# PUBMED_transductive-AS.ipynb
This file encompasses the code for extracting spatial feature vectors, domain feature vectors, and performing various machine learning tasks within a transductive setting for the PUBMED dataset. 

# MAGTransdactive.ipynb and MAGMLP.ipynb
This file includes the code for loading the dataset, extracting spatial feature vectors for the MAG dataset within a transductive setting. These vectors are subsequently saved as "Feature_1it_nbd_mag.csv". Later, the vectors are utilized in the "MAGMLP.ipynb" file, where they are combined with domain features and employed for various machine learning tasks.

# ArxivMLP.ipynb and Ablation Arxiv.ipynb
The "ArxivMLP.ipynb" file comprises Python code for the Arxiv dataset, responsible for generating spatial and domain features. These features are then saved as "Feature_nbd_tran_OGB_arxiv". Subsequently, these vectors are utilized in the "Arxiv.ipynb" file to carry out various machine learning tasks.

# Node_classification(1).ipynb
This file contains the code for extracting both the spatial and domain feature vector for the CORA, CITESEER, and PUBMED, in transductive setting and OGBN-MAG datasets in inductive setting including all meachine learning related works for example train-test-split, evaluating accuracy, XGBoost, etc.
# OGBN_Node_Classification.ipynb
This file contains the code for loading dataset, extracting both spatial and domain feature vector, and other meachine learing works for other OGBN-datasets.
 
