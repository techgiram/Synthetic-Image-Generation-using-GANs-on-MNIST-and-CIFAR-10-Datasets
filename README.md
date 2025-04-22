# Synthetic-Image-Generation-using-GANs-on-MNIST-and-CIFAR-10-Datasets

This script trains a simple neural network on the MNIST dataset and predicts handwritten digits from external images.

## 🧠 Model
- Input: 28x28 grayscale images
- Network: 2 hidden layers (128 and 64 neurons)
- Output: 10 classes (digits 0-9)

## 🏁 How to Run
1. Train and evaluate model:
```
python mnist_digit_predictor.py
```

2. Add your custom digit images (28x28 pixels, grayscale PNG/JPG) into the `digits/` folder.

3. The model will predict each digit and print results.

Make sure images are 28x28 pixels for accurate predictions.
