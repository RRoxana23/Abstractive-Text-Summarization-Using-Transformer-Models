# Abstractive Text Summarization Using Transformer Models

This repository contains the experimental software developed for a Deep Learning project on abstractive text summarization using Transformer models. The project focuses on fine-tuning a pre-trained T5 model on the CNN/DailyMail dataset and comparing its performance with an extractive baseline.

---

## Open in Google Colab

You can run the full experiment directly in Google Colab using the link below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/RRoxana23/Abstractive-Text-Summarization-Using-Transformer-Models/blob/main/Text_Summarization.ipynb
)

---

## Project Overview

- Task: Abstractive text summarization
- Model: T5-small (Transformer encoder–decoder)
- Dataset: CNN/DailyMail
- Baseline: Lead-3 extractive summarization
- Evaluation Metrics: ROUGE-1, ROUGE-2, ROUGE-L, ROUGE-Lsum

---

## Repository Contents

- `Text_Summarization.ipynb`  
  Google Colab notebook containing the full experimental pipeline:
  - dataset loading and preprocessing
  - model fine-tuning
  - evaluation and comparison
  - result visualization

---

## How to Run the Code (Google Colab)

The experiment was developed and tested using Google Colab. To reproduce the results, follow these steps:

1. Open the notebook in Google Colab:
   - Click the **"Open in Colab"** button at the top of the notebook on GitHub  
   or  
   - Upload `t5_cnn_dailymail_summarization.ipynb` manually to Google Colab.

2. In Colab, set the runtime to use a GPU:
   - `Runtime → Change runtime type`
   - Hardware accelerator: **GPU**

3. Run the notebook cells sequentially from top to bottom.
   - All required libraries are installed automatically.
   - Dataset downloading is handled via the Hugging Face Datasets library.

4. The following outputs will be generated:
   - Training loss curve
   - ROUGE score tables
   - ROUGE comparison figures
   - Qualitative summary examples

---

## Reproducibility

- A fixed random seed is used throughout the experiment.
- All hyperparameters and configuration details are explicitly defined in the notebook.
- Evaluation is performed on a fixed subset of the test set.

---

## Author

Roxana-Georgiana Albăstroiu
