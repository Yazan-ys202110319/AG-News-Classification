# AG News Classification with PyTorch

This project is a hands-on PyTorch learning notebook for building a news topic classification model on the AG News dataset. The goal is to understand the full text-classification workflow by working through data loading, preprocessing, model building, training, and evaluation in one place.

## Project Goal

The notebook is designed to help you learn PyTorch by implementing an AG News classifier step by step. It uses the Hugging Face `datasets` library to load the dataset and provides a starting point for experimenting with a custom text classification model.

## Dataset

The project uses the AG News dataset, which contains news headlines and descriptions grouped into four categories:

- World
- Sports
- Business
- Sci/Tech

## What You Will Learn

- How to load and inspect a text dataset with Hugging Face
- How to prepare text data for PyTorch models
- How to build a neural network for multi-class text classification
- How to train and evaluate a model on AG News
- How to iterate on model performance with experiments

## Files

- [main.ipynb](main.ipynb): main notebook for the project

## Getting Started

1. Install the required Python packages.
2. Open [main.ipynb](main.ipynb).
3. Run the cells in order to explore the dataset and build the model.

### Suggested Dependencies

- `torch`
- `datasets`
- `numpy`
- `pandas`

If you want to extend the notebook later, you may also find `scikit-learn` and `matplotlib` useful for evaluation and visualization.

## Notes

This repository is currently focused on learning and experimentation rather than a production-ready pipeline. The notebook is intended to grow as the model, preprocessing, and evaluation steps are developed.
