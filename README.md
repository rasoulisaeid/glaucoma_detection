# Glaucoma Detection with Deep Learning

This repository contains a Jupyter notebook that demonstrates how to detect Glaucoma using a deep learning model. The model is trained and evaluated on a dataset of eye images, with a focus on the optic cup and disc, which are key indicators of the disease.

## Methodology

The process begins with preprocessing steps to prepare the images for analysis. This includes cropping each image to focus on the smaller region that contains the optic cup and disc.

The preprocessed images are then used to train a VGG19 model, a convolutional neural network that has shown high performance in image recognition tasks. The model is implemented using PyTorch, a popular framework for deep learning.

We employ a **transfer learning** approach, leveraging a **pretrained VGG19 model**. This allows us to take advantage of the features learned from large datasets and apply them to our specific task, improving the model's performance and reducing training time.

## Dataset

The [dataset](https://www.kaggle.com/datasets/sshikamaru/glaucoma-detection/data) used in this project is sourced from Kaggle. You can access it here. It contains images of eyes affected by Glaucoma, as well as healthy eyes.
