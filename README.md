# Image Classification using Transfer Learning

## Background
In recent years, image classification has become a significant area of research and application in computer vision. Traditional methods require substantial amounts of labeled data and computational resources to train deep learning models from scratch. Transfer learning, a technique where a pre-trained model is used as a starting point, has emerged as a powerful approach to overcome these challenges. It leverages the knowledge gained from large datasets and complex models, such as Inception, ResNet, MobileNet, and EfficientNet, to solve new tasks with limited data and computational resources.

## Goals
The primary goals of this project are:
1. To explore and implement transfer learning techniques using popular pre-trained models: Inception, ResNet, MobileNet, and EfficientNet.
2. To compare the performance of these models on a given image classification task.
3. To demonstrate the efficacy of transfer learning in improving classification accuracy with reduced training time and data requirements.
4. To provide a comprehensive guide and codebase for implementing transfer learning in image classification tasks.

## Method
The project is structured as follows:

### 1. Data Collection
- Collect a dataset for image classification. The dataset is collection of indianfood image (https://www.kaggle.com/datasets/l33tc0d3r/indian-food-classification)

### 2. Data Preprocessing
Load and preprocess the dataset. This includes resizing images, normalization, and data augmentation.
Use Keras' ImageDataGenerator for data augmentation to improve model generalization.


### 3. Model Selection and Implementation
Implement transfer learning using the following pre-trained models:
- InceptionV3: A deep convolutional neural network architecture known for its high accuracy on image classification tasks.
- ResNet50: A residual neural network that introduces skip connections to address the vanishing gradient problem.
- MobileNetV2: A lightweight deep learning model designed for mobile and embedded vision applications.
- EfficientNet: A family of models that scale up network width, depth, and resolution efficiently.
- Xception