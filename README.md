# DeepLearning-AutoEncoder
This project applies a deep learning autoencoder to learn compressed representations of the Nuts dataset for dimensionality reduction and anomaly detection. Autoencoders are useful for uncovering hidden patterns in data, identifying unusual cases, and improving downstream machine learning tasks.

Features :

1. Data Preprocessing

a.  EDA

b. Prepared input-output pairs for training an unsupervised autoencoder model


2. Model Architecture

a. Implemented an encoder-decoder neural network to compress and reconstruct input features

b. Tuned number of layers, neurons, and activation functions to minimize reconstruction loss


3. Training & Evaluation

a. Trained the model to reconstruct normal samples

b. Evaluated performace using SSIM score (Structural Similarity)
