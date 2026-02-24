# 🌐 Federated Learning: Collaborative & Privacy-Preserving AI

This repository contains a collection of 10 assignments focused on the design, implementation, and optimization of **Federated Learning (FL)** systems. The projects range from basic parameter aggregation to advanced topics like Vertical FL and Differential Privacy.

---

## 🏗️ System Architecture
In these simulations, we follow the decentralized training paradigm where data remains on-device, and only model weights are synchronized.



---

## 📚 Assignment Roadmap

### 1. Fundamentals & Core Workflow
* **Assignment 1: Basic FL Simulation** – Implementing the primary server-client handshake and simple parameter averaging.
* **Assignment 4: Local Training & Transmission** – Detailed implementation of the local gradient descent and weight serialization for transmission.
* **Assignment 8: Full Loop Simulation** – A complete end-to-end cycle of local training, global update, and model redistribution.

### 2. Data Engineering & Partitioning
* **Assignment 2: Data Pre-processing** – Cleaning, normalizing, and partitioning a **Student Performance Dataset** across $N$ virtual nodes.
* **Assignment 3: Linear Regression on House Prices** – Splitting regression features across clients to collaboratively predict market values via **FedAvg**.

### 3. Advanced Aggregation & Vertical FL
* **Assignment 5: Weighted Federated Averaging** – Implementing $W_{FedAvg}$ where updates are weighted based on the client's local sample size.
* **Assignment 6: Vertical Federated Learning (VFL)** – Joint feature-based prediction where different features of the same samples are hosted on different servers.

### 4. Domain-Specific Implementations
* **Assignment 7: Healthcare (Diabetic Patient Data)** – A privacy-preserving diagnostic model for medical institutions to train shared models without leaking sensitive patient records.
* **Assignment 10: Federated Reinforcement Learning** – Multi-agent **Q-Learning** in a grid-world environment where agents share learned Q-values to accelerate convergence.

### 5. Privacy & Security
* **Assignment 9: Differential Privacy (DP)** – Enhancing security by adding **Gaussian/Laplacian noise** to model updates before transmission to prevent membership inference attacks.

---

## 🛠️ Tech Stack
<p align="left">
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,numpy,pandas,mysql" />
</p>

> **Specialized Tools:** Matplotlib (Visualization), Flower (FL Framework), Opacus (Differential Privacy).

---

## 📊 Performance Visualization
The repository includes scripts to visualize:
1.  **Convergence Rates:** Comparing Local vs. Federated training accuracy.
2.  **Privacy Loss:** Tracking the $(\epsilon, \delta)$ budget in Differentially Private training.
3.  **Communication Overhead:** Analyzing the data size of model updates.

---

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/prachishende007/Federated_Learning.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run a specific task: `python assignment_1/main.py`
