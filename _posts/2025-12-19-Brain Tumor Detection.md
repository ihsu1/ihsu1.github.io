---
layout: post
title:  "MRI Brain Tumor Detection"
date:   2025-12-19
categories: projects
---

This is the write up for my final project in CPSC 066 Machine Learning (ML). 

## Abstract

Because of its potential to support accurate and efficient decision-making, machine learning (ML) has become an increasingly important tool for automating complex pattern recognition tasks in the medical field. Our goal with this project is to apply deep learning techniques to detect brain tumors from MRI scans. In this paper, we compare the performance of traditional machine learning models– K-Nearest Neighbors, Decision Trees, Logistic Regression, and Random Forest classifiers– with Convolution Neural Networks (CNN), which are often considered the state-of-the-art models for image-based tasks. We then try to optimize our CNN using data augmentation and hyperparameter tuning with Optuna. Our results indicate that the hyperparameter-optimized CNN achieved the best performance overall, reaching 79.4% accuracy and an F1-score of 0.84. However, contrary to our initial hypotheses, both the baseline CNN and the CNN with data augmentation had lower performance than the traditional classifiers. These results highlight the challenges of applying CNNs to small, imbalanced datasets, a difficulty common in the medical imaging field. To address these limitations and move toward clinically-deployable reliability, we suggest future work should focus on expanding the dataset with alternative sources of data that are relevant and more readily available.  

<iframe src="{{ 'assets/finalproject_moludar1_ihsu1_main.pdf' | relative_url }}" width="100%" height="700px">
    This browser does not support PDFs. Please download the PDF to view it: <a href="{{ 'assets/finalproject_moludar1_ihsu1_main.pdf' | relative_url }}">Download PDF</a>.
</iframe>

Due to class policy, please reach out for the code. 
