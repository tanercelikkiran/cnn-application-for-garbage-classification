# CNN Application for Garbage Classification

## Introduction

This is a simple application of CNN for garbage classification. The dataset is from [Kaggle](https://www.kaggle.com/asdasdasasdas/garbage-classification). With the help of CNN, a garbage that is not in the dataset can be classified with a high accuracy rate.

## Dataset

The dataset contains 6 classes of garbage: cardboard, glass, metal, paper, plastic, and trash. Each photo is 512x384 pixels. It contains 2527 photos in total. For each class, there are various types of garbage. For example, the class "cardboard" contains 393 photos of different types of cardboard such as flat cardboard, paper bag, etc.

## Model

The model is a simple CNN model with 3 convolutional layers and 2 fully connected layers. The accuracy rate is 0.90 for 15 epochs with the given seeds.

## Requirements

- Python 3.6 or above
- Tensorflow
- Pathlib
- Jupyter Notebook

or

- Google Colab

## Usage

1. Download the dataset from [Kaggle](https://www.kaggle.com/asdasdasasdas/garbage-classification) and put it in the same directory as the code.
2. Open the code in Jupyter Notebook or Google Colab
3. Run the code cell by cell