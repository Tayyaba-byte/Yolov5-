Surface Defect Detection

This repository provides a framework for detecting surface defects using a deep learning approach. It includes all necessary scripts and data references to train and evaluate models efficiently.

Dataset:

https://figshare.com/articles/dataset/NEU-CLS/28903550

The coco128.yaml file includes all the necessary class details. In the above link the dataset is already pre-processed and ready to use with the training scripts provided

Training:

The model can be trained easily using the commands available in train.py. These commands allow you to customize parameters such as batch size, epochs, and data paths.
training command: python train.py --data-path ./data/COOC128 --epochs 50 --batch-size 16

Features:

Easy-to-use training script with configurable parameters
Support for COOC128 dataset out of the box
Modular design for quick experimentation with different models and hyperparameters
Output includes training logs, evaluation results, and visualizations
