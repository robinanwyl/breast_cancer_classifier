# breast_cancer_classifier
BENG 203/CSE 283 SP25 Final Project
Group 3: Robin Anwyl, Krithika Iyer, Maahi Shah

The goal of this project is to train a breast cancer classifier to classify cancer vs. non-cancer samples from Zhou et al (2019). We trained and compared performance of several classifiers (support vector machine, random forest, and multi-layer perceptron), leveraging biology-inspired approaches for feature selection (regulons and commercial breast cancer gene panels) and taking steps to minimize overfitting.

This repo contains two Jupyter notebooks (from Google Colab). `BENG203_CSE283_DiffExpr_FeatureSets.ipynb` contains code for differential expression analysis on the dataset and curation of feature sets. `BENG203_CSE283_ClassifierTraining.ipynb` contains code to train the SVM, RF, and MLP classifiers.

Dataset source: Zhou, Z., Wu, Q., Yan, Z., Zheng, H., Chen, C. J., Liu, Y., Qi, Z., Calandrelli, R., Chen, Z., Chien, S., Su, H. I., & Zhong, S. (2019). Extracellular RNA in a single droplet of human serum reflects physiologic and disease states. Proceedings of the National Academy of Sciences of the United States of America, 116(38), 19200–19208.
