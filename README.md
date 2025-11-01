# Master's Thesis Experiments in Jupyter Notebooks

This repository contains the preliminary work and experiments for my master's thesis, focusing on medical image processing using the MONAI (Medical Open Network for AI) framework.

## Project Overview
This project explores various deep learning approaches for medical image processing, including autoencoders, adversarial autoencoders (AAE), and conditional GANs, specifically working with the SynthRad2023 dataset (https://zenodo.org/records/7260705).

## Table of Contents
- [Processing experiment](#processing-synthrad-2023-images)
- [Autoenconder experiment](#autoencoder-implementation)
- [Adversarial Autoencoder experiment](#adversarial-autoencoder)
- [cGAN experiment](#conditional-GAN-for-Pix2Pix)

## 1. Processing SynthRad2023 Images
- Data loading and preprocessing pipeline
- MONAI-specific preprocessing steps:
  - Channel-first conversion
  - Image resampling
  - MRI and CT normalization (range: -1 to 1)
- Visualization of image slices for quality control

## 2. Autoencoder Implementation
- Basic autoencoder architecture for medical image processing
- Implementation using MONAI framework
- Training and evaluation experiments

## 3. Adversarial Autoencoder
- Advanced implementation of Adversarial Autoencoders
- Combination of autoencoder architecture with adversarial training
- Experiments with latent space manipulation

## 4. Conditional GAN for Pix2Pix
- Implementation of cGAN architecture from https://arxiv.org/abs/1611.07004
- Pix2Pix approach for medical image translation
- Application to SynthRad 2023 dataset

## Dependencies
- MONAI
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook
