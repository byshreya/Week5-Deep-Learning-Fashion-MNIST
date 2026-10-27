Deep Learning Application in Data Science

Fashion-MNIST Clothing Classification Using a Neural Network

Project Overview

This project applies deep learning to classify clothing images using the Fashion-MNIST dataset. A feedforward neural network was developed using TensorFlow and Keras to predict the category of each image.

Objectives

- Understand the basic working of a neural network.
- Preprocess image data for deep learning.
- Train a model to classify ten clothing categories.
- Evaluate model performance using classification metrics.
- Visualize training performance and predictions.

Dataset

Fashion-MNIST contains 70,000 grayscale clothing images, each measuring 28 × 28 pixels.

- Training images: 60,000
- Testing images: 10,000
- Categories: 10

The dataset was loaded directly through the TensorFlow Keras API.

Methodology

1. Loaded and normalized the image data.
2. Built a neural network using Flatten, Dense, and Dropout layers.
3. Trained the model for 15 epochs using the Adam optimizer.
4. Evaluated the model using test accuracy, weighted precision, weighted recall, and weighted F1-score.
5. Visualized the training curves, confusion matrix, and sample predictions.

Results

- Test accuracy: 87.83%
- Weighted precision: 87.99%
- Weighted recall: 87.83%
- Weighted F1-score: 87.65%

Tools and Libraries

Python, Google Colab, TensorFlow, Keras, NumPy, Pandas, Matplotlib, and Scikit-learn.

Project Files

The repository will contain the Colab notebook, evaluation metrics CSV, prediction results CSV, and project report.

Dataset Reference

https://github.com/zalandoresearch/fashion-mnist

Author

Shreya Dolui
