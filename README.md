# DCGAN-for-parametrization-and-image-generation

## Summary

Generation of geologically realistic and reliable predictive models, honoring both prior conceptual geological model and field measurements has always been one of key components of sound reservoir management workflow. Effective parametrization of geological models is one way of making it possible to generate geologically realistic and reliable predictive models. In this work, Deep Convolutional Generative Adversarial Networks (DCGAN) is proposed as a novel and effective method for the generation and parametrization of a binary facies channel model. Specifically, one representative training image for a channelized system is randomly sampled to generate training data for training the GAN. Once trained and tuned, GAN is used to generate unconditional geological models. Based on results, we can see that most of channel features from training image are reproduced, though there is a loss of some connectivity in generated models. Performance of proposed workflow is evaluated using some quantative methods and also compared with Variational Autoencoders (VAE) and Principal Component Analysis (PCA) based parametrization. GAN-generated models have been observed to have a higher quality.

## Workflow
![workflow_and_components](https://user-images.githubusercontent.com/68789630/147446231-558eb35c-81fd-47d1-a4ae-9b7a56bd3c07.jpg)

## Files
- project presentation
- project report
- code for GAN-based model generation
- code for VAE-based model generation
- code for PCA-based model generation





