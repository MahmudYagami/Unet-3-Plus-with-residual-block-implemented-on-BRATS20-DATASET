# UNet-3+ with Residual Blocks on BRATS 2020 Dataset

This repository contains an implementation of UNet-3+ with residual blocks for brain tumor segmentation using the BRATS 2020 dataset. The model is designed to improve segmentation accuracy by leveraging deep residual connections and advanced UNet architecture.

Dataset
The model is trained and evaluated on the BRATS 2020 dataset, which contains MRI scans labeled for brain tumor segmentation. The dataset includes the following segmentation classes:

0: Background (No tumor)

1: Necrotic/Core (Non-enhancing tumor core)

2: Edema

3: Enhancing Tumor

Features
UNet-3+ architecture with residual blocks

Multi-scale feature fusion for better segmentation

Data preprocessing and augmentation for improved generalization

TensorFlow/Keras-based implementation

Installation
Clone the repository:
git clone https://github.com/MahmudYagami/Unet-3-Plus-with-residual-block-implemented-on-BRATS20-DATASET.git
Install dependencies:
pip install -r requirements.txt
Ensure the BRATS 2020 dataset is available in the correct path.
Run the Jupyter Notebook to train and evaluate the model:
jupyter notebook unet-3+residual_block.ipynb
Model Performance
The model is designed to improve segmentation performance by leveraging residual connections in the UNet-3+ architecture. Performance metrics such as Dice coefficient, IoU, and Accuracy can be evaluated after training.

Acknowledgments
This project is based on research in medical image segmentation and utilizes deep learning techniques for tumor detection.
