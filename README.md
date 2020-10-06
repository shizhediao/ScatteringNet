# Mini-Project 1. Feature Extraction and Transfer Learning
MATH 6380P. Advanced Topics in Deep Learning Fall 2020

Authors: Shizhe Diao, Jincheng Yu, Duo Li, Yimin Zheng (in no particular order)

### Introduction
This repo contains the source code for Mini-Project 1. Feature Extraction and Transfer Learning.

We explore the feature extractions using existing networks, such as pre-trained deep neural networks (i.e. ResNet18) and scattering nets, in image classifications with traditional machine learning methods.

### Functions and commands
Feature extraction by scattering net with known invariants;
Feature extraction by pre-trained deep neural networks, e.g. VGG19, and resnet18, etc.;
Visualize these features using classical unsupervised learning methods, e.g. PCA/MDS, Man- ifold Learning, t-SNE, etc.;
Computation and analysis
Image classifications using traditional supervised learning methods based on the features extracted, e.g. LDA, logistic regression, SVM, random forests, etc.;

### Dependencies
python 3.6
pytorch 1.6.0
scatwave 0.0.1
scikit-cuda	0.5.3
scikit-learn	0.23.2
cupy	8.0.0
kymatio	0.3.dev0  
matplotlib	3.3.2 


### Datasets
Fashion-MNIST dataset: Zalando’s Fashion-MNIST dataset of 60,000 training images and 10,000 test images, of size 28-by-28 in grayscale.
https://github.com/zalandoresearch/fashion-mnist