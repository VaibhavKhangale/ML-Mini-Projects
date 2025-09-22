# 🤖 Machine Learning Mini Projects

Welcome to my collection of machine learning mini-projects!  
Each folder in this repo contains a self-contained ML project with its own code, results, and explanation.

---

## 📂 Projects

### 1. 🧠 Brain Tumor Detection and Classification
A ML pipeline for developing Tumor Classifier in Tensorflow using Transfer learning.

### 2. 🚗 AI based Smart Grid-Headlights
An AI based headlight system which makes use of computer vision to avoid blinding drivers.

---

## 📌 Motive

This repository serves as a collection of small but practical ML projects to:
- Sharpen model-building and tuning skills
- Test different architectures and baselines
- Document and share insights along the way

---

## 🛠️ Setup

```bash

#Create a conda environment as,
conda create -n py310 python=3.10
conda activate py310

# Install tensorflow to run using GPU,
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
python -m pip install "tensorflow<2.11"

#install any other required libraries,
pip install numpy pandas matplotlib
#etc.

#install jupyter lab
conda install -c conda-forge jupyterlab
jupyter lab


