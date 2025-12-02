# price_prediction_MNIST_classifier

This repository implements two deep learning tasks using **PyTorch**. It progresses from basic image classification to building a complex hybrid regression model.

### 2. FashionMNIST Classifier (Intro)
**Goal:** Classify clothing items using a standard CNN (`StylishNN`).
* **Purpose:** Served as an exercise to establish the architecture to be utilized in the main project.
* 
### 1. Hybrid House Price Prediction (Main)
**Goal:** Predict Houston home prices by fusing listing images with tabular features.
* **Data Engineering:** Engineered a robust pipeline to handle "messy" data, including pruning missing relational keys, imputing incomplete features, and normalizing inputs.
* **Model:** Built a **Hybrid Neural Network** that concatenates a CNN (for images) and an MLP (for tabular data). The model outperformed uni-modal baselines.

## Utilized Tools
* **Core:** PyTorch, Torchvision
* **Data:** Pandas, NumPy, PIL
* **Visualization:** Matplotlib
