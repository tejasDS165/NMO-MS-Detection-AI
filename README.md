# AI-Based Detection of Neuromyelitis Optica (NMO) vs Multiple Sclerosis (MS)

This project develops a **deep learning-based diagnostic model** to classify MRI images into **Neuromyelitis Optica (NMO)** and **Multiple Sclerosis (MS)**.
Both diseases affect the **central nervous system** and often show similar symptoms, making accurate diagnosis difficult.

The model uses **Convolutional Neural Networks (CNN) with Transfer Learning** to analyze MRI images and assist in distinguishing between these two neurological disorders.

---

# Project Overview

The goal of this project is to build an **AI-powered medical diagnostic system** that can support healthcare professionals in differentiating between **NMO and MS** using MRI imaging data.

The system performs the following steps:

1. Data preprocessing and normalization
2. Image augmentation to improve model generalization
3. Feature extraction using **InceptionV3 (Transfer Learning)**
4. Training CNN models with different activation functions
5. Model evaluation using performance metrics

---

# Technologies & Tools

* **Python**
* **TensorFlow / Keras**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

Deep Learning Architecture:

* **CNN (Convolutional Neural Network)**
* **InceptionV3 Transfer Learning**

---

# Methodology

The workflow of the system includes:

1. **Data Collection**

   * MRI medical imaging dataset

2. **Data Preprocessing**

   * Image resizing
   * Normalization
   * Dataset organization

3. **Data Augmentation**

   * Rotation
   * Horizontal flipping
   * Zoom
   * Brightness adjustments

4. **Model Development**

   * Pretrained **InceptionV3** used for feature extraction
   * Custom classification layers added on top

5. **Activation Function Comparison**

   * ReLU
   * Leaky ReLU
   * ELU

6. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1-score

---

# Results

The model was evaluated using different activation functions.

| Activation Function | Test Accuracy |
| ------------------- | ------------- |
| ReLU                | ~83%          |
| Leaky ReLU          | ~82%          |
| ELU                 | ~80%          |

ReLU provided the **best overall performance** for the classification task.

---

# Sample Visualizations

The project includes several training and evaluation visualizations:

* Training vs Validation Accuracy Graph
* Activation Function Comparison
* Test Accuracy Bar Chart

These visualizations help analyze model performance and convergence behavior.

---

# Project Structure

```
nmo-ms-detection-ai
│
├── Nmo_MS.ipynb              # Jupyter notebook with model implementation
├── Final_report.pdf          # Detailed project report
├── images
│   ├── accuracy_graph.png
│   └── training_validation.png
├── requirements.txt
└── README.md
```

---

# Future Improvements

Potential enhancements for this project include:

* Using **larger medical datasets**
* Improving **model accuracy through hyperparameter tuning**
* Implementing **explainable AI (XAI)** techniques
* Deploying the model as a **web application for clinical use**
---

If you found this project interesting, feel free to star the repository!
