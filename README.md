# Deep-learning-reconstruction-in-quantum-gas-microscopes

This project explores the development and application of an unsupervised deep learning algorithm focused on the field of ultracold atomic physics, specifically for the reconstruction of atomic occupancy in optical lattices using fluorescence images. The algorithm is implemented using autoencoders to accurately replicate the fluorescence images from quantum experiments, aiming to improve the speed and reliability of image reconstruction.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Usage](#usage)
4. [Examples](#examples)
5. [Configuration](#configuration)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgements](#acknowledgements)

## Introduction

This project focuses on the implementation and evaluation of deep learning models in the QUIONE quantum microscope at the Institute of Photonic Sciences (ICFO). The goal is to enhance the efficiency and accuracy of processing experimental images, contributing to the advancement of research in quantum phenomena and simulations.

## Features

- **PSF Calculation**: Calculate the Point Spread Function (PSF) of the optical system.
- **Optical Lattice Calculation**: Determine the optical lattice grid from fluorescence images.
- **Model Training**: Train autoencoders to reconstruct atomic occupancy from images.
- **Evaluation**: Evaluate the performance of the trained models on test data.
