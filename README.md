# Equivalence_between_Principal_Component_analysis_Denoising_Autoencoder_and_Contractive-_Autoencoder

We have familiarised ourselves with PCA and autoencoder as tools for dimensionality reduction
used in both data analysis and machine learning. They both have similarities and differences,
and while there are some equivalences between them, they are not entirely equivalent. We know

that PCA is a linear transformation technique that maps high-dimensional data onto a lower-
dimensional space. It seeks to find the principal components of the data, which are the directions

along which the data varies the most. These principal components are orthogonal, which means
they are uncorrelated with each other. PCA finds the linear combinations of the original variables
that maximize the variance of the data in the new coordinate system. On the other hand we are
familiar with encoder a neural network architecture that can be used for dimensionality reduction,
feature extraction, and data compression. It consists of three parts: an encoder, bottleneck and a decoder.
The encoder maps the input data to a lower-dimensional latent space, while the decoder maps the
latent space back to the original space. Autoencoders can be used for unsupervised learning and
can learn more complex, non-linear transformations compared to PCA. There are several special
types of autoencoders that are commonly used in machine learning and deep learning and one of
them is linear autoencoder. In this work we seek to explain the equivalence between PCA and a
linear autoencoder using theoretical, mathematical and analytical approaches. We shown that,the autoencoder with a linear activation function is equal to principal components Analysis.
