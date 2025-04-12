# Orange-or-Grape-Classification_Simple-Deep-Learning

# Classification of binary class orange or grape with simple deep learning

This project involves the classification of oranges and grapefruits based on three key features: color, weight, and diameter. The dataset is created artificially by generating a variety of samples representing oranges and grapefruits, and the goal is to develop a machine learning model that can accurately distinguish between the two fruits.

### Dataset Source:
[Oranges vs Grapefruit Dataset on Kaggle](https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit)

## Dataset Overview

The dataset contains fictional data where each sample represents either an orange or a grapefruit. The features used for classification are:

- **Color**: An average value representing the color of the fruit.
- **Weight**: The weight of the fruit in grams.
- **Diameter**: The diameter of the fruit in centimeters.

While the dataset is mostly fictional, it serves as a great learning tool for binary classification problems.

## Project Goals

The goal of this project is to build a binary classification model that can classify fruit samples as either an "orange" or a "grapefruit" based on the provided features.

## Model Results

### Training Results:
- **Epochs**: 50
- **Accuracy**: 93.21%
- **Loss**: 0.1624

### Testing Results:
- **Accuracy**: 92.52%
- **Loss**: 0.1920
- **Final Model Performance**: 92.13% accuracy


## Future Improvements

- **Data Augmentation**: In the future, we can use real-world data and apply augmentation techniques to increase the size and variety of the dataset.
- **Hyperparameter Tuning**: Experimenting with different hyperparameters to further improve the model's accuracy.
- **Real-time Predictions**: Implementing a live model for classifying new fruit samples based on color, weight, and diameter.
