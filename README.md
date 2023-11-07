# Deep Learning Essentials: A Comprehensive PyTorch Tutorial

Halfway through [CS231n](http://cs231n.stanford.edu/) lectures and assignments, I decided to write this tutorial on **PyTorch** and **the best neural network practices** by implementing an image classification project. Despite the problem being simple, it is a great starting point as many other Computer Vision problems like object detection and segmentation can be reduced to image classification. This tutorial is heavily inspired by the teachings of [Andrej Karpathy](https://karpathy.ai/). It covers the most basic and essential information you should definitely know if you’re getting started with your ML/DL career.

To run this notebook locally:
1. Download the CIFAR-10 dataset from [here](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz) 
2. Create a `dataset` folder in the same directory as the notebook and extract it there 

With Kaggle:
1. Import notebook into Kaggle (gives free 32 GPU hours once verified)
2. Search for [CIFAR-10](https://www.kaggle.com/datasets/pankrzysiu/cifar10-python) dataset and add it
3. Enable GPU and you're good to go 

Model weights are available [here](https://drive.google.com/drive/folders/1-3Fx7Z-DT-59eIS2YGHADRWf19p5JadK)