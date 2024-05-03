# Deep_Learning_Hanoi
# Leak Detection and Localization using 1D CNN

This repository contains the code for detecting and localizing leaks in water distribution networks using a 1D Convolutional Neural Network (CNN). The model is applied to the LeakDB (Leakage Diagnosis Benchmark) dataset.

## Dataset: LeakDB

LeakDB (Leakage Diagnosis Benchmark) is a realistic leakage dataset for water distribution networks. The dataset is comprised of a large number of artificially created but realistic leakage scenarios, on different water distribution networks, under varying conditions. A scoring algorithm in MATLAB code is provided to evaluate the results of different algorithms.

You can download the complete LeakDB dataset from [here]([https://ucy-my.sharepoint.com/personal/mkiria01_ucy_ac_cy/_layouts/15/onedrive.aspx?ga=1&id=%2Fpersonal%2Fmkiria01%5Fucy%5Fac%5Fcy%2FDocuments%2FLeakage%2DBenchmark%2DDataset%2FLeakDB%2FBENCHMARK](https://ucy-my.sharepoint.com/personal/mkiria01_ucy_ac_cy/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fmkiria01%5Fucy%5Fac%5Fcy%2FDocuments%2FLeakage%2DBenchmark%2DDataset%2FLeakDB&ga=1)).

## Files

The repository contains the following Jupyter Notebook files:

1. `pre-processing finAL.ipynb`: This notebook contains the code for preprocessing the LeakDB dataset.
2. `LeakDetection2-4-24.ipynb`: This notebook contains the code for detecting leaks in the preprocessed dataset using a 1D CNN model.
3. `Leak Localization.ipynb`: This notebook contains the code for localizing leaks in the preprocessed dataset using a 1D CNN model.

## Usage

1. Clone this repository:https://github.com/KarandeepSinghSodhi/Deep_Learning_Hanoi.git
2.  Run the Jupyter Notebook files in the following order:
- `pre-processing finAL.ipynb`
- `LeakDetection2-4-24.ipynb`
- `Leak Localization.ipynb`

## Requirements

- Python 3
- Jupyter Notebook
- TensorFlow
- NumPy
- Pandas
- Matplotlib



