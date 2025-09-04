# Variational-Autoencoder-VAE-for-Image-Generation-and-Representation-Learning
Built a Variational Autoencoder (VAE) to learn latent representations of image data and generate new samples. Trained on MNIST using TensorFlow/Keras. Visualized reconstructions, latent space, and random generations. Useful for image generation and anomaly detection.
This project implements a **Variational Autoencoder (VAE)** using Python and TensorFlow/Keras. VAEs are a type of generative model that learn to encode input data into a latent space and reconstruct it, while also enabling the generation of new, similar data.

---

## 🎯 Objective

To build a Variational Autoencoder that:
- Learns compressed latent representations of images
- Reconstructs input images with high accuracy
- Generates new images by sampling from the latent space

---

## 📊 Key Features

- Custom VAE architecture built using TensorFlow/Keras
- Encoder and decoder implemented as neural networks
- KL Divergence + Reconstruction loss optimization
- Visualization of:
  - Training loss curves
  - Reconstructed vs original images
  - Generated images from random latent vectors
  - Latent space distribution (2D projection for small datasets)

---

## 📁 Dataset

You can use standard datasets like:
- **MNIST** (handwritten digits)
- **Fashion-MNIST** (clothing items)
- **CIFAR-10** (optional, for more complex examples)

Data is automatically loaded using `tensorflow.keras.datasets`.

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib / Seaborn  

---

## 📦 Project Structure

