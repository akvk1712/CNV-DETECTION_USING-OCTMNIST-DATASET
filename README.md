
# About
CNV Classification with Interpretability and Style Transfer
This repository explores different approaches to CNV (Copy Number Variation) classification in OCT (Optical Coherence Tomography) images, emphasizing model interpretability and style transfer.

# Key functionalities:

Train and evaluate CNN models: Implement and compare various CNN architectures for CNV classification.
Leverage pre-trained features: Employ VGG16 and ResNet50 for feature extraction.
Explain predictions with LIME: Visualize regions influencing model decisions using LIME.
Generate stylized images: Use CycleGAN for content-preserving style transfer.

# Code structure:

data_loader.py: Loads and preprocesses OCT image data.
models.py: Defines various CNN architectures for CNV classification.
training.py: Trains and evaluates models with early stopping.
evaluation.py: Calculates and compares performance metrics.
lime_visualization.py: Visualizes LIME explanations for model predictions.
style_transfer.py: Implements CycleGAN for content-preserving style transfer.

# Prerequisites:

Python 3.6+
TensorFlow
Keras
scikit-learn
Lime
matplotlib
pandas
(Optional) CycleGAN pre-trained model

# DATASET
The OCTMNIST dataset contains 138,186 retinal OCT images with 2 categories: CNV (Choroidal Neovascularization) and normal.

Here is a breakdown of the dataset size:

Training set: 102,940 images (74.5%)
Validation set: 17,128 images (12.4%)
Test set: 18,118 images (13.1%)

The code followed by " #dataset code " represents the code required to load the data from the OCTMNIST Dataset.