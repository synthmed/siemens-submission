# Synthetic Medical Images from Dual Generative Adversarial Networks: A Solution to the Scarcity and Privacy of Medical Data for Deep Learning

Source code for the 2017 Siemens Science Fair Competition.

Our code is split into two stages: a segmentation-mask-generating DCGAN, and an image-to-image translator using pix2pix.

Run code through Jupyter Notebook.

# Prerequisites
- Python 2 and 3
- numpy
- [TensorFlow](https://www.tensorflow.org/install/) 1.0+
- Keras
- **Preprocessed dataset**

# Abstract 

Currently there is strong interest in data-driven approaches to medical image classification. However, medical imaging data is scarce, expensive, and fraught with legal concerns regarding patient privacy. Typical consent forms only allow for patient data to be used in medical journals or education, meaning the majority of medical data is inaccessible for public research.


We propose a novel, two-stage pipeline for generating synthetic medical images from a pair of generative adversarial networks, tested in practice on retinal fundi images. We develop a hierarchical generation process to divide the complex image generation task into two parts: geometry and photorealism.


The effectiveness of our synthetic data was proven by an F1 score of **0.8877**, in comparison to **0.8988** on real data, showing a negligible difference between the two datasets.


We hope researchers will use our pipeline to bring medical data into the public domain, sparking growth in imaging tasks that have previously relied on the hand-tuning of models. We have begun this initiative through the development of SynthMed, an online repository for synthetic medical images.


# Figures

![Imgur Image](https://i.imgur.com/KIUQYbc.jpg)

![Imgur Image](https://i.imgur.com/0kyBN4e.png)


Acknowledgements:

Stage-I GAN based on: https://github.com/carpedm20/DCGAN-tensorflow
<br></br>
Stage-II GAN based on: https://github.com/ray0809/pix2pix
