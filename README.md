#🎙️ Speech Emotion Detector

![GitHub repo size](https://img.shields.io/github/repo-size/Ajith-ajay/speech-emotion-detector)
![GitHub stars](https://img.shields.io/github/stars/Ajith-ajay/speech-emotion-detector?style=social)
![GitHub forks](https://img.shields.io/github/forks/Ajith-ajay/speech-emotion-detector?style=social)
![License](https://img.shields.io/github/license/Ajith-ajay/speech-emotion-detector)

> A machine learning project to classify human emotions from speech using Scikit-learn, TensorFlow, and PyTorch.

---
## Table of Contents
- [Overview](#overview)
- [Required Modules](#required-modules)
- [Installation Instructions](#installation-instruction)
  - [Installing Environment](#installing_environment)
  - [Installing Libraries](#installing_libraries)
- [Usage](#usage)
  

## Overview

Speech Emotion Detection is a machine learning project that focuses on identifying human emotions from audio speech signals. The goal is to enable machines to understand and classify emotions such as happy, sad, angry, neutral, and more by analyzing the acoustic features of spoken language.

This project explores and compares three different machine learning frameworks — Scikit-learn, TensorFlow, and PyTorch — to train and evaluate models for emotion classification. It provides a hands-on, modular pipeline from feature extraction to training, evaluation, and prediction.

## ✅ Required Modules

Make sure the following packages are installed:

- Python (>=3.7)
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib (for visualization)
- seaborn (for advance visualization)

---

## 🛠️ Installation Instructions

### 1. Install Python and an IDE (if not already installed)

- [Download Python](https://www.python.org/downloads/)
- [Download Visual Studio Code](https://code.visualstudio.com/) or any other IDE that supports Jupyter

---

### 2. Clone the Repository

```bash
git clone https://github.com/Ajith-ajay/speech-emotion-detector
cd speech-emotion-detector
```

**Create and Activate a Virtual Environment**

```bash
python -m venv env  # where env is environment name
```
**Activate the Environment**
For windows
```bash
\env\scripts\activate
```
For macos
```bash
python3 -m venv env
source env/bin/activate
```
**installing libraries**

```bash
pip install -r requirements.txt
```

**🚀 Running the Project**
1.Launch Jupyter Notebook
```bash
Launch Jupyter Notebook
```

2. Open and Run the Notebook
    In the browser window that opens, navigate to the project folder:

    Open the file and run each cell to execute the code step by step. shift + enter is the shortcut for the executing the each cell

**📂 Folder Structure**
```bash
SPEECH EMOTION DETECTOR/
│
├── data/                     # Folder for training and validation data
├── test/                     # Folder for test audio samples
│
├── .gitignore                # Git ignore rules
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
│
├── train.ipynb               # Training notebook using Scikit-learn
├── train_keras.ipynb         # Training notebook using TensorFlow/Keras
├── train_torch.ipynb         # Training notebook using PyTorch

```

**📄 License**
This project is open-source and available under the MIT License.

## Usage

This is a basic student-level project designed to understand the concept of Machine Learning. Gold Rate Prediction serves as a practical example of applying machine learning to a real-world financial problem. It demonstrates how historical data can be used to train models that predict future values, helping to explore the fundamentals of data analysis, feature selection, and regression algorithms in a meaningful context.