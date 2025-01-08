# 💻 BigDataAnalytics_Laboratory_works

This repository contains laboratory works written in Python and completed during the "Big Data Analytics" course at the National Technical University of Ukraine 'Kyiv Polytechnic Institute', IASA AI department, during the second semester of the master's program from February to June 2024. Scikit-learn library was used for Machine Learning, MLxtend for Data Mining, and PyTorch library with Lightning for deep learning, where GPU acceleration was utilized to boost training speed.

---

## 🔬 Laboratory work 1

Tasks completed:
- Performed EDA and data preprocessing for 'loan_data.csv' including class labels, nominal and ordinal features encoding.
- Performed comparison of different algorithms and strategies for filling in missing values and analyzed the results.

---

## 🔬 Laboratory work 2

- Data used:
    - Breast Cancer Wisconsin (Diagnostic) Dataset.
    - Artificially generated classification datasets with samples>>features / samples<<features.
- Tasks completed:
    - Performed EDA and data preprocessing.
    - Compared different feature selection methods.

---

## 🔬 Laboratory work 3

- For Breast Cancer Wisconsin (Diagnostic) Dataset and artificially generated classification dataset compared different dimensionality reduction methods including usage of a deep autoencoder.

---

## 🔬 Laboratory work 4

- Data used:
    - "Moons" data with small/big amount of samples.
    - "Blobs" data with small/big amount of samples.
- Tasks completed:
    - Found best hyperparameters for BIRCH using Grid-search that optimize Homogenity, Completness or V-mesure.
    - Evaluated the stability BIRCH with obtained hyperparameters using the Jaccard index and resampling.

---

## 🔬 Laboratory work 5

Tasks completed:
- Performed EDA for Bakery Transactions Dataset.
- Using Apriori and FP-Growth algorithms:
    - Found best hyperparameters for the algorithm to search significant rules using Grid-search.
    - Found frequent itemsets and significant association rules using obtained hyperparameters.
- Compared results produced by these two algorithms.
- Performed predictions for possible goods that might be bought with a given set.

---

## 🔬 Laboratory work 6

Tasks completed:
- Trained Deep Convolutional Generative Adversarial Network on 'Anime Face Dataset'.
- Performed interpolation between several pairs of faces using obtained GAN model.
- Tested the continuity of the GAN latent space on practice.

---

## 🔬 Additional task with SRGAN (Super Resolution GAN)

- Trained the SRGAN on CelebADataset with different combinations of vanila/pretrained on ImageNet weights for discriminator/generator and with/without EMA for generator and compared the results.