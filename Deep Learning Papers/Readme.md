# CONTENTS

## 1. AutoAugment: Learning Augmentation Policies from Data 
#### Subjects:	Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG); Machine Learning (stat.ML)
#### Authors: Ekin D. Cubuk, Barret Zoph, Dandelion Mane, Vijay Vasudevan, Quoc V. Le
Data augmentation is an effective technique for improving the accuracy of modern image classifiers. However, current data augmentation implementations are manually designed. In this paper, we describe a simple procedure called **AutoAugment to automatically search for improved data augmentation policies**. In our implementation, we have designed a search space where a policy consists of many sub-policies, one of which is randomly chosen for each image in each mini-batch. A sub-policy consists of two operations, each operation being an image processing function such as translation, rotation, or shearing, and the probabilities and magnitudes with which the functions are applied. We use a search algorithm to find the best policy such that the neural network yields the highest validation accuracy on a target dataset. Our method achieves state-of-the-art accuracy on CIFAR-10, CIFAR-100, SVHN, and ImageNet (without additional data).

## 2. Introduction to Convolutional Neural Networks
#### Author: Jianxin Wu
The Convolutional Neural Network (CNN) has shown excellent performance in many computer vision and machine learning problems. CNN is useful in a lot of applications, especially in image related tasks. Applications of CNN include image classification, image semantic segmentation,2object detection in images, etc. We will focus on **image classification** (or categorization) in this note. In image categorization, every image has a major object which occupies a large portion of the image.

## 3. Understanding Convolutional Neural Networks with A Mathematical Model
#### Author: C.-C. Jay Kuo
This work attempts to address two fundamental questions about the structure of the convolutional neural networks (CNN): 1) why a nonlinear activation function is essential at the filter output of all intermediate layers? 2) what is the advantage of the two-layer cascade system over the one-layer system? A mathematical model called the **“REctified-COrrelations on a Sphere” (RECOS)** is proposed to answer these two questions.

## 4. Evaluation of Pooling Operations in Convolutional Architectures for Object Recognition
#### Authors: Dominik Scherer, Andreas Muller, and Sven Behnke
A common practice to gain invariant features in object recognition models is to aggregate multiple low-level features over a small neighborhood. However, the differences between those models makes a comparison of the properties of different aggregation functions hard. Our aim is to gain insight into different functions by directly comparing them on a fixed architecture for several common object recognition tasks. Empirical results show that a maximum pooling operation significantly outperforms subsampling operations. Despite their shift-invariant properties, overlapping pooling windows are no significant improvement over non-overlapping pooling windows. By applying this knowledge, we achieve state-of-the-art error rates of 4.57% on the NORB normalized-uniform dataset and 5.6% on the NORB jittered-cluttered dataset.

## 5. An Empirical Exploration of Recurrent Network Architectures
#### Authors: Rafal Jozefowicz (RAFALJ@GOOGLE.COM), Wojciech Zaremba (WOJ.ZAREMBA@GMAIL.COM), Ilya Sutskever (ILYASU@GOOGLE.COM)
In this work, we aim to determine whether the LSTM architecture is optimal or whether much better architectures exist. We conducted a thorough architecture search where we evaluated over ten thousand different RNN architectures, and identified an architecture that outperforms both the LSTM and the recently-introduced Gated Recurrent Unit (GRU) on some but not all tasks. We found that adding a bias of 1 to the LSTM’s forget gate closes the gap between the LSTM and the GRU.

## 6. Gradient-Based Learning Applied to Document Recognition
#### Authors: Yann LeCun, Leon Bottou, Yoshua Bengio, Patrick Haffner
The main message of this paper is that better pattern recognition systems can be built by relying more on automatic learning and less on hand-designed heuristics.

## 7. The Self-Organizing Map
#### Author: Teuvo Kohonen

## 8. On the difficulty of training Recurrent Neural Networks
#### Authors: Razvan Pascanu (pascanur@iro.umontreal.ca), Tomas Mikolov (t.mikolov@gmail.com), Yoshua Bengio (yoshua.bengio@umontreal.ca)
There are two widely known issues with properly training Recurrent Neural Networks, the vanishing and the exploding gradient problems detailed in Bengio et al. (1994). In this paper we attempt to improve the understanding of the underlying issues by exploring these problems from an analytical, a geometric and a dynamical systems perspective. Our analysis is used to justify a simple yet effective solution. We propose a gradient norm clipping strategy to deal with exploding gradients and a soft constraint for the vanishing gradients problem. We validate empirically our hypothesis and proposed solutions in the experimental section.
