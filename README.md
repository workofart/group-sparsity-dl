# Benefit of Group Sparsity in Deep Learning

We will apply some non-deep learning classification algorithms as well as many deep learning algorithms with or without group sparsity on some real datasets. Our goal is to show the benefits of group sparsity in deep learning: **significantly reduce the number of parameters while preserve a good accuracy**. We will also include some brief discussion on theoretical properties of group sparsity.

---

## Authors
*Kan Chen, Zongyu Dai, Hanxiang (Henry) Pan, Yue Sheng*


## How to run

Please find the implementation and experiments in `Project Experiments.ipynb`.


## Dependencies

Please note that the notebook is run with a freshly installed Python `3.6.9` environment with the dependencies defined in `requirements.txt`.



## Dataset

**Please find the datasets in the following links:**
- https://archive.ics.uci.edu/ml/machine-learning-databases/00325/Sensorless_drive_diagnosis.txt --> then rename to sdd.txt
- https://archive.ics.uci.edu/ml/machine-learning-databases/covtype/covtype.data.gz --> unzip to same folder
- MNIST should be downloaded automatically through Pytorch
