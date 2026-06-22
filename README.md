# CIFAR-10 Image Classification using CNN (PyTorch)

A Convolutional Neural Network (CNN) built from scratch in PyTorch for image classification on the CIFAR-10 dataset.

## Results

- Test Accuracy: **71.08%**
- Dataset: CIFAR-10
- Epochs: 15
- Optimizer: Adam
- Learning Rate: 0.001

## Architecture

Conv2D(3 → 32, kernel_size=3)
↓
ReLU
↓
MaxPool2D(2×2)

Conv2D(32 → 64, kernel_size=3)
↓
ReLU
↓
MaxPool2D(2×2)

Conv2D(64 → 128, kernel_size=3)
↓
ReLU

Flatten (2048)

Linear(2048 → 128)
↓
ReLU

Linear(128 → 10)

## Dataset

CIFAR-10 contains 60,000 images across 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy

## Author

Svanik Soma
