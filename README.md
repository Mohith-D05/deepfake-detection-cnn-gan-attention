# Deepfake Detection using CNN-GAN-Attention

##  Project Overview

This project proposes a hybrid deep learning model for detecting deepfake facial images using:

* Convolutional Neural Networks (CNN)
* Generative Adversarial Networks (GAN)
* Spatial Attention Mechanism

##  Features

* High accuracy deepfake detection (92.6%)
* Attention-based interpretability
* GAN-based data augmentation
* Cross-dataset evaluation

##  Project Structure

```
data/        -> sample data
src/         -> model + training code
results/     -> output images and graphs
report.pdf   -> IEEE paper
```

##  Setup Instructions

### 1. Clone repository

```
git clone https://github.com/your-username/deepfake-detection.git
cd deepfake-detection
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run project

```
python src/train.py
```

##  Results

* Accuracy: 92.6%
* AUC: 98.9%

##  Datasets Used

* FaceForensics++
* Celeb-DF v2

##  Authors

* Mohith D
* Mohammed Rayyan Ul Asgar
* Mohammed Umar Farooq
