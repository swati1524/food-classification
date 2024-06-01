# Food Vision Big™

Food Vision Big™ is an advanced food image classification model built using the entire Food101 dataset. This project builds upon previous work in transfer learning, particularly "Transfer Learning Part 3: Scaling Up," where we created *Food Vision Mini*. With Food Vision Mini, we surpassed the original results of the Food101 paper using only 10% of the data. Now, we're scaling up to use the full dataset.

## Objective

The primary objective of this project is to build a powerful food classification model using the entire Food101 dataset. Our goal is to surpass the performance of *DeepFood*, a 2016 paper that achieved 77.4% top-1 accuracy using a Convolutional Neural Network trained for 2-3 days.

## Dataset

- *Training Images*: 75,750
- *Testing Images*: 25,250

## Project Goals

- Beat the top-1 accuracy of 77.4% achieved by DeepFood.

## Features

1. *Data Download and Exploration*
   - Utilizes TensorFlow Datasets to download and explore the Food101 dataset.
   
2. *Data Preprocessing*
   - Creates preprocessing functions for efficient data preparation.
   
3. *Dataset Preparation*
   - Batching and preparing datasets to ensure optimal performance.
   
4. *Modeling Callbacks*
   - Implements callbacks to monitor and enhance the training process.
   
5. *Mixed Precision Training*
   - Sets up mixed precision training for faster and more efficient model training.
   
6. *Feature Extraction Model*
   - Builds a feature extraction model as outlined in "Transfer Learning Part 1: Feature Extraction."
   
7. *Model Fine-Tuning*
   - Fine-tunes the feature extraction model as detailed in "Transfer Learning Part 2: Fine-Tuning."
   
8. *Training Visualization*
   - Uses TensorBoard to visualize and analyze training results.
