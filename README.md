# Cat-vs-Dog Image Classification

## Overview

This project focuses on image classification to distinguish between cats and dogs using a Convolutional Neural Network (CNN). The dataset comprises two folders - 'train' and 'test,' each containing 10,000 dog and cat images in 'train' and 2,500 images in 'test.'

## Accessing Files

1. Obtain Kaggle API Token:
   - Go to your Kaggle profile >> account >> Create a new API token.
   - Save the generated JSON file on your local machine.

2. Uploading Token to Google Colab:
   - Open the IPython notebook (ipynb) file in Google Colab.
   - Upload the Kaggle API token in the files section.

3. Dataset Retrieval:
   - Visit the dataset link on Kaggle.
   - Click on the three dots (ellipsis) on the right-hand side and copy the API command.
   - Replace the API command in the ipynb file with your specific command and run the file.

## Project Details

### CNN Architecture:
- An initial CNN architecture was created, but it exhibited overfitting.

### Overfitting Mitigation:
- Batch normalization and dropout layers with a dropout rate of 0.2 were introduced to mitigate overfitting.

### Model Refinement:
- To further reduce overfitting, the dropout rate was increased to 0.4.
- Achieved a model with 75% training accuracy and 78% testing accuracy.

## Instructions for Replication

1. Ensure the Kaggle API token is uploaded to the Google Colab environment.
2. Replace the API command in the provided IPython notebook with your specific command.
3. Run the notebook to reproduce the CNN architecture, training, and testing phases.

## Acknowledgments

- [Dataset Source](https://www.kaggle.com/datasets/salader/dogs-vs-cats)

Feel free to contribute, suggest improvements, or use this project as a foundation for further exploration into image classification.
