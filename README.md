# Quantum-Siamese-Network
A novel quantum siamese network for image similarity
This notebook constructs a novel quantum siamese network to detect image similarity in MNIST data. 
It takes two separate images and feeds them through two separate variational quantum classifiers. 
It then combines the output of the separate circuits and feeds it through a larger variational quantum classifier.
The MNIST data was reduced to a two dimensional vector using PCA and T-SNE and used to train the model. 
