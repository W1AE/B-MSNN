# Multimodal Feature Reinforcement Framework using Moore-Penrose Inverse for Big Data Analysis

## Abstract: 
The fully-connected (FC) layer is an essential component both of representation learning frameworks and deep convolutional networks. Among the existing FC neural networks (FCNNs), the backpropagation-based and Moore-Penrose (MP) inverse-based frameworks have proven to be powerful and effective learning models. However, most FCNNs, such as auto-encoder and deep belief networks encode features and find the final cognition with basic building blocks, resulting in loosely connected feature representation. This work addresses this pitfall through training a new hierarchical subnetwork (HS)-based FC framework, termed HS-based neural network (HSNN). The novelties of this algorithm are as follows: (i) It is an iterative learning process, instead of stacking separate blocks to obtain the discriminative encoding. In this sense, the global optimal feature subspaces are generated; (ii) It introduces multimodal learning to boost the classification performance to overcome the bias that may incur in single-modal networks due to one-sided feature description; (iii) It applies MP inverse-based batch-by-batch learning strategy to handle large-scale datasets, such as Place365 containing 1.8 million images. The experimental results on multiple domains with varying number of training samples, from 1,274 to 1.8 million, show that the proposed feature reinforcement framework achieves better generalization performance compared with most state-of-the-art FCNNs.

## Contributions:
* A novel FC framework for representation learning. In order to increase the representational power of the network, two NIN structures, SNN, and reinforcement SNN (Re-SNN) are introduced to find the generalized feature subspaces.

* A batch-by-batch learning strategy for HSNN to process large scale datasets. The learning mode for HSNN can be switched from one-batch to batch-by-batch flexibly, only with the consideration of input data size.

* A multimodal encoding algorithm. It is to boost  the  classification  performance  and to  overcome  the  bias  that may  incur  in  single-modal  networks  due  to  one-sided  feature encoding.

## Learning Structure:
