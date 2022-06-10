**project solubility-predictor** (in progress)

# Predicting Aqueous Solubility of Organic Molecules Using Molecular Descriptor Model

## ML model: Random Forest Regressor

## ML features: physico-chemical descriptors obtained with PaDEL software
according to article **"Predicting Aqueous Solubility of Organic Molecules Using Deep Learning Models withVaried Molecular Representations"** by Panapitiya et al, 2021 *(https://arxiv.org/pdf/2105.12638v1.pdf)*, Molecular Descriptor Model overperforms fully connected neural networks (FCNNs), recurrent neural networks (RNNs), graph neural networks (GNNs), and SchNet.

## Training Dataset: ESOL Delaney, Water solubility data (**LogS**, log solubility in mols per litre) for common organic small molecules.

dataset is obtained from https://moleculenet.org/datasets-1 , original data **Delaney "ESOL:  Estimating Aqueous Solubility Directly from Molecular Structure"** *J. Chem. Inf. Comput. Sci.* 2004, **44**, 3, 1000–1005)
