# Demystifying AI Basic for Doctors

This Excel file, **AI4Med\_present\_new2.xlsx**, is a comprehensive, step-by-step educational resource designed to illustrate the **core mechanics of a Neural Network (NN) by hand**. It provides detailed, numerical calculations for a complete deep learning workflow, from dataset preparation to multi-layer backpropagation.

This file is structured across multiple sheets, each focusing on a distinct phase of the neural network lifecycle:

***
<img width="961" height="588" alt="image" src="https://github.com/user-attachments/assets/ab7835be-8032-4a3f-8868-4c655a8c0cb9" />

***

### 1. Dataset-Tumor

* **Content:** Contains the input data (normalized pixel values, $\mathbf{X}$) for a **Brain Tumor MRI Dataset** (sourced from a Kaggle link), along with their corresponding classification labels.
* **Purpose:** Serves as the raw input data for training and demonstrating the models within the file.

### 2. Perceptron

* **Content:** Demonstrates the foundational **Single-Layer Perceptron** model.
* **Purpose:** Illustrates the fundamental concepts of a neural network: input, linear transformation (weighted sum), activation, and the calculation of a basic loss function.

### 3. Multilayer (MLP)

* **Content:** Details the **Forward Propagation** process for a **Multi-Layer Perceptron (MLP)**.
* **Purpose:** Shows the numerical flow of information through an input layer and at least one hidden layer, including the application of weights ($\mathbf{W}$) and biases ($\mathbf{b}$) to calculate activations ($\mathbf{a}^{(1)}, \mathbf{a}^{(2)}$).

### 4. Backprop\_single\_image

* **Content:** Provides a complete, detailed walkthrough of the **Backpropagation** algorithm for a **single training image**.
* **Key Feature:** Includes the calculation of the hidden layer error signal ($\delta^{(1)}$) using the derivative of the **$\text{ReLU}$ (Rectified Linear Unit)** activation function, demonstrating how gradients are gated by active/inactive neurons. This is the heart of the NN learning process.

### 5. Backprop\_more\_image

* **Content:** Extends the backpropagation demonstration to cover **multiple images** (a mini-batch or full epoch).
* **Purpose:** Shows how gradients are accumulated across several samples to calculate the final weight and bias updates ($\Delta \mathbf{W}, \Delta \mathbf{b}$).

<img width="472" height="589" alt="image" src="https://github.com/user-attachments/assets/de9c2c4c-cb64-4db1-ab2e-fb5d3783d0ba" />


### 6. Intro

* **Content:** Contains introductory information, high-level summaries of the topics covered ("Loss graph," "Multilayer"), and possible attribution/project context for the work.

***

**Overall Project Goal:** To visually and numerically demystify deep learning concepts by translating complex matrix operations into manageable, cell-by-cell spreadsheet calculations, making it a resource for learning AI "by hand."
