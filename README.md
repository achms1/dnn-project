# dnn-project
Implementation of Conditional Generative Adversarial Network over Fashion - MNIST dataset


1) Training of GAN can be done using either .ipynb or src code files. Both of them contains sections for training generator model and testing Generator.
2) Generator Model trained on Collab is saved into CGAN_199_G.pt.
3) Also, all the images for each class are collected and saved into classes directory. These are the test images used in AutoEncoder.
4) Autoencoder model is also saved into autoencoder.h5 files.
5) User can run AutoEncoder-CGAN-Final to verify similarity(cosine similarity) to training images.
6) User can run AutoEncoder-CGAN-Final_ED_CS.ipynb to verify both similarity(cosine similarity) and Euclidean distance similarity to training images.
