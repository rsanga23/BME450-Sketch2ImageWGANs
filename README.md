# BME450-Sketch2ImageWGANs

# Team
Rohan Sangameswaran (rsanga23)

# Description
This project explores the use of Generative Adversarial Networks (GANs) for sketch-to-image translation using the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 32x32 color images across 10 object categories, such as airplanes, cars, birds, and cats. In this project, the original color images will serve as the ground truth, while input sketches will be generated using OpenCV Canny edge detection applied to grayscale versions of the same images. May explore higher resolution versions of the dataset.

The goal is to train a conditional GAN (inspired by Pix2Pix) that can take these Canny edge maps as input and reconstruct the corresponding realistic color images. The model will be implemented  using PyTorch. We aim to evaluate the quality of generated images both visually and using similarity metrics.


