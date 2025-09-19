# Image Colouring

Project developed by [Alejandro Cano Caldero](https://github.com/AlejandroCanoCaldero) and [Jesús Moncada Ramírez](https://github.com/jemonra) for the subject *Neural Networks and Deep Learning*, University of Padova, 2022-23.

## 1. Abstract

We present a method to tackle the image recoloring problem, namely assigning RGB values to grayscale pixels. Not only will this paper show how this problem can be handled by implementing a UNET Autoencoder and Patch GAN, but it will also showcase an important enhancement provided by additional perceptual losses and the implementation of a W-GAN network with gradient penalty. These tools will prove to match human perception well and give higher stability to the training model, respectively. To visualize the progress that has been made, we will gradually attach the refinements previously mentioned and the given results to show how the final implementation outperforms the rest.

## 2. Trained models

We trained some models with a 500-sample training set from [Imagenette](https://github.com/fastai/imagenette).

## 3. Some results

Some results of our work are the following. For this input image:

![Input image](/results/input_image_1.png "Input image")

The image recoloring architecture produced the recolored image:

![Result](/results/result_1.png "Results")

## 4. Paper

We have also created a [paper](docs/ImageRecoloringWithConditionalGANs.pdf) explaining all the work done, the theory behind the models, and the obtained results.

## 5. Interesting links

Some interesting links that helped us to understand the covered problem:
- [(Video) Image to image translation using Pix2Pix GAN](https://www.youtube.com/watch?v=UcHe0xiuvpg)
- [(Video) Satellite image to maps translation using pix2pix GAN](https://www.youtube.com/watch?v=6pUSZgPJ3Yg)
- [Pix2Pix:Image-to-Image Translation in PyTorch & TensorFlow](https://learnopencv.com/paired-image-to-image-translation-pix2pix/#discriminator)
- [Introduction to Generative Adversarial Netowrks (GANs)](https://learnopencv.com/introduction-to-generative-adversarial-networks/)
- [Conditional GAN (cGAN) in PyTorch and TensorFlow](https://learnopencv.com/conditional-gan-cgan-in-pytorch-and-tensorflow/)


