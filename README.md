# Project Details:

This repository demonstrates the implementation of Generative Adversarial Networks (GANs) for generating Pokémon images using the Pokémon images and types dataset. The GAN consists of a generator and a discriminator neural network, trained simultaneously in a competitive setting.

The dataset is prepared by downloading and preprocessing Pokémon images, including resizing, center cropping, converting to tensors, and normalization. The generator and discriminator models are then defined using convolutional and transpose convolutional layers, respectively.

The training process involves alternating between training the discriminator to distinguish between real and fake images and training the generator to generate more realistic images to fool the discriminator. The training progress is visualized through loss and score plots, as well as generated image samples.


# DataSet URL: 

https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types


