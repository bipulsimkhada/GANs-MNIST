# GANs-MNIST

## GANS
GANs (Generative Adversarial Networks) are a type of deep learning algorithm that is used to
generate new data by learning from existing data. GANs were first introduced by Ian Goodfellow
and his colleagues in 2014, and have since become one of the most popular and promising areas
of research in artificial intelligence.

The basic idea behind GANs is to have two neural networks competing with each other - a
generator network and a discriminator network. The generator network creates new data that is
similar to the training data, while the discriminator network tries to distinguish between the
generated data and the real data. The two networks are trained together in an adversarial manner,
with the generator trying to fool the discriminator and the discriminator trying to correctly identify
the real data.

Over time, as the two networks continue to learn from each other, the generator becomes better at
creating realistic data that can fool the discriminator. This process continues until the generator
produces data that is almost indistinguishable from the real data. This is the ultimate goal of GANs to generate data that is so realistic that it is difficult to tell whether it is real or fake.


## Libraries 
* Keras
* matplotlib
* imageio
* git
* PIL
* glob
* os
* IPython - Display
* numpy
* pandas

## Tool
* Google Colab
* Google Drive

## Dataset
Data Set: Keras - MNIST

## Image Generation using GANs
In this project, we generate MNIST images using GANS archetitecture. We have generator and discriminator models in our archetitecture where generator will generate image and discriminator will classify the generated images as real or fake. Here are the steps involved:
* Install and import required libraries.
* Load Dataset and reshape image size to 28X28
* Define Generator Model
* Define Discriminator Model
* Define loss and optimizer for generator and discriminator models
* Train model
* Generate and save image
* Create GIF of generated image in each epoch stage. 

## Generated image GIF
<img src="https://github.com/bipulsimkhada/GANs-MNIST/blob/main/Image/Generated%20image.gif">

## Generated image after 50 epochs
<img src="https://github.com/bipulsimkhada/GANs-MNIST/blob/main/Image/Generated%20image.png">


