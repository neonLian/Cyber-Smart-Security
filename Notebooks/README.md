Note: each model has multiple notebooks numbered in order. These notebooks are mostly copies of each other, with small changes to test different training approaches (such as hyperparameters, binary vs multiclass prediction).

### General
Contains code to preprocess the data and use the ADASYN algorithm to balance the number of each prediction class in the data.

### Machine Learning
Contains training code for Decision Trees, GBTs, KNN, logistic regression, SVMs, Random Forests.

### Dense Neural Networks
Contains training code for the multilayer perceptron networks. 

### Conv Networks
Contains training code for using convolutional neural networks on a version of the data converted to images.

### Recurrent Neural Networks
Contains training code for using recurrent neural networks.

### Ensemble
Contains code testing ensembles of multiple of the other models working in unison. This did not prove effective so it was not included in the presentation.

### PCAPs
Exploration of the raw PCAP data. The training code described above used the version of the IDS2017 dataset with pre-extracted features, not the raw packet data.