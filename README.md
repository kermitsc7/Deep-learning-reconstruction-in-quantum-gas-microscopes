# Deep-learning-reconstruction-in-quantum-gas-microscopes

This project explores the development and application of an unsupervised deep learning algorithm focused on the field of ultracold atomic physics, specifically for the reconstruction of atomic occupancy in optical lattices using fluorescence images. The algorithm is implemented using autoencoders to accurately replicate the fluorescence images from quantum experiments, aiming to improve the speed and reliability of image reconstruction.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Configuration](#configuration)
5. [Use](#use)

## Introduction

This project focuses on the implementation and evaluation of deep learning models in the QUIONE quantum microscope at the Institute of Photonic Sciences (ICFO). The goal is to enhance the efficiency and accuracy of processing experimental images, contributing to the advancement of research in quantum phenomena and simulations.

## Features

- **PSF Calculation**: Calculate the Point Spread Function (PSF) of the optical system.
- **Optical Lattice Calculation**: Determine the optical lattice grid from fluorescence images.
- **Model Training**: Train autoencoders to reconstruct atomic occupancy from images.
- **Evaluation**: Evaluate the performance of the trained models on test data.

## Requirements

In order to run the notebooks you need to create a virtual environment by installing the ``requirements.txt`` file found in the ``config`` folder

## Configuration

Modify parameters for runs based on actual data
```

pixel_size = 16  #mu m
magnification = 126.7 
wavelength = 461 #nm

pixel_size_nm= (pixel_size*1000) / magnification
fwhm_nm = 470 

sigma_theorical = fwhm_nm / (2 * np.sqrt(2 * np.log(2)))
sigma_object_pixels = sigma_theorical / pixel_size_nm

```

## Use






