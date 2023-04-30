# Dog Breed Neural Network

This repository contains code for building and training a machine learning model that can classify images of dogs into different breeds using PyTorch resnet50.

## Overview

The goal of this project is to build a neural network that can accurately classify a given dog image into its corresponding breed with a high degree of confidence. The model uses the resnet50 architecture from PyTorch as its backbone and is trained on a dataset of labeled dog images.

## Usage

The dog_reco.pt has been trained on the dataset.

## Performance

The model currently achieves a test accuracy of 80% on the provided test dataset. However, this accuracy may vary depending on the dataset and the specific problem being addressed.

## Integration

This dog breed classifier has been integrated into an iOS app in another repository. The app allows users to take a picture of a dog and get the predicted breed using the trained model. The integration was done using CoreML to convert the PyTorch model to a format that can be used in an iOS app.
[dog-recognizer](https://github.com/max044/dog-recognizer)

## Future Work

There are several areas where this project could be improved. For example, more data could be collected and added to the dataset to improve the model's performance. The model architecture and hyperparameters could also be fine-tuned to improve accuracy. Additionally, the model could be deployed to a web API to allow it to be used in other applications.
Moreover, the dataset is clean and boundbox are used to separates dogs on image.
