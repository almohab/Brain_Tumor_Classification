Brain Tumor MRI Classification

This repository contains five Jupyter notebooks for three-class brain tumor MRI classification using deep learning.

Models

Custom CNN — 100 epochs

DenseNet201 — 20 epochs

InceptionV3 — 20 epochs

MobileNetV2 — 20 epochs

VGG16 — 20 epochs

Repository Structure

Brain_Tumor_Classification/
├── Notebooks/
│   ├── Brain_Tumor_Custom_CNN_100_Epochs.ipynb
│   ├── Brain_Tumor_DenseNet201_20_Epochs.ipynb
│   ├── Brain_Tumor_InceptionV3_20_Epochs.ipynb
│   ├── Brain_Tumor_MobileNetV2_20_Epochs.ipynb
│   └── Brain_Tumor_VGG16_20_Epochs.ipynb
├── README.md
└── requirements.txt

Dataset

The experiments use the publicly available Brain Tumor Dataset by Jun Cheng, hosted by Science Data Bank. It contains 3,064 contrast-enhanced T1-weighted MRI images covering three tumor classes:

Glioma

Meningioma

Pituitary tumor

The dataset is not included in this repository. Download it from the official dataset record and update the dataset paths in the notebooks before running them.

Dataset Citation

Please cite the original dataset when using it in your research:

Cheng J. Brain Tumor Dataset [DS/OL]. V1. Science Data Bank, 2022. https://cstr.cn/31253.11.sciencedb.06290. CSTR:31253.11.sciencedb.06290.

The dataset is reported as being distributed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. Please consult the official dataset record for the applicable attribution and reuse terms.

Installation

Install the required Python packages in your environment:

pip install -r requirements.txt

How to Run

Clone or download this repository.

Download the dataset from the official source.

Extract the dataset and update the image paths in the notebooks.

Install the required dependencies.

Open a notebook using Jupyter Notebook, JupyterLab, or Google Colab.

Run the notebook cells in order.

Reproducibility

The notebooks contain the model training and evaluation workflows. Saved outputs are retained where available. Results may vary depending on dataset organization, random seeds, hardware, software versions, and training settings.

The dataset and trained model weights are not included in this repository unless explicitly added.

Disclaimer

This repository is intended for research and educational purposes. The models are not intended to replace professional medical diagnosis or clinical judgment.
