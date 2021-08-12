# Cassava Leaf Disease Classifier

This repository contains experiments conducted to create a classifier capable of identifying the type of disease present on a cassava leaf image.

All experiments are tracked using [Weights & Biases](https://wandb.ai/ravimashru/cassava-clf).

Data source: [Kaggle - Cassava Leaf Disease Classification](https://www.kaggle.com/c/cassava-leaf-disease-classification)

## Iterations

### Baseline

[Notebook](01-baseline.ipynb)

Accuracy achieved: 0.879645

### Progressive Resizing, Normalization and Test Time Augmentation

[Notebook](02-progressive-resizing.ipynb)

Accuracy achieved: 0.885029

### Progressive Resizing, Normalization, Test Time Augmentation and MixUp

[Blog post](https://ravimashru.dev/blog/2021-08-11-fastbook-ch7/)

Accuracy achieved: 0.885019
