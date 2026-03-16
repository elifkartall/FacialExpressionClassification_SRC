# FacialExpressionClassification

🛠️ Technologies & Libraries I Use
<p align="left"> <!-- Python en üstte --> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> </p> <p align="left"> <!-- Grup 1 --> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"/> </p> <p align="left"> <!-- Grup 2 --> <img src="https://img.shields.io/badge/Matplotlib-F37626?style=for-the-badge&logo=matplotlib&logoColor=white"/> <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/PyWavelets-3F3F3F?style=for-the-badge&logo=python&logoColor=white"/> </p>

# Overview

This project explores facial expression recognition and image compression using three main approaches:

Singular Value Decomposition (SVD) – For image compression and reconstruction.

Principal Component Analysis (PCA) – To analyze facial features and reconstruct images using eigenfaces.

Sparse Representation-based Classification (SRC) – For identifying facial expressions using sparse coding. Additionally, Fourier and Wavelet transformations are used to evaluate the impact of different bases on classification performance.

## 📂 Dataset

Please check [**data folder**](https://github.com/elifkartall/FacialExpressionClassification_SRC/tree/main/data) to download image data first, or access it [**here**](https://drive.google.com/drive/folders/1ABehRVdE1_C0H5sOW0qDb7RPd93myDJD?usp=sharing) via Google Drive.

## 💻 Google Colab Notebook

You can access the Colab notebook [**here**](https://colab.research.google.com/drive/1sDYTmZrmx4Ie5wg-CrRQjrDPt_tlAy2B?usp=sharing).

# Project Structure
```
ML_HW1_EK/
│
├── angry_face.jpg  # Image for step a
│         
│
├── Part_B_images/
│   ├── happy/               # 10 happy faces
│   └── sad/                 # 10 sad faces
│
├── Part_C_images/
│   ├── train/ # there are 10 images in every file
│   │   ├── disgusted_faces/  
│   │   ├── happy_faces/           
│   │   ├── sad_faces/
│   │   └── surprised_faces/
│   └── test/  # there are 3 images in every file
│       ├── disgusted_faces/
│       ├── happy_faces/
│       ├── sad_faces/
│       └── surprised_faces/
│
└── ML_HW1_project.ipynb   
 ```

## 📝 Report
You can access the report file [**here**](Facial_Expression_Classification_EK.pdf) or via [**Google Drive**](https://drive.google.com/drive/folders/1ABehRVdE1_C0H5sOW0qDb7RPd93myDJD?usp=sharing).
