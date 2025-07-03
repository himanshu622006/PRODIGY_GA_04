# PRODIGY_GA_04

# Task Number-4: Image-to-Image Translation with cGAN

This project demonstrates image-to-image translation using conditional Generative Adversarial Networks (cGANs). A cGAN learns to transform input images into corresponding output images by conditioning both the generator and discriminator on additional information — typically an image or label map.

## Repository Features

The repository includes:

1. Implementation of a conditional GAN (cGAN) architecture using PyTorch or TensorFlow.
2. Training pipeline for paired datasets (e.g., edges → photos, maps → satellite views).
3. Preprocessing scripts for input and target images.
4. Inference script for generating new images from unseen inputs.
5. Visualization tools to compare input, generated, and ground-truth images.

## Use Cases

- Edges to photo-realistic image translation  
- Maps to satellite images  
- Day-to-night or sketch-to-color conversions  
- Style and attribute transfer between paired image domains

## Purpose

This project helps explore how conditional GANs can be used for supervised image-to-image translation tasks. It highlights the potential of generative models in computer vision for real-world applications such as data augmentation, artistic rendering, and scene transformation.
