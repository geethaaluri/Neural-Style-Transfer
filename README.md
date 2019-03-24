# Neural-Style-Transfer
Style transfer using Convolutional Neural Networks and Vgg

Style transfer is a technique where we use deep learning to compose an image in the style of another image.

We can take an input image and the style image that we want to match. We can use neural networks to  transform the base input image by minimizing the content and style distances (losses) with backpropagation, creating an image that matches the content of the base image and the style of the style image. In this project, the network architecture used is VGG19, a pretrained image classification network.

Here is the style image I am going to use:
![style2](https://user-images.githubusercontent.com/48276005/54877025-8b7bd780-4dd6-11e9-85a5-113a4d2f6433.jpg)

Here is the base input image:
![original2](https://user-images.githubusercontent.com/48276005/54877050-d72e8100-4dd6-11e9-9774-1c9f82eac6fd.jpg)

Here is my output image with the style in it!
![neural_city_at_iteration_9](https://user-images.githubusercontent.com/48276005/54877052-dc8bcb80-4dd6-11e9-829b-2549fa946717.png)
