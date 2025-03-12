This repository contains the full training code and model architectures for the Basic U-Net 9 and all the model architecture codes for MACB U-Net variants used in the study:
"Systematic Evaluation of Atrous Spatial Pyramid Pooling in U-Net for Pore Segmentation in Plasma Electrolytic Oxidation Coatings"
Chi-Wei Chu, Chun-Ming Lu, Wing Kiu Yeung (NTUT)

The project systematically evaluates the effect of Atrous Spatial Pyramid Pooling (ASPP) in different positions of the U-Net architecture (Encoder, Bridge, and Decoder) to optimize segmentation performance on SEM images of PEO coatings.

Model training in our research was conducted on Google Colab, leveraging an NVIDIA L4 GPU to accelerate deep learning computations. The experiments were implemented using TensorFlow 2.18.0 and executed in a Python 3.11.11 environment.
