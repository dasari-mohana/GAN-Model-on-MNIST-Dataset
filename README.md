# GAN-Model-on-MNIST-Dataset

## Aim

To build Generative Adversarial Networks in PyTorch and to generate synthetic MNIST images (images of 0-9 digits)

## Data Description

The MNIST database of handwritten digits comprises a training set of 60,000 samples and a test set of 10,000 examples. It can be accessed via this link (http://yann.lecun.com/exdb/mnist/). It is a portion of a larger set that is made public by NIST. The digits have been centred in a fixed-size image and size-normalized. In addition, the NIST black and white photos were anti-aliased, which added grayscale levels, and normalised to fit within a 28x28 pixel bounding box.

## Tech stack

 -> Language - Python

 -> Libraries: torch, torchvision, numpy, matplotlib

## My Approach

1. Import the required libraries.

2. Function to transform and load the data with Torch

3. Build Generator network

4. Build Discriminator network

5. Function to train the model using PyTorch

6. Defining Model Parameters

7. Training the model

8. Function to plot the image

9. Generationg fake image from random noise

## Project code overview

1. data folder - It contains data_utils.py file which is used to download and transform the data. It will download and store the data in the respective folder

2. model folder - contains gan.py, train.py, and run.py.

    a. gan.py - The Generator and Discriminator classes are constructed.

    b. train.py - contain the code for model training.

    c. run.py - It is the main file in which all functions are called.

3. GAN_MNIST.ipynb - It is .ipythonnotebook which is used to train themodel and generated synthetic images (I used Colab GPU for training).

4. The requirements.txt file has all the required libraries with respective versions. Install the file by using the command 

`pip install -r requirements.txt`
