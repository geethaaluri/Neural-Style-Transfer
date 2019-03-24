# Neural-Style-Transfer
Style transfer using Convolutional Neural Networks and Vgg

Style transfer is a technique where we use deep learning to compose an image in the style of another image.

We can take an input image and the style image that we want to match. We can use neural networks to  transform the base input image by minimizing the content and style distances (losses) with backpropagation, creating an image that matches the content of the base image and the style of the style image. In this project, the network architecture used is VGG19, a pretrained image classification network.
