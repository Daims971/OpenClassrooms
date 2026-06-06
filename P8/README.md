# Project 8: Kaggle Competition : GAN

This is the documentation for project number 8.
The github link for versioning can be found at: Daims971/gan_project (github.com)
The Kaggle Kernel can be found at : P8_GAN_032023 | Kaggle
Other useful Kernel :
-	gan_project/p8-gan-032023-train-and-save.ipynb at Dev · Daims971/gan_project (github.com)
-	gan_project/p8-gan-202303-generate-img.ipynb at Dev · Daims971/gan_project (github.com)

#### English
#### Context of project

The main purpose of this competition is to make a GAN that will be able to generate between 7000 and 10000 images with the style of the famous painter Monet.
The generated images have to be jpg format with a size of 256x256x3 (RGB) and be zipped in a single file named images.zip.
The evaluation metric used by kaggle to know if the image is considered good is MiFD: 
- Memorization-informed Fréchet Inception Distance.

The smaller MiFID is, the better your generated images are.

More details can be found at: Kaggle Competition.
A notebook that allows to well start this challenge is the Notebook of de Amy Jang:
- https://www.kaggle.com/amyjang/monet-cyclegan-tutorial

This notebook gives basis of how data will be loaded inside a kaggle notebook. The method used in this notebbok to kgenerate images is called cycleGAN, that we won't use for the time being.

Another notebook that allows to manage the development and the training of a GAN is from Tensorflow tutorial:
- Deep Convolutional Generative Adversarial Network  |  TensorFlow Core
Some ideas of models to design for the generator and the discriminator of the GAN could be found at these links:
- Building a Generative Adversarial Network using Keras - GeeksforGeeks
- pix2pix: Image-to-image translation with a conditional GAN  |  TensorFlow Core

#### The table of content for the study of the notebook P8_GAN which goal is to load data, make the GAN and train is as follow:

1. Introduction to GAN
2. Competiton context
3. Data preparation
4. Model preparation
    4.1. Different type of Neural Networks
    4.2. Evaluation of time generation
    4.3. Build the GAN
5. Train the GAN
6. Test the GAN

