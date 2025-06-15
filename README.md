# ECSA-FSL-2025

## An Entropy-Driven Clustering and Semantic Association Framework for Cross-Domain Few-Shot Hyperspectral Image Classification.

This is a code demo for the paper "An Entropy-Driven Clustering and Semantic Association Framework for Cross-Domain Few-Shot Hyperspectral Image Classification". IEEE Transactions on Geoscience and Remote Sensing Letters, doi: 10.1109/LGRS.2025.3576715.

[1]Yan Wang, Fengyi Zhang, Jing Tian, Xuewei Gong , and Zhaokui LI,"An Entropy-driven Clustering and Semantic Association Framework for Cross-domain Few-shot Hyperspectral Image Classification" IEEE Transactions on Geoscience and Remote Sensing Letters, doi: 10.1109/LGRS.2025.3576715.

## Requirements

- CUDA = 12.4
- python = 3.9.19
- torch = 2.0.0+cu118
- transformers = 4.44.2
- scikit-learn = 1.5.1
- numpy = 1.26.3

## Datasets

You can download the source and target datasets mentioned above at https://pan.baidu.com/s/1erafsAzPYCdomqBziJpy-w?pwd=ddf1, and move to folder `datasets`.  An example datasets folder has the following structure:



```
datasets
├── Chikusei_imdb_128_7_7.pickle
├── Chikusei_raw_mat
│   ├── HyperspecVNIR_Chikusei_20140729.mat
│   └── HyperspecVNIR_Chikusei_20140729_Ground_Truth.mat
├── IP
│   ├── indian_pines_corrected.mat
│   └── indian_pines_gt.mat
├── Houston
│   ├── data.mat
│   ├── mask_train.mat
│   └── mask_test.mat
```

## Usage:

run `ECSA-FSL-IP.py`  or  `ECSA-FSL-HT.py`. 

