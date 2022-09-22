# Autoencoder
Autoencoder is an unsupervised artificial neural network that learns how to efficiently compress and encode data then learns how to reconstruct the data back from the reduced encoded representation

Denoising Autoencoder corrupt the data on purpose then try to find features and reconstruct image

# Data
### dataset : [DATA](https://www.kaggle.com/code/javidtheimmortal/sar-image-despeckling-using-a-convolutional-neural/data)
here i have selected s2 of urban images and produce noise in them

# Layers
<img src="/autoencoder.png" alt="layers" width="480"/>

here there are 2 layers to reduce it to 64 x 64 latent vector/bottleneck layer
2 layes to upsample and bring back the decoded/noise removed image

# Libraries 
![tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) 
![pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![numpy](    https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)
SEABORN, MATPLOT and others.
