🧠 Image Compression and Reconstruction using Custom Neural Networks
🎯 Objective
The goal of this project is to gain hands-on experience in building neural networks from scratch to understand their capabilities in image compression and reconstruction. By experimenting with different neural network architectures, students will learn how model design impacts compression performance and reconstruction quality.

📂 Dataset
Dataset Name: LIVE Image Compression Dataset (LIVE 1)

Contents: Paired sets of original and JPEG-compressed images.

Purpose: Used for training and evaluating neural networks in lossy image compression tasks.

✅ Tasks Overview
1. 🔍 Data Exploration & Preprocessing
Load and inspect the dataset (image resolution, quality, compression artifacts).

Normalize and resize images as required.

Prepare train-validation splits.

2. 🛠️ Neural Network Implementation
Build from Scratch: Use only NumPy or PyTorch (without using high-level libraries like Keras).

Baseline Model: Start with a minimal architecture (e.g., fully connected or shallow autoencoder).

Model Enhancements:

Add convolutional layers for spatial feature learning.

Include pooling layers, dense layers, and flattening.

Experiment with:

Layer depth and width

Activation functions (ReLU, Sigmoid, Tanh)

Dropout and Batch Normalization

Bottleneck representations (latent vectors)

3. 🚀 Training Process
Input: Original high-quality images

Target: JPEG-compressed versions of the same images

Use techniques like:

Learning rate scheduling

Dropout for regularization

Batch normalization to improve convergence

Optimizers such as SGD or Adam

4. 📈 Evaluation of Results
Reconstruction Quality Metrics:

PSNR (Peak Signal-to-Noise Ratio)

SSIM (Structural Similarity Index)

Visual Comparison:

Plot side-by-side comparisons of original, compressed, and reconstructed images.

Architectural Analysis:

Evaluate how layer modifications affect image quality, training stability, and overfitting.

5. 🧪 Analysis & Insights
Discuss trade-offs:

Model complexity vs. performance

Training time vs. reconstruction accuracy

Identify key components that contribute most to effective image reconstruction.

