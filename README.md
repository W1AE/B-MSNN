# Multimodal Feature Learning Structure with MP Inverse for Big Data

## Abstract: 
The fully-connected neural networks (FCNNs) are the simplest type of networks which aims to process the feature learning tasks. They are present in most of the models. For example, the FC layers are an essential component of DCNNs, which have been proven very successful in classifying images. However, most FCNNs search the latent space features with separate blocks, which result in loosely connected feature encoding. This work addresses this pitfall through training a new hierarchical subnetwork (HS)-based FC framework, termed HS-based neural network (HSNN). The novelties of this algorithm are as follows: 1) It's a one-step iterative learning process, instead of stacking separate sections to obtain the discriminative representation and classify the objects. By doing so, the researchers are easily to find the more generalized features. 2) Single-modality networks may incur coding bias due to one-sided feature description, therefore, this work proposes a multiple-modality learning to boost the classification performance; 3) More importantly, it develops a MP inverse-based batch-by-batch learning strategy to process the large-scale databases. Experiments on image classification and radar signal processing domains with varying number of training samples show that the proposed feature representation network gets stronger testing performance compared with other feature learning frameworks.

## Contributions:
* We provided a new FC structure for representation learning. We aimed to improve the representational power of the framework, two network-in-network structures, subnetwork (SNN), and reinforcement subnetwork (Re-SNN) were applied to find the generalized feature space.

* We proposed a batch-by-batch learning strategy for this hierarchical neural network in order to process large scale databases. 

* We introduced a multimodal representation learning algorithm. Single modality feature coding may be biased and inadequate for a  certain learning task. Hence, in this paper, the multi-channel statistical model evaluation network was used. 

## Learning Structure:

<img src="https://github.com/1027051515/HSNN/raw/master/FIG1.jpg" width="1200" height="300" />

<img src="https://github.com/1027051515/HSNN/raw/master/FIG2.jpg" width="1200" height="300" />

## Downloads:
### Scene-15
* Fine-tuned VGG-16 features: [VGG16_S15](https://drive.google.com/open?id=16Jhzxp2zwXyYXpAEaP_2Pjwxki6HeRZB)
* Fine-tuned ResNet-50 features: [Res50_S15](https://drive.google.com/open?id=1Jb_xdmA9StQLUme3LG_e3_EjlNIM3hiH)
* Fine-tuned InceptionNet-v3 features: [Incv3_S15](https://drive.google.com/open?id=1ku7huEzJ8I99qYKT5gtCG803puMz9kxe)
* Source code for Scene-15: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-101
* Caltech-101 dataset: [Caltech-101](http://www.vision.caltech.edu/Image_Datasets/Caltech101/#Download)
* Fine-tuned VGG-16 features: [VGG16_C101](https://drive.google.com/open?id=1lKlwxtGF3eMyYwnVtoe8YsmMhcgsCpJN)
* Fine-tuned ResNet-50 features: [Res50_C101](https://drive.google.com/open?id=1F5BUPCQkzR1OmTlx2aID-E-Is6PrWHRZ)
* Fine-tuned InceptionNet-v3 features: [Incv3_C101](https://drive.google.com/open?id=1pFeL9kC8vs9ljmB4JYOxTznSj0MxM6DF)
* Source code for Caltech-101: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-256
* Caltech-256 dataset: [Caltech-256](http://www.vision.caltech.edu/Image_Datasets/Caltech256/)
* Fine-tuned VGG-16 features: [VGG16_C256](https://drive.google.com/open?id=1u7rY_meYZt5FpHZsHpELMF2tXcwdNhWF)
* Fine-tuned ResNet-50 features: [Res50_C256](https://drive.google.com/open?id=104hhcvC20s4sp0J7TYRRM6VK51a6d83v)
* Fine-tuned InceptionNet-v3 features: [Incv3_C256](https://drive.google.com/open?id=1XIHncWSHRH97TDtxCj2-QvR2KjubMXNh)
* Source code for Caltech-256: The file will be made public after acceptance of the manuscript (if decided so).

