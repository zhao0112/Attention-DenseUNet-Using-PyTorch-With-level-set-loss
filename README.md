# Attention-DenseUNet-Using-PyTorch-With-level-set-loss
# Overview
This repository contains a Python script for a deep learning-based image segmentation task. The code utilizes PyTorch, Segmentation Models PyTorch, NumPy, and Pandas to create and train a segmentation model.

# Requirements
The required Python libraries are:

PyTorch
Segmentation Models PyTorch
NumPy
Pandas
torchvision
PIL (Python Imaging Library)
sklearn
matplotlib
tqdm
zipfile
glob
Data
The dataset is expected to be a zip file consisting of RGB images and their corresponding segmentation masks. The code will automatically extract the data from the zip file. The data should be located in a directory named "input" and the extracted files will be stored in a directory named "working".

# Usage
The code is divided into several sections:
Importing necessary libraries: This includes PyTorch and other data processing libraries.
Configuration: Configurations like batch size, learning rate, epochs, image size, etc., are set.
Data Extraction: The train data from a zip file is extracted.
Data Loading: The train and validation datasets are created using a custom MyDataset class, which inherits from PyTorch's Dataset class.
Data Visualization: A couple of sample images and masks from the train dataset are visualized.
The provided code does not include the model definition and training loop. You will need to add your own model definition and training routine.

For running the code, you just need to run the Python script (either in a Python environment or a Jupyter notebook). Make sure you have access to the GPU for faster computation.
