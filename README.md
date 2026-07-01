# 🚦 Task-Adaptive Semantic Communication for Multi-Task Traffic Sign Classification

> An end-to-end semantic communication framework that learns compact, task-aware representations for reliable traffic sign understanding under noisy wireless communication environments.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Research](https://img.shields.io/badge/Research-BTP-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

Traditional communication systems transmit every bit of information regardless of its importance.

This project explores **Semantic Communication**, where only task-relevant information is transmitted, reducing communication cost while maintaining high inference accuracy.

The proposed framework combines:

- Shared CNN Semantic Encoder
- Task-Adaptive Attention Module
- Top-K Semantic Feature Selection
- AWGN Channel Simulation
- Multi-Task Learning
- Task-Specific Decoders

The framework was developed as part of our **B.Tech Thesis (BTP)** and evaluates robustness under varying communication constraints.

---

# 🏗️ System Architecture

The proposed framework follows an **end-to-end semantic communication architecture** designed for efficient multi-task inference under communication constraints.

The system is composed of three major components:

### 📡 Transmitter
- Shared CNN Semantic Encoder
- Task Embedding Layer
- Cross-Attention Module
- Top-K Semantic Feature Selector

### 📶 Communication Channel
- Additive White Gaussian Noise (AWGN) Channel
- Simulates noisy wireless communication environments

### 🖥️ Receiver
- Task Switch Router
- Shape Decoder
- Color Decoder
- Speed Limit Decoder

<p align="center">
    <img src="images/architecture.png" width="1000">
</p>

The architecture jointly learns semantic representation, task-aware reasoning, and task-specific inference in an end-to-end manner, enabling reliable prediction even under noisy communication channels.
