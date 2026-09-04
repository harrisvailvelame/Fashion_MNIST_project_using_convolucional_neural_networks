# Fashion MNIST — CNN Image Classification

> Historical machine-learning project from my earlier Data Science work. My current portfolio focus is Data Engineering, lakehouse architecture, data quality and cloud platforms.

## Overview

This project trains a convolutional neural network to classify the 10 Fashion-MNIST image categories from 28×28 grayscale images.

The original experiment reports approximately **90.75% test accuracy** in the notebook. The metric is preserved here as an experimental result from that run, not as a production benchmark.

## What this project demonstrates

- supervised image classification;
- CNN modeling with Keras;
- train/test evaluation;
- numerical data handling with NumPy/Pandas;
- notebook-based experimentation and model iteration.

## Repository structure

```text
.
├── fashion_mnist_cnn.ipynb                     # original experiment
├── requirements.txt                            # reproducibility dependencies
└── .github/workflows/quality.yml               # lightweight repository checks
```

## Dataset

Fashion-MNIST contains 70,000 grayscale images across 10 apparel categories:

- 60,000 training images;
- 10,000 test images;
- 28×28 pixels per image.

The notebook loads the dataset through Keras, so the dataset itself is not duplicated in this repository.

## Reproduce locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook fashion_mnist_cnn.ipynb
```

## Engineering perspective

This repository is intentionally kept as an earlier ML artifact. For my current engineering work, see the Data Engineering portfolio in [`harrisvailvelame/pedrohvel`](https://github.com/harrisvailvelame/pedrohvel), including tested Medallion and dbt reference projects.

---

**Author:** Harrison Grant Vail  
[LinkedIn](https://www.linkedin.com/in/harrison-grant-vail) · [GitHub](https://github.com/harrisvailvelame)
