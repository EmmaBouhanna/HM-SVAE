# HM-SVAE
A modification of the original SVAE model with Hasting Metropolis sampling

## About
This project is a variant of the S-VAE algorithm originally implemented in Davidson, Falorsi, De Cao et al., *Hyperspherical Variational Auto-Encoders*, which is available here : https://github.com/nicola-decao/s-vae-tf.

## In this repository
- hyperspherical_vae : original library from Davidson & al, which we modified a little bit to replace the sampling method in the latent space by Hasting Metropolis sampling.

- Train_HM.ipynb : allows to train a model with 100 epochs in 2 dimension. Uses the mnist.py file. This notebook shows visualizations of training performances, and testing performances

- illustration_vMF.ipynb : allows to visualize sampling of von Mises-Fisher distribution, both with the original sampling method and the Hasting metropolis sampling.

- gaussian_to_hypersphere.ipynb : Small experiment to show the soap bubble effect.

- reconstructing_MNIST.ipynb : Notebook representing figures for the SVAE latent space with HM sampler. Visualizations of MNIST reconstruction of latent space sampling.

## Authors
Sebastian Partarrieu & Emma Bou Hanna
