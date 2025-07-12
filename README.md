# Shallow Optimizers and Deep Autoencoder

This project was developed as part of the **CSE473 - Computational Intelligence** course. It consists of two main milestones:

1. **A comparison of optimization strategies for training shallow neural networks on CIFAR-10.**
2. **Design and evaluation of autoencoder-based architectures for face recognition.**

---

## Milestone 1: Shallow Optimizers (CIFAR-10)

In this milestone, we built a shallow neural network and trained it on the **CIFAR-10 dataset** to compare the effectiveness of various optimization algorithms and learning rate strategies.

### Algorithms Compared:
- **Stochastic Gradient Descent with Warm Restarts (SGDR)**
- **Nesterov Accelerated Gradient (NAG)**
- **RMSProp**
- **Nadam**
- **Learning Rate Schedulers**: 
  - Exponential Decay
  - Step Decay

### Evaluation Criteria:
- Training time
- Accuracy
- Convergence behavior (loss vs. epochs)

---

## Milestone 2: Deep Autoencoder for Face Recognition

In this milestone, we designed and trained several encoder-decoder models to learn meaningful representations for face recognition using deep learning.

### Architectures Implemented:
- **Vanilla Autoencoder**
- **Variational Autoencoder (VAE)**
- **Convolutional Autoencoder (CAE)**

### Methodology:
- Dataset: [CASIA-WebFace / FRGC] *(replace with the one you used)*
- Data split: 70% train, 15% validation, 15% test
- Normalization: mean subtraction & standard deviation division per feature
- Cross-validation to find the optimal number of hidden layers and nodes
- Feature extraction using the latent code from each model
- Classification using **Minimum Euclidean Distance Classifier**

### Visualizations:
- Training loss curves
- Face reconstructions
- Latent space representations
- Accuracy comparisons across models

---
## Team Members

This project was completed as part of the **CSE473 – Computational Intelligence** course  
Faculty of Engineering, Ain Shams Univesity

- **Lydia Safwat Ghali**
- **Shahd AbouHashem**
- **Ziad Walid ElHanafy**  
---

## Appendix
All code is contained within the two notebooks above.  
Feel free to explore, modify, and build upon these models.

[Drive Link](https://drive.google.com/drive/folders/1ejn5D8Q7qM7eS6vTjzUQBDuUoomVu1hq)


