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
##########################################################

**Hint**
we have modified the ‘kegra’ package, and we have uploaded this package to our repository. This package has been downloaded from this link, and if you use our code, you should cite our paper and their paper. You should cite their paper as follows:
@inproceedings{kipf2017semi,
  title={Semi-Supervised Classification with Graph Convolutional Networks},
  author={Kipf, Thomas N. and Welling, Max},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2017}
}}

