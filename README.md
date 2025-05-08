## Introduction

This repository contains the full training code and model architectures for the Basic U-Net 9 and all the model architecture codes for MACB U-Net variants used in the study:
"Systematic Evaluation of Atrous Spatial Pyramid Pooling in U-Net for Pore Segmentation in Plasma Electrolytic Oxidation Coatings"
Chi-Wei Chu, Chun-Ming Lu, Wing Kiu Yeung (NTUT)

The project systematically evaluates the effect of Atrous Spatial Pyramid Pooling (ASPP) in different positions of the U-Net architecture (Encoder, Bridge, and Decoder) to optimize segmentation performance on SEM images of PEO coatings.

Model training in our research was conducted on Google Colab, leveraging an NVIDIA L4 GPU to accelerate deep learning computations. The experiments were implemented using TensorFlow 2.18.0 and executed in a Python 3.11.11 environment.

## Dataset

This study uses a dataset of 200 annotated SEM images of Plasma Electrolytic Oxidation (PEO) coatings, each with a resolution of 800×800 pixels and a corresponding binary segmentation mask. Below are the split files used for training and evaluation.

- **train 120 refined**: Contains 120 pairs of SEM images and binary masks used for training.  
  [Google Drive link](https://drive.google.com/drive/folders/1Pj50Xzh4O7QDmpdqzrPa7wy1Luj8H3SL?usp=sharing)

- **test 80 refined**: Contains 80 pairs of SEM images and binary masks used for model evaluation.  
  [Google Drive link](https://drive.google.com/drive/folders/1nL9yluKED42pJTm3eplWpEfXBuuOpgXo?usp=sharing)

- **test 40 refined**: Contains 120 pairs of SEM images and binary masks used for model evaluation.  
  [Google Drive link](https://drive.google.com/drive/folders/1otS5Gp2Gjo6ihtNr60dOFZ_dLGCJ714X?usp=sharing)

- **validation 40 refined**: Contains 120 pairs of SEM images and binary masks used for monitoring training F1 score.  
  [Google Drive link](https://drive.google.com/drive/folders/1wVqP1qeWZD5iE8N0iKqZq3bd-ldme8px?usp=sharing)


If you use this dataset, please cite this repository or contact the authors for further information.

