# Microscopy Image Analysis  
顕微鏡画像解析：ノイズ除去・粒子解析・Deep Learning 応用デモ

---
## License
Licensed under the MIT License (free for use, modification, and commercial redistribution).

## 🧭 Overview

This repository provides example notebooks and scripts for  
microscopy image analysis using Python.  
It covers basic image processing (denoising, filtering, binarization),  
machine learning (k-means clustering), and deep learning-based segmentation (Cellpose).

本リポジトリは、顕微鏡画像解析を題材にした教育・研究用のサンプルコードを提供します。  
ノイズ除去や二値化、粒子解析、k-means法による領域抽出、Cellposeを使った深層学習による分割を扱います。

---


---

## 🚀 Open in Google Colab

You can directly run each notebook on Google Colab using the buttons below 👇

| Notebook | Open in Colab |
|-----------|----------------|
| **Read_image.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Read_image.ipynb) |
| **Filter.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Filter.ipynb) |
| **Histogram_Equalization.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Histogram_Equalization.ipynb) |
| **Binarize.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Binarize.ipynb) |
| **kmeans.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/kmeans.ipynb) |
| **Cellpose.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Cellpose.ipynb) |
| **Evaluation.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Evaluation.ipynb) |
| **Binarize_粒子解析.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/Binarize_%E7%B2%92%E5%AD%90%E8%A7%A3%E6%9E%90.ipynb) |
| **kmeans_ver2.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/kmeans_ver2.ipynb) |
| **phaze_noise_reduction.ipynb** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/suzuki-ma/microscopy_image-analysis/blob/main/notebooks/phaze_noise_reduction.ipynb) |

---

## 🧩 How to Use in Colab

In each notebook, the following code clones this repository and installs dependencies:

```python
!git clone https://github.com/suzuki-ma/microscopy_image-analysis.git
%cd microscopy_image-analysis
!pip install -r requirements.txt

import sys
sys.path.append("src")
from binarize import binarize_image


📚 Dataset Acknowledgement

This repository includes sample images from the following publicly available datasets
(for demonstration only):

1️⃣ MP-Set: Microplastic Segmentation Dataset
Authors: Sanghyeon Austin Park et al. (2022)
License: CC BY 4.0
Source: Kaggle
Fluorescence microscopy images of microplastics (Nile Red stained).
One representative image is included here for demonstration.

2️⃣ EMPS: Electron Microscopy Particle Segmentation Dataset
Author: Batuhan Yilmaz (2021)
Image License: CC BY 4.0
Code License: MIT
Source: Kaggle
One representative electron microscopy image is included for demonstration.
Details are described in data/README_DATA.md
.

