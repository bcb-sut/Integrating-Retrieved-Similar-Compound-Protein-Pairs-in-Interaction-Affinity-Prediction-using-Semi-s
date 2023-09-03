# PLA-SGCN: Protein-Ligand Binding Affinity Prediction by Integrating Similar Pairs and Semi-supervised Graph Convolutional Network
PLA-SGCN: Protein-Ligand Binding Affinity Prediction by Integrating Similar Pairs and Semi-supervised Graph Convolutional Network
# PLA-SGCN
########################################################## 

The source code for
PLA-SGCN: Protein-Ligand Binding Affinity Prediction by Integrating Similar Pairs and Semi-supervised Graph Convolutional Network

##########################################################

**Requirements**

Python 3.8

Tensorflow 0.12.0

Keras (1.1 or higher)

Scipy 1.3.2

NumPy

Keras-gcn (download and install it-download link:https://github.com/tkipf/keras-gcn) 
##########################################################

**Data**


Download the data from the following link.

https://drive.google.com/open?id=1B72WnWMbywxK2M9RntquRWQ3cm6U9YoW

Download the folded data from the following link:

https://drive.google.com/open?id=15KotSJWknMOAnHM68RpOh_rqMISsMwsE
##########################################################

**Usage**

At first, Keras-gcn should be installed. The hyperparameters are set in the config.py file. You can select Davis, KIBA, PDBind, and BindingDB datasets in this file. Also, The other hyperparameters could be set to your desired values. Then, you can run the sgcn.py.
