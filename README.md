# PyTorch Image Classification

## Overview

This project implements a Convolutional Neural Network (CNN) for image classification using PyTorch. The primary goal is to classify handwritten digits using the MNIST dataset. The project includes the definition of the CNN architecture, a training script, and a function for making predictions on new images.  
  
Project is based on youtube video made by Nicholas Renotte -  
"https://www.youtube.com/watch?v=mozBidd58VQ&ab_channel=NicholasRenotte"

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
  - [Guess](#guess)
  - [Train](#train)


## Requirements

- Python 3.x
- PyTorch
- torchvision
- PIL (Pillow)

Install dependencies using:

```bash
pip install torch torchvision pillow
```

## Installation
```bash
git clone https://github.com/yourusername/guess-num-pytorch.git
cd guess-num-pytorch/guess-num-pytorch
```

## Project Structure
- torchnn.py: The main script containing the model definition, training loop, and inference functions.
- model_state.pt: The saved state of the trained model.
- data/: Directory where the MNIST dataset is downloaded and stored.
- img_1, img_2, img_3: example images

## Usage
### Guess
Run with proper argument in guess function 
### Train
Comment "Guessing part" and uncomment "Training part"
