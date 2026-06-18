MGLeaf-Disease Dataset and Deep Learning Framework

**Overview:**

This repository contains the implementation code for the research work:
"MGLeaf-Disease: A Real-Time Mango and Groundnut Leaf Image Dataset for Multiclass Disease Identification"
The repository includes preprocessing scripts, augmentation pipeline, model training code, evaluation scripts, and performance analysis for multiclass plant disease classification.

**Dataset:**
The dataset is publicly available at Mendeley Data:
Dataset Link: https://data.mendeley.com/datasets/7m8n4ym4nm/1

The dataset contains:
91,438 annotated images
9 disease and healthy classes
Mango and Groundnut crops
Image size: 256 × 256 pixels

**Implemented Models:**
Custom CNN
MobileNetV2
VGG16
EfficientNetB0
Features
Image preprocessing using LANCZOS rescaling
Data augmentation using TensorFlow ImageDataGenerator
Dataset partitioning (80:20)
Model training and evaluation
Confusion matrix generation
Accuracy and loss visualization

**Requirements:**
Python 3.10+
TensorFlow 2.x
NumPy
Matplotlib
Scikit-learn
PIL
OpenCV
Usage

**Install Dependencies:**
pip install -r requirements.txt
Train Model
python train.py
Evaluate Model
python evaluate.py


**License:**

This project is released under the MIT License.
Dataset is distributed under CC BY 4.0.
