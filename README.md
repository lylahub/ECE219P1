# ECE 219 Project 1 – Text Embeddings and Classification

This repository contains code for **Project 1** of ECE 219 (Large-Scale Data Mining), which studies document representations for text mining and evaluates them via downstream classification tasks.

---

## How to Run

1. Obtain the dataset using the link provided in the project handout (https://drive.google.com/file/d/1qOsO1ocP9WT0pK1CMK2EDNlmqemSZID8/view?usp=sharing).
2. Place the dataset file as `dataset.csv` in the repository root.
3. Open `P1_code.ipynb` in a Jupyter environment.
4. Run the notebook cells in order.

> The dataset file is **intentionally ignored** and not tracked in this repository.

---

## Repository Contents

- `P1_code.ipynb`  
  Main notebook implementing the project pipeline, including:
  - Dataset inspection and visualization
  - Text embedding methods (TF–IDF, pretrained embeddings, Transformer encoders)
  - Dimensionality reduction (LSI / NMF)
  - Binary and multiclass classification
  - Evaluation and comparison of representations

- `.gitignore`  
  Excludes the dataset and other non-source artifacts.

---

## Dataset Summary

The dataset consists of news articles with hierarchical labels:
- **root_label**: `sports`, `climate`
- **leaf_label**: 10 fine-grained topic classes under the two root categories