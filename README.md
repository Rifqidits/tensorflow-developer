# tensorflow-developer

Implementations from the TensorFlow Developer Certificate curriculum — covering convolutional neural networks, image classification, and natural language processing with TensorFlow/Keras.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## Overview

This repository contains notebook implementations organized around the core TensorFlow Developer Certificate topics. Each notebook focuses on building, training, and evaluating models using TensorFlow 2.x and the Keras API.

---

## Repository Structure

```
tensorflow-developer/
├── cnn-tensorflow/
│   ├── cnn-for-cats-dogs/
│   │   └── cnn_for_cats_dogs.ipynb           # Binary image classification with CNN
│   ├── multiclass-classification/
│   │   └── multiclass_classification.ipynb   # Softmax output, categorical cross-entropy
│   ├── tackle-overfitting-data-augmentation/
│   │   └── tackle_overfitting_data_augmentation.ipynb  # Dropout, augmentation
│   └── transfer-learning/
│       └── transfer_learning.ipynb           # Fine-tuning pretrained models
└── natural-language-processing/
    └── predicting_the_next_word.ipynb        # Tokenization, embedding, LSTM language model
```

---

## Topics Covered

| Module | Techniques |
|--------|-----------|
| **CNN — Binary Classification** | Conv2D, MaxPooling, sigmoid output, binary cross-entropy |
| **CNN — Multiclass** | Softmax, categorical cross-entropy, one-hot encoding |
| **Overfitting & Augmentation** | Dropout, ImageDataGenerator, L2 regularization |
| **Transfer Learning** | Feature extraction, fine-tuning, frozen layers |
| **NLP** | Tokenizer, padding, word embeddings, LSTM, next-word prediction |

---

## Getting Started

### Prerequisites

- Python 3.10+
- TensorFlow 2.x

### Installation

```bash
git clone https://github.com/Rifqidits/tensorflow-developer.git
cd tensorflow-developer
pip install -r requirements.txt
jupyter notebook
```

---

## License

MIT License — see [LICENSE](LICENSE) for details.
