# Brain Tumor Classification Using CNN

A deep learning academic project focused on classifying brain MRI images into four categories using a Convolutional Neural Network (CNN) built with Python, TensorFlow, and Keras.

## Overview

This project explores the use of CNNs for multi-class image classification of brain MRI scans. The model is designed to distinguish between the following categories:

* **Glioma**
* **Meningioma**
* **Pituitary Tumor**
* **No Tumor**

The project was developed using Google Colab as part of an academic exploration of deep learning and medical image classification.

> **Disclaimer:** This project is for educational and research purposes only. It is not intended for clinical use or medical diagnosis.

## Technologies Used

* **Python** — Programming language
* **TensorFlow** — Deep learning framework
* **Keras** — Neural network API
* **Google Colab** — Development and training environment
* **NumPy** — Numerical computation
* **Matplotlib** — Data visualization

## Dataset

The notebook uses a brain MRI image dataset divided into training, validation, and testing sets.

| Dataset    | Number of Images |
| ---------- | ---------------: |
| Training   |            5,712 |
| Validation |              655 |
| Testing    |              656 |
| **Total**  |        **7,023** |

The images are processed at a resolution of 224 × 224 pixels with RGB color channels.

**Note:** Dataset access and redistribution depend on the original dataset's license and terms. The dataset is not included in this repository.

## Model Architecture

The project implements a CNN with convolutional, pooling, and fully connected layers for image classification.

The architecture includes:

1. **Convolutional layers:** Extract visual features from MRI images using progressively larger filter sets.
2. **Max pooling layers:** Reduce spatial dimensions and computational complexity.
3. **Flatten layer:** Convert extracted feature maps into a one-dimensional feature vector.
4. **Dense layers:** Learn higher-level representations for classification.
5. **Softmax output layer:** Produce class probabilities for the four target categories.

The model was configured for training over 10 epochs.

## Project Workflow

1. Load the MRI image dataset from Google Drive in Google Colab.
2. Prepare image data for model training.
3. Build the CNN architecture using TensorFlow and Keras.
4. Train the model using the training dataset and validation data.
5. Evaluate the model using the separate testing dataset.

## Repository Structure

```text
brain-tumor-classification-cnn/
├── Brain_Tumor_CNN.ipynb
└── README.md
```

## Getting Started

### Requirements

* Python 3.x
* TensorFlow
* NumPy
* Matplotlib
* Google Colab or Jupyter Notebook

### Run in Google Colab

1. Open the notebook in Google Colab.
2. Make sure you have access to the required MRI dataset.
3. Update the dataset paths in the notebook to match your Google Drive directory.
4. Run the notebook cells in order to prepare the data, build the model, and start training.

### Run Locally

Install the required packages:

```bash
pip install tensorflow numpy matplotlib
```

Open the notebook using Jupyter:

```bash
jupyter notebook Brain_Tumor_CNN.ipynb
```

Ensure the dataset paths are configured correctly before running the notebook.

## Results

The notebook contains the CNN architecture and training workflow. Final training and testing metrics have not yet been verified from the saved notebook outputs.

Evaluation metrics such as accuracy, precision, recall, F1-score, and a confusion matrix should be recorded after successfully completing model training and evaluation.

## Learning Objectives

* Understand the fundamentals of convolutional neural networks.
* Explore image preprocessing and classification workflows.
* Gain practical experience with TensorFlow and Keras.
* Implement a multi-class image classification model.
* Practice using Google Colab for deep learning experiments.

## Future Improvements

* Complete and document model training and evaluation.
* Add a confusion matrix and detailed classification report.
* Experiment with data augmentation and regularization.
* Compare the CNN against traditional machine learning approaches.
* Explore model deployment through a REST API.

## Author

**Eko Alfianto**

GitHub: [ekoalfn](https://github.com/ekoalfn)

Portfolio: [ekoalfi.my.id](https://ekoalfi.my.id)

---

*Academic project developed for learning and experimentation with deep learning and medical image classification.*
