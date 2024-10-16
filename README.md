# PRODIGY_ML_03
# Cats vs Dogs Classification using SVM

This project uses Support Vector Machines (SVM) to classify images of cats and dogs. The images are preprocessed, flattened, and passed through an SVM classifier to predict whether an image contains a cat or dog.

# Overview
This project demonstrates the use of a Support Vector Machine (SVM) for image classification. We work with the popular Kaggle Dogs vs. Cats dataset, training a binary classifier to predict whether an image contains a cat or a dog.

The images are resized, normalized, and then flattened before being passed into the SVM. The model aims to achieve high classification accuracy using this supervised learning approach.

# Dataset
The dataset used in this project is the Dogs vs. Cats dataset, which contains 25,000 images of cats and dogs in a 50/50 ratio.To download the dataset, you will need to authenticate using the Kaggle API. 

  Follow these steps:
    1. Sign up for a Kaggle account if you don't have one: https://www.kaggle.com.
    2. Generate your API key
    3. Place the kaggle.json file in the correct directory If you are working locally.For Google Colab, you can upload the kaggle.json file manually using
    
  # Reduce Dataset Size if Needed:
    If the training process takes too long (e.g., more than 1 hour), you can reduce the number of images being used. Before splitting the dataset, you can randomly sample a subset of the data to speed up the training. For example, reducing the number of images to 10,000     or 5,000 may significantly improve training time without compromising much on performance.

# Installation
To run this project, you will need the following dependencies:

  1. Python 3.x
  2. Jupyter Notebook (or Google Colab)
  3. Libraries:
        numpy
        scikit-learn
        opencv-python
        matplotlib
        pandas

# Future Improvements
  1. Increase Image Resolution: Use larger image sizes (e.g., 128x128) to capture more details.
  2. Feature Engineering: Apply techniques like HOG (Histogram of Oriented Gradients) for better feature extraction.
  3. Hyperparameter Tuning: Experiment with different kernels (e.g., RBF) and regularization parameters.
  4. Explore Other Models: Try using deep learning models like Convolutional Neural Networks (CNNs) for more complex image classification.
