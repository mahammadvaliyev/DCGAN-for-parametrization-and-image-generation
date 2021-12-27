# DCGAN-for-parametrization-and-image-generation

Generation of geologically realistic and reliable predictive models, honoring both prior conceptual geological model and field measurements has always been one of key components of sound reservoir management workflow. Effective parametrization of geological models is one way of making it possible to generate geologically realistic and reliable predictive models. In this work, Deep Convolutional Generative Adversarial Networks (DCGAN) is proposed as a novel and effective method for the generation and parametrization of a binary facies channel model. Specifically, one representative training image for a channelized system is randomly sampled to generate training data for training the GAN. Once trained and tuned, GAN is used to generate unconditional geological models. 

## Workflow

![workflow](https://user-images.githubusercontent.com/68789630/147445917-e887a19e-2b54-4551-a0c0-82c9deb78b88.JPG)

Based on results, we can see that most of channel features from training image are reproduced, though there is a loss of some connectivity in generated models. Performance of proposed workflow is evaluated using some quantative methods and also compared with Variational Autoencoders (VAE) and Principal Component Analysis (PCA) based parametrization. GAN-generated models have been observed to have a higher quality.


