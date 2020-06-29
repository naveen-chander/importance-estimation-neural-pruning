# Importance Estimation based Pruning for Neural Networks

## Table of Contents

1. [Overview](#overview)
2. [Requirements] (#req)
3. [Setup ](#setup)
4. [Acknowledgments](#ack)


<a name="overview"></a>
### Overview
This repository is an notebook-tutorial for pruning neural networks based on Importance based Pruning Method applied to CNN and MLP.
MNIST Dataset is used in both cases. Also, a comparison is made between the *l1- structural pruner* and the *importance pruner*.
Paper: https://arxiv.org/abs/1906.10771

<a name="req"></a>
### Requirements

* Tensorflow==1.13.1 
```
pip install tensorflow==1.1.3
```
* Keras==2.3     	
```
pip install keras==2.3
```
* keras surgeon  
```	
pip install kerassurgeon
```
* If you are only using the MLP notebook, then the latest versions for MLP and Keras can be used.

* Jupyter Notebook

<a name="setup"></a>
### Setup 

* Clone the github 
```
   $ git clone https://github.com/naveen-chander/importance-estimation-neural-pruning.git 
```
* Open Notebook in Jupyter Notebook
* Notebook is self explanatory

<a name="ack"></a>
### Acknowledgments
1. Prof. Ambedkar Dukkipati , Dept. of Computer Science and Automation, Indian Institute of Science, Bengaluru
2. Molchanov et al., (2019) , https://arxiv.org/abs/1906.10771
3. https://medium.com/@anuj_shah/model-pruning-in-keras-with-keras-surgeon-e8e6ff439c07
4. KerasSurgeon package has been adopted from: https://github.com/BenWhetton/keras-surgeon



