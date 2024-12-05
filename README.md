# ** MNIST : Convolutional Autoencoder with GMM Latent Space**

This project implements a convolutional autoencoder (AE) trained on the MNIST dataset. The AE reduces the dimensionality of the input images and compresses them into a latent space. A Gaussian Mixture Model (GMM) is applied to the latent space to generate new samples, allowing exploration of the data distribution.

---

## **Features**
- **Convolutional Autoencoder (AE)** with:
  - 3 convolutional layers in the encoder.
  - 3 transposed convolutional layers in the decoder.
- **Gaussian Mixture Model (GMM)** applied to the latent space for:
  - Sampling new images from the learned data distribution.
  - Visualizing generated samples.

---

## **Installation**

### **Requirements**
- Python 3.8+
- PyTorch
- torchvision
- scikit-learn
- matplotlib
- numpy