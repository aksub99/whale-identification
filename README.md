# Humpback Whale Identification
PyTorch solution to **Humpback Whale Identification** challenge on Kaggle. [Link](https://www.kaggle.com/c/humpback-whale-identification)

## Problem Statement
Classify the input image of a whale's tail into one of 5005 possible classes.

## Model Summary
Densenet model pretrained on ImageNet classes has been finetuned on the whale dataset.
### Data Augmentation
1. Random Horizontal Flip with 0.5 probability
2. Random Affine
