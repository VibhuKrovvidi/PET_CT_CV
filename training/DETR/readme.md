# Pretrained Model Weights

Pretrained weights for the model are available at the following location. Access to these weights requires Lion Mail credentials.

**Google Drive Link:** [Pretrained Model Weights](https://drive.google.com/drive/folders/1RvKHOoLgnDI8mVpi5H7Q3Rf5D7cejlMd?usp=sharing)

Please ensure that you are signed in with your Lion Mail account to access and download the pretrained weights.

## Model and Dataset Information

| Sr No | Model Name          | Dataset Type   |
|-------|---------------------|----------------|
| 1     | Conditional DETR   | SUV            |
| 2     | Conditional DETR   | CT             |
| 3     | Conditional DETR   | K Means        |
| 4     | Conditional DETR   | SUV Positive   |
| 5     | Conditional DETR   | Stacked        |
| 6     | Conditional DETR   | Stacked Positive |

## Driver Code

This repository contains the driver code for running the training example of Conditional DETR.

## Hyperparameters

| Hyperparameter          | Value                  |
|--------------------------|------------------------|
| Learning Rate (Detr)     | \(1 \times 10^{-4}\)   |
| Learning Rate (Backbone) | \(1 \times 10^{-5}\)   |
| Weight Decay             | \(1 \times 10^{-4}\)   |
| Image Dimensions (DIM)  | 408                    |
| Batch Size               | 8                      |
| Pin Memory               | True                   |
| Number of Workers        | 12                     |


## Environment Specifications

| GPU Type | GPU Memory | RAM    |
|----------|------------|--------|
| L4 GPU   | 24 GB      | 48 GB  |

Refer requirements.txt to setup infrastructure on GCP 
