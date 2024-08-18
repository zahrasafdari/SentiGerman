# German Text Sentiment Classification

## Overview

This project focuses on classifying sentiment in German text using two transformer-based models: BERT and RoBERTa. The models are trained and evaluated on the SB10K dataset, which is accessible from [here](https://github.com/oliverguhr/german-sentiment/tree/master/source-data/SB10k). The goal is to classify text into three sentiment categories: positive, negative, and neutral.

## Model Architecture

The project implements the following models:
- **SimpleBERTModel**: A BERT-based model for sentiment classification.
- **SimpleRoBERTaModel**: A RoBERTa-based model for sentiment classification.

Both models are fine-tuned on the SB10K dataset using PyTorch and the `transformers` library.

## Dataset

The dataset used for this project is the SB10K dataset. It can be downloaded from the following link: [SB10K Dataset](https://github.com/oliverguhr/german-sentiment/tree/master/source-data/SB10k).

## Project Structure

- `SentimentDataset`: A custom dataset class for loading and processing the SB10K data.
- `SimpleBERTModel`: A custom BERT model for sentiment classification.
- `SimpleRoBERTaModel`: A custom RoBERTa model for sentiment classification.

## Requirements

- `torch`
- `transformers`
- `pandas`
- `sklearn`

You can install the required packages using:

```bash
pip install torch transformers pandas scikit-learn
```


2. **Run the Training**: Execute the `train.py` script to start the training process. This script trains both the BERT and RoBERTa models and evaluates their performance on the test set.

```bash
python train.py
```

## Model Diagram
![sentiment-diagram drawio (1)](https://github.com/user-attachments/assets/8191fcd4-679f-4720-a658-22e620c66c54)
