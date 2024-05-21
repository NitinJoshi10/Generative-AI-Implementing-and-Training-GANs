# Project Details:

This repository demonstrates the implementation of Generative Adversarial Networks (GANs) for generating Pokémon images using the Pokémon images and types dataset. The GAN consists of a generator and a discriminator neural network, trained simultaneously in a competitive setting.

The dataset is prepared by downloading and preprocessing Pokémon images, including resizing, center cropping, converting to tensors, and normalization. The generator and discriminator models are then defined using convolutional and transpose convolutional layers, respectively.

The training process involves alternating between training the discriminator to distinguish between real and fake images and training the generator to generate more realistic images to fool the discriminator. The training progress is visualized through loss and score plots, as well as generated image samples.

# Introduction

Generative Adversarial Networks (GANs) offer a unique approach to generative modeling, characterized by a competitive interplay between two neural networks: the generator and the discriminator. This diagram illustrates the fundamental concept of GANs:

![Generative Adversarial Network](https://i.imgur.com/6NMdO9u.png)

In this setup, the generator aims to produce synthetic data samples that are indistinguishable from genuine data, while the discriminator's objective is to accurately distinguish between real and fake data. Through an adversarial training process, both networks iteratively improve, leading to the generation of high-quality synthetic data.

# Example

Explore the intriguing capabilities of generative models by visiting [thispersondoesnotexist.com](https://thispersondoesnotexist.com). With each page reload, a novel image of a person's face is dynamically generated. The outcomes are captivating, showcasing the remarkable potential of generative models to produce realistic and diverse images.

![Generated Faces](https://imgix.bustle.com/inverse/4b/17/8f/0e/cf91/4506/99c7/e6a491c5d4ac/these-people-are-not-real--they-were-produced-by-our-generator-that-allows-control-over-different-a.png)



# DataSet URL: 

https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types

## About Dataset

Images of all Pokemon from generation 1 to generation 7, along with their types (primary and secondary) as a csv.

### Acknowledgements

Data scrapped from https://pokemondb.net/pokedex/national & most of the learning done from https://jovian.com/


