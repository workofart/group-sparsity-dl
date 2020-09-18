# Benefit of Group Sparsity in Deep Learning

We will apply some non-deep learning classification algorithms as well as many deep learning algorithms with or without group sparsity on some real datasets. Our goal is to show the benefits of group sparsity in deep learning: **significantly reduce the number of parameters while preserve a good accuracy**. We will also include some brief discussion on theoretical properties of group sparsity.

---

## Authors
*Kan Chen, Zongyu Dai, Hanxiang (Henry) Pan, Yue Sheng*

## Research Report

[Here](https://github.com/workofart/group-sparsity-dl/blob/master/Benefit_of_Group_Sparsity_in_Deep_Learning.pdf)

## How to run

Please find the implementation and experiments in `Project Experiments.ipynb`.


## Dependencies

Please note that the notebook is run with a freshly installed Python `3.6.9` environment with the dependencies defined in `requirements.txt`.

## Experiment Results

These can be found in `Experiment Result/{Regularization Type}/{Dataset}`
- **Regularization Type** can be one of [`L1`, `L2`, `Group Sparsity`]
- **Dataset** can be one of [`Cover`, `MNIST`, `SDD`].

The results include plots of accuracy vs different types of hyperparameters, as well as raw results stored as `{Dataset}_result.json`.

## Datasets

[MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)
- MNIST should be downloaded automatically through Pytorch
  
[Forest Covertype](https://archive.ics.uci.edu/ml/datasets/covertype)
- https://archive.ics.uci.edu/ml/machine-learning-databases/covtype/covtype.data.gz --> unzip to same folder

[Sensorless Drive Diagnosis](https://archive.ics.uci.edu/ml/datasets/Dataset+for+Sensorless+Drive+Diagnosis)
- https://archive.ics.uci.edu/ml/machine-learning-databases/00325/Sensorless_drive_diagnosis.txt --> then rename to sdd.txt