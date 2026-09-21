# Image Compression, Reconstruction, and Facial Feature Analysis via PCA & SVD

An exploratory data science and image processing project investigating Principal Component Analysis (PCA), Singular Value Decomposition (SVD), image compression, patch reorganization, and facial feature encryption/decryption effects.

---

## 📌 Project Overview

This project utilizes the famous **Lenna** image and facial datasets to conduct comprehensive experiments on matrix approximations and feature transformations. Key objectives include:
* **Image Compression & Reconstruction**: Implementing SVD-based rank-$q$ approximation to compress and restore images while maintaining high quality.
* **Matrix Reorganization Analysis**: Comparing different matrix rearrangement arrangements before rank-$q$ approximation under identical compression ratios to observe and explain restoration quality.
* **Patch-Based Processing**: Cutting and reassembling images with various patch sizes to evaluate digital image compression and generation behaviors.
* **Encryption & Decryption Effects**: Analyzing the effectiveness of face vs. non-face encryption/decryption, and testing the feasibility of using facial features to encrypt non-face images.

---

## 🚀 Pipeline & Experimental Workflow

1. **SVD Rank-$q$ Approximation**: Applying singular value decomposition to image matrices to retain dominant singular values and achieve target compression ratios.
2. **Matrix Reorganization (Arrangements)**: Experimenting with different structural arrangements of image matrix $X$ prior to compression to determine optimal restoration fidelity.
3. **Patch Cutting & Reassembly**: Segmenting images into distinct patch sizes, analyzing localized spatial correlations, and studying reconstruction quality.
4. **Facial Feature Encryption / Decryption**: Investigating transformation effects on facial versus non-facial images, and evaluating cross-domain security and encryption feasibility.

---

## 🛠️ Tech Stack

* **Language**: Python
* **Libraries**: `NumPy`, `SciPy`, `Matplotlib`, `Scikit-Learn`
* **Data Sources**: Lenna Image Standard Test Dataset, Facial and Non-Facial Image Datasets.
