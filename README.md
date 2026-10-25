# Brain Tumor MRI Classification

This repository contains five Jupyter notebooks for three-class brain tumor MRI classification using deep learning.

## Models

- **Custom CNN** — 100 epochs
- **DenseNet201** — 20 epochs
- **InceptionV3** — 20 epochs
- **MobileNetV2** — 20 epochs
- **VGG16** — 20 epochs

## Repository structure

```text
Brain_Tumor_Classification/
├── notebooks/
│   ├── Brain_Tumor_Custom_CNN_100_Epochs.ipynb
│   ├── Brain_Tumor_DenseNet201_20_Epochs.ipynb
│   ├── Brain_Tumor_InceptionV3_20_Epochs.ipynb
│   ├── Brain_Tumor_MobileNetV2_20_Epochs.ipynb
│   └── Brain_Tumor_VGG16_20_Epochs.ipynb
├── README.md
└── requirements.txt
```

## Dataset

The experiments use the publicly available **Brain Tumor Dataset** by Jun Cheng, hosted by Science Data Bank. The dataset contains 3,064 contrast-enhanced T1-weighted MRI images across three tumor classes: glioma, meningioma, and pituitary tumor. The dataset is not included in this repository; download it from the [official dataset record](https://doi.org/10.57760/sciencedb.06290) and configure the data paths in the notebooks.

Please cite the dataset if you use this code or dataset:

> Cheng J. Brain Tumor Dataset [DS/OL]. V1. Science Data Bank, 2022. https://cstr.cn/31253.11.sciencedb.06290. CSTR:31253.11.sciencedb.06290.

The dataset is distributed under the **CC BY 4.0** license. Review the dataset record for attribution and reuse terms.

## Installation and use

Use a Python environment compatible with the installed TensorFlow version, then run:

```bash
pip install -r requirements.txt
```

Open a notebook in Jupyter Notebook, JupyterLab, or Google Colab and execute the cells in order. Update dataset paths before training.

## Reproducibility

Saved notebook outputs are retained where available. Results may vary with dataset organization, random seeds, hardware, software versions, and execution settings. The dataset and trained model weights are not included unless explicitly saved in the repository.
