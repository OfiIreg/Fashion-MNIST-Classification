# Fashion-MNIST Classification

## Overview
This project implements a 6-layer Convolutional Neural Network (CNN) using **Keras** in both Python and R to classify the **Fashion-MNIST** dataset.

## Files
- `keras_cnn_fashion_mnist.py` — Python script (TensorFlow Keras)
- `keras_cnn_fashion_mnist.R` — R script (keras R package)

## Requirements

### Python
```bash
pip install tensorflow numpy
```
### R
```r
install.packages('keras')
library(keras)
keras::install_keras()
```

## How to Run

### Python
```bash
python keras_cnn_fashion_mnist.py --epochs 5 --batch_size 128
```

### R
```r
source('keras_cnn_fashion_mnist.R')
```

## Outputs
- Trained model (`.h5` format)
- Predictions for two sample test images (indices 0 and 1)

## Notes
To adapt this project for **user profile classification**, replace the dataset with your image dataset and consider using **transfer learning** (e.g., MobileNet, EfficientNet) for color profile images.


## Academic Information

**Assignment:** Fashion MNIST Classification
**Course:** Programming in R & Python  
**Institution:** Nexford University 
**Student:** Ofure Iregbeyen  
**Date:** 13-11-2025 

---

**End of README**
