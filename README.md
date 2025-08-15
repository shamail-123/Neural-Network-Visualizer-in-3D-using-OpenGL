# 🧠 3D Neural Network Visualizer in OpenGL

## 📌 Overview
This project visualizes the architecture and inference process of a trained neural network **in 3D** using OpenGL.  
It shows **neurons**, **connections**, and **activations** lighting up in real time as input flows through the network.

---

## 🚀 Features
- 3D rendering of neurons (spheres) and connections (lines)
- Animated inference: activations light up layer by layer
- Color-coded activations and weight strengths
- Interactive rotation, zoom, and sample selection
- Uses **MNIST dataset** for demonstration

---

## 📂 Project Structure




📊 Dataset
We use the MNIST dataset, which contains:

60,000 training images

10,000 test images

28×28 grayscale pixels

🛠️ How it Works
Train a neural network on MNIST

Extract weights, biases, and activations

Render them in 3D with OpenGL

Animate the data flow from input to output

🔮 Future Work
Support CNN architectures

Add real-time training visualization

WebGL version for browser
