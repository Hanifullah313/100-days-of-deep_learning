
# 🧠 100 Days of Deep Learning

![Deep Learning](https://img.shields.io/badge/Skill-Deep%20Learning-FF6F00?style=for-the-badge&logo=google-colab&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

> *"I have always been convinced that the only way to get artificial intelligence to work is to do the computation in a way similar to the human brain."* — Geoffrey Hinton

---

## 🌌 The Mission

Welcome to the code archives of my **100 Days of Deep Learning** challenge. This repository documents my intensive journey from the fundamental mathematics of a single neuron to building state-of-the-art Generative AI models from scratch.

This is not just a collection of scripts; it is a systematic exploration of the **architectures that power modern AI**. Each folder represents a leap in complexity, moving from simple classification to complex sequence modeling and computer vision.

---

## 🗺️ The Architecture Roadmap

I have organized my learning path into distinct conceptual modules:

### 🔹 Module 1: The Neural Foundation
*Building the brain, one neuron at a time.*
- **Perceptron:** Implementing the mathematical grandfather of modern AI. Understanding weights, biases, and activation functions.
- **ANN (Artificial Neural Networks):** Building fully connected dense networks (MLP).
- **Functional API:** Mastering non-linear topologies, shared layers, and multiple inputs/outputs in Keras.
- **Handwritten Digit Classification:** The "Hello World" of Deep Learning using the MNIST dataset.

### 🔹 Module 2: Computer Vision (CV)
*Teaching machines to "see" and interpret visual data.*
- **CNN (Convolutional Neural Networks):** Filters, Kernels, Pooling layers, and spatial hierarchies.
- **Data Augmentation:** Techniques to artificially expand datasets (Rotation, Zoom, Flips) to prevent overfitting.
- **Transfer Learning:** Leveraging the power of VGG16, ResNet, and MobileNet for tasks like **Cat vs. Dog Classification**.
- **PreTrained Models:** Utilizing weights trained on ImageNet to solve custom problems with minimal data.

### 🔹 Module 3: Sequence Modeling (NLP)
*Giving the model memory and context.*
- **SimpleRNN:** Understanding vanishing gradients and temporal dependencies.
- **LSTM (Long Short-Term Memory):** Solving the short-term memory problem with Forget, Input, and Output gates.
- **Text Generation:** Predicting the next character or word in a sequence.

### 🔹 Module 4: The Transformer Era (Generative AI)
*The architecture that changed everything.*
- **Transformers:** Understanding Self-Attention, Multi-Head Attention, and Positional Embeddings.
- **GPT From Scratch:** A complete implementation of a **Decoder-only Transformer** (NanoGPT). Trained on Shakespeare to generate text character-by-character.
    - *Features:* Masked Self-Attention, LayerNorm, Residual Connections.

### 🔹 Module 5: Optimization & Tuning
- **Keras Tuner:** Automating hyperparameter search (Random Search, Hyperband) to find the optimal model architecture.

---

## 📂 Repository Structure

```plaintext
100-days-of-deep_learning/
│
├── 📂 Perceptron/                 # The mathematical basics
├── 📂 Handwritten Digit Class.../ # ANN Project (MNIST)
├── 📂 Functional_API/             # Advanced Keras structures
├── 📂 Keras Tuner/                # Hyperparameter Optimization
│
├── 📂 CNN/                        # Convolutions & Pooling
├── 📂 Data Augmentation/          # Image Preprocessing techniques
├── 📂 Transfer Learning/          # Fine-tuning custom models
├── 📂 PreTrained Models/          # ResNet, VGG implementations
│
├── 📂 SimpleRNN/                  # Basic Recurrent Networks
├── 📂 LSTM/                       # Long Short-Term Memory Networks
│
├── 📂 Transformers/               # ★ CAPSTONE: GPT from Scratch
└── 📜 README.md                   # Documentation

```

---

## 🛠️ Tech Stack

| Domain | Library / Tool |
| --- | --- |
| **Frameworks** | TensorFlow 2.x, Keras, PyTorch |
| **Data Processing** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Development** | Google Colab, Jupyter Notebooks |
| **Accelerators** | NVIDIA CUDA (GPU) |

---

## 🌟 Featured Projects

### 1. GPT From Scratch (NanoGPT)

Built a replica of the GPT-2 architecture using PyTorch. This model generates infinite Shakespearean text by learning the statistical probabilities of character sequences.

* **Key Tech:** `torch.nn`, `MultiHeadAttention`, `LayerNorm`
* **Location:** `Transformers/GPT from Scratch`

### 2. Cat vs. Dog Classifier (Transfer Learning)

Utilized a pre-trained CNN (MobileNetV2) to classify images of pets with >95% accuracy, demonstrating the power of feature extraction.

* **Key Tech:** `Keras Applications`, `GlobalAveragePooling2D`
* **Location:** `Transfer Learning`

---

## 📈 Visualizations & Results

*Below represents the training loss curve from the recent GPT model training:*

```text
Step 0:    Loss 4.21
Step 1000: Loss 2.45
Step 3000: Loss 1.90
Step 5000: Loss 1.72 (Converged)

```

*(Note: Detailed plots for accuracy and loss are included within the individual notebooks.)*

---

## 🤝 Connect

I am actively building projects in Generative AI and MLOps.

**Hanif Ullah**

---

<p align="center">
<i>"The best way to predict the future is to invent it." — Alan Kay</i>
</p>

```

```
