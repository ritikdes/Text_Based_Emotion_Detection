# Text-Based Emotion Detection

Hey! This repository contains the code, experiments, and model training scripts for my text-based emotion detection project. 

The goal here was to explore how well different transformer models (like BERT and RoBERTa) can pick up on subtle emotional cues from text data (like Reddit comments and standard NLP datasets).

## What's in here?

* **`notebooks/`**: Contains the Jupyter notebooks used for data exploration (EDA) and model training. 
  * `TBED_EDA_v3.ipynb`: Initial data analysis and preprocessing steps.
  * `TBED_bert_uncased_final.ipynb`: Training and fine-tuning pipeline for the BERT model.
* **Other versions**: I've left behind a few older experimental notebooks just to keep track of how the training evolved, though the main ones above are the clean/final versions.

## Tech Stack & Libraries
* Python
* PyTorch
* Hugging Face Transformers
* Scikit-learn / Pandas for data handling

## Quick Start
If you want to run or test the notebooks yourself:
1. Clone the repo:
   ```bash
   git clone [https://github.com/ritikdes/Text_Based_Emotion_Detection.git](https://github.com/ritikdes/Text_Based_Emotion_Detection.git)
