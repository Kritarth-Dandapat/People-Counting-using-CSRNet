# People-Counting-using-CSRNet

This project implements a people counting model based on the CSRNet (Congested Scene Recognition Network) architecture, as described in the paper "[CSRNet: Dilated Convolutional Neural Networks for Understanding the Highly Congested Scenes](https://arxiv.org/abs/1802.10062)" by Yuhong Li, Xiaofan Zhang, and Deming Chen.

## Overview

People counting is a crucial task in various applications, such as crowd monitoring, public safety, and urban planning. Traditional methods struggle in highly congested scenes, where overlapping and occlusion occur frequently. CSRNet addresses this issue using a convolutional neural network with dilated convolutions, allowing it to capture both local and global features effectively.

This repository contains the implementation of the CSRNet model and demonstrates its application for counting people in crowded scenes.

## Features

- **CSRNet Architecture:** The model is built according to the CSRNet paper, utilizing dilated convolutions to improve feature extraction.
- **Preprocessing:** The data is preprocessed to normalize and standardize images, and density maps are generated to train the model.
- **Training & Evaluation:** The model is trained on a dataset with annotated head positions, and its performance is evaluated based on the mean absolute error (MAE) and mean squared error (MSE).

## Requirements

To run the code in this repository, you'll need the following libraries:

- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`
- `scipy`
- `Pillow`

You can install the necessary dependencies using `pip`:

```bash
pip install tensorflow keras numpy matplotlib scipy pillow
