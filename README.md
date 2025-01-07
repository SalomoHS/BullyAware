# Bullying-Detection

---

## Table of Contents

- [Overview](#overview)  
- [Models](#models)  
- [Dataset](#dataset)  
- [Setup](#setup)  
- [Training](#training)  
- [Evaluation](#evaluation)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

This project aims to leverage 3D convolutional networks to detect bullying actions in videos. The key objectives are:  
- **High accuracy in classification.**  
- **Real-time applicability for monitoring systems.**  
- **Transferability to other action-recognition tasks.**  

The repository demonstrates the use of state-of-the-art models, such as:  
1. **C3D (Convolutional 3D)**  
2. **Expanded 3D (E3D)**  
3. **Inflated 3D (I3D)**  

Each model has been fine-tuned for the specific task of bullying action classification.

---

## Models

### 1. **C3D (Convolutional 3D)**  
C3D captures spatial and temporal features in videos using 3D convolutions, making it well-suited for action recognition.

### 2. **Expanded 3D (E3D)**  
E3D expands on traditional 3D convolutions by optimizing kernel size and adding more depth to layers for improved feature extraction.

### 3. **Inflated 3D (I3D)**  
I3D inflates 2D convolutional filters into 3D, using pre-trained ImageNet models to initialize weights and improve performance on video-based tasks.

---

## Dataset

Dataset source: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/weiji14/deepbedmap/]
We train the models with following class:   
- **Pushing**  
- **Punching**  
- **Strangling**  
- **Hair-grabbing**  
- **Kicking**  
- **Slapping**  

Each video has been pre-processed into numpy arrays (`.npy` files), capturing body motion and spatial-temporal information.

---

## Setup

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Bullying-Detection.git
   cd Bullying-Detection
2. Install dependencies:
   ```bash
   pip install requirements.txt

---
