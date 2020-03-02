# Multimodal Feature Reinforcement Framework using Moore-Penrose Inverse for Big Data Analysis

## Abstract: 
The fully-connected (FC) layer is an essential component both of representation learning frameworks and deep convolutional networks. Among the existing FC neural networks (FCNNs), the backpropagation-based and Moore-Penrose (MP) inverse-based frameworks have proven to be powerful and effective learning models. However, most FCNNs, such as auto-encoder and deep belief networks encode features and find the final cognition with basic building blocks, resulting in loosely connected feature representation. This work addresses this pitfall through training a new hierarchical subnetwork (HS)-based FC framework, termed HS-based neural network (HSNN). The novelties of this algorithm are as follows: (i) It is an iterative learning process, instead of stacking separate blocks to obtain the discriminative encoding. In this sense, the global optimal feature subspaces are generated; (ii) It introduces multimodal learning to boost the classification performance to overcome the bias that may incur in single-modal networks due to one-sided feature description; (iii) It applies MP inverse-based batch-by-batch learning strategy to handle large-scale datasets, such as Place365 containing 1.8 million images. The experimental results on multiple domains with varying number of training samples, from 1,274 to 1.8 million, show that the proposed feature reinforcement framework achieves better generalization performance compared with most state-of-the-art FCNNs.

## Contributions:
* A novel FC framework for representation learning. In order to increase the representational power of the network, two NIN structures, SNN, and reinforcement SNN (Re-SNN) are introduced to find the generalized feature subspaces.

* A batch-by-batch learning strategy for HSNN to process large scale datasets. The learning mode for HSNN can be switched from one-batch to batch-by-batch flexibly, only with the consideration of input data size.

* A multimodal encoding algorithm. It is to boost  the  classification  performance  and to  overcome  the  bias  that may  incur  in  single-modal  networks  due  to  one-sided  feature encoding.

## Learning Structure:

<img src="https://github.com/1027051515/HSNN/raw/master/FIG1.jpg" width="1200" height="300" />

<img src="https://github.com/1027051515/HSNN/raw/master/FIG2.jpg" width="1200" height="300" />

## Downloads:
### Scene-15
* Scene-15 dataset: [Scene-15](http://elm-lang.org/)
* Fine-tuned VGG-16 features: [VGG16_S15](http://elm-lang.org/)
* Fine-tuned ResNet-50 features: [Res50_S15](http://elm-lang.org/)
* Fine-tuned InceptionNet-v3 features: [Incv3_S15](https://drive.google.com/open?id=16Z_fdS2i_qF1dxC6at1795NhV7m6OBPl)
* Source code for Scene-15: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-101
* Caltech-101 dataset: [Caltech-101](http://www.vision.caltech.edu/Image_Datasets/Caltech101/#Download)
* Fine-tuned VGG-16 features: [VGG16_C101](http://elm-lang.org/)
* Fine-tuned ResNet-50 features: [Res50_C101](http://elm-lang.org/)
* Fine-tuned InceptionNet-v3 features: [Incv3_C101](http://elm-lang.org/)
* Source code for Caltech-101: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-256
* Caltech-256 dataset: [Caltech-256](http://www.vision.caltech.edu/Image_Datasets/Caltech256/)
* Fine-tuned VGG-16 features: [VGG16_C256](http://elm-lang.org/)
* Fine-tuned ResNet-50 features: [Res50_C256](http://elm-lang.org/)
* Fine-tuned InceptionNet-v3 features: [Incv3_C256](http://elm-lang.org/)
* Source code for Caltech-256: The file will be made public after acceptance of the manuscript (if decided so).
