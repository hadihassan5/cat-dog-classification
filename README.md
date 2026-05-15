# 🐱🐶 Cat vs Dog Classification

This notebook shows how to tell cat and dog pictures apart using TensorFlow.

## 🚀 Project Overview

- **Dataset:** `cats_vs_dogs`
- **Model:** `MobileNetV2`
- **Image size:** `224 x 224`
- **Goal:** Predict cat or dog

## 🔧 What the Notebook Does

1. Loads the cat and dog images
2. Splits data into training and test groups
3. Resizes images and scales pixel values
4. Builds a model with a pre-trained MobileNetV2 base
5. Trains the model and checks accuracy
6. Shows a plot of training and validation accuracy
7. Uses the model to guess if a new image is a cat or dog

## ✅ Requirements

- Python 3.8 or newer
- TensorFlow
- TensorFlow Datasets
- Matplotlib
- NumPy

## ▶️ Usage

1. Open `cat_dog_DL_Classification.ipynb`
2. Run each cell in order
3. Upload an image to try the model
4. It prints `🐶 Dog Detected` or `🐱 Cat Detected`

## 💡 Notes

- The notebook uses MobileNetV2 without training its base layers.
- You can get better results by training more layers or running more epochs.
- The prediction step uses a Google Colab-style upload.
