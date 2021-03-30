# Udacity Machine Learning Engineer Nanodegree Capstone Project

## Purpose

This repo serves as a storage location for the proposal, report, and data for final submission of the Capstone Project of the Udacity Machine Learning Engineer Nanodegree.

## Data

All data used in this project can be found in the `data` folder. If you try to reproduce the results in `Capstone.ipynb`, you will need to update the "real" images in the folders `data/train`, `data/val`, and `data/test`, replacing them with the corresponding data from the folders in `real_round1`. Other than that, you should be able to run the notebooks as-is. See the following section for a caveat to that.

## Training Details

Please note that the models were originally trained on CPU-based instances in Amazon Sagemaker. The SVM classifier was trained using a more powerful instance, so you may run out of memory depending on what machine you use to run that notebook.

## Software Libraries Used

The following Python packages were used in this project. Most were available in the `conda_pytorch_py36` kernal available in Amazon SageMaker.
* Matplotlib
* NumPy
* PyTorch
* requests