# Project Details:

This repository demonstrates the implementation of Generative Adversarial Networks (GANs) for generating Pokémon images using the Pokémon images and types dataset. The GAN consists of a generator and a discriminator neural network, trained simultaneously in a competitive setting.

The dataset is prepared by downloading and preprocessing Pokémon images, including resizing, center cropping, converting to tensors, and normalization. The generator and discriminator models are then defined using convolutional and transpose convolutional layers, respectively.

The training process involves alternating between training the discriminator to distinguish between real and fake images and training the generator to generate more realistic images to fool the discriminator. The training progress is visualized through loss and score plots, as well as generated image samples.


# DataSet URL: 

https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types

## About Dataset

Images of all Pokemon from generation 1 to generation 7, along with their types (primary and secondary) as a csv.

### Inspiration
New evolution forms from two different Pokemon. (Create new Pokemon). Predict Pokemon primary and secondary types from the images. Identify what types the evolution form will have based on the pre-evolved forms. Eg. from Pichu and Pikachu predict for Raichu.

### Future work/Ideas:

Merge with other information such as moves, generation, strong/weak against etc, and use the images to classify.

### Acknowledgements

Data scrapped from https://pokemondb.net/pokedex/national


