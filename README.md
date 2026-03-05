# Image Classification with MobileNetV2

- This project implements a **multi-class image classification model** using **TensorFlow/Keras** with **MobileNetV2 transfer learning**.
- The model was trained on a modified version of the **Caltech101 dataset** and achieves approximately **90.5% validation accuracy**.

## Dataset

- Dataset: **Caltech101**
- Source: https://www.kaggle.com/datasets/imbikramsaha/caltech-101
- **Note:** The **BACKGROUND_Google** class was removed before training.

## Requirements

- Tested with **Python 3.12.3**.
- Install dependencies with:
  `pip install -r requirements.txt`

## Results

- **Validation accuracy:** ~90.5%
- **Custom test set accuracy:** 85% (17/20 images)
