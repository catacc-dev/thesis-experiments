## Master's Thesis Experiments in Jupyter Notebooks

This repository contains the preliminary work and experiments for my master's thesis, focusing on medical image processing using the MONAI (Medical Open Network for AI) framework from NVIDIA.

<details>
<summary>Table of Contents</summary>

1. [About the Project](#about-the-project)
    - [Built With](#built-with)
    - [Processing experiment](#processing-synthrad2023-images)
    - [Autoencoder experiment](#autoencoder-implementation)
    - [Adversarial Autoencoder experiment](#adversarial-autoencoder)
    - [cGAN experiment](#conditional-gan-for-pix2pix)
2. [Getting Started](#getting-started)
   - [Installation](#installation)
3. [Contributing](#contributing)

</details>

## About the project
This project explores various deep learning approaches for medical image processing, including autoencoders, adversarial autoencoders (AAE), and conditional GANs, working with the SynthRad2023 dataset ([download the dataset](https://zenodo.org/records/7260705)).

### Built With
- MONAI
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

### Processing SynthRad2023 Images
- Data loading and preprocessing pipeline
- MONAI-specific preprocessing steps:
  - Channel-first conversion
  - Image resampling
  - MRI and CT normalisation (range: -1 to 1)
- Visualisation of image slices for quality control

### Autoencoder Implementation
- Basic autoencoder architecture
- Implementation using MONAI framework
- Training and evaluation experiments

### Adversarial Autoencoder
- Advanced implementation of Adversarial Autoencoders: a combination of autoencoder architecture with adversarial training

### Conditional GAN for Pix2Pix
- Implementation of cGAN architecture: Pix2Pix approach for medical image translation ([see the architecture](https://arxiv.org/abs/1611.07004))

## Getting started

### Installation
1. Clone the repo
   `git clone https://github.com/catacc-dev/thesis-experiments.git`
2. Create a virtual environment
    `python3 -m venv venv
    source venv/bin/activate      # Linux or macOS
    venv\Scripts\activate         # Windows`
3. Install packages
   `pip install monai tqdm SimpleITK pathlib os torch torchvision numpy matplotlib nibabel`

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
   
