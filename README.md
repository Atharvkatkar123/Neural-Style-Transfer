# Neural-Style-Transfer
This repository contains a PyTorch implementation of Neural Style Transfer, a technique to combine the content of one image with the style of another using Convolutional Neural Networks (CNNs). The model leverages the pre-trained VGG19 network to extract and blend the content and style features, producing visually stunning, artistic images.

Neural Style Transfer is an exciting application of deep learning that allows us to blend the content of one image with the style of another. This project uses the VGG19 network, pre-trained on the ImageNet dataset, to perform this task.

The main steps involved are:
1. **Feature Extraction**: Extract features from the content and style images using the VGG19 network.
2. **Gram Matrix Calculation**: Compute the Gram matrix for style features to capture style information.
3. **Loss Calculation**: Calculate the content and style loss to optimize the target image.
4. **Optimization**: Optimize the target image to minimize the total loss.

## Installation
To run this project, you'll need to have Python and the following packages installed:

- torch
- torchvision
- pillow
- matplotlib
- numpy

You can install the required packages using `pip`:
```bash
pip install torch torchvision pillow matplotlib numpy
