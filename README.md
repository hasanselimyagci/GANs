# Deep Convolutional Generative Adversarial Networks

- Two models are trained simultaneously by an adversarial process. A *generator* 
 learns to create images that look real, while a *discriminator* learns to tell real images apart from fakes.

- During training, the *generator* progressively becomes better at creating images that look real, while the *discriminator* becomes better at telling them apart. The process reaches equilibrium when the *discriminator* can no longer distinguish real images from fakes.

- The notebook in this repo demonstrates this process on the MNIST dataset.
