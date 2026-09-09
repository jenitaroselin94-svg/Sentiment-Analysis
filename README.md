# Sentiment Analysis

A simple AI-powered Sentiment Analysis web application built using Python, Streamlit, and Hugging Face Transformers.

This application analyzes the given text and predicts whether the sentiment is Positive or Negative.

## Features

- Enter any text or sentence
- AI-based sentiment prediction
- Displays sentiment result
- Shows confidence score
- Simple and user-friendly interface
- Uses a pre-trained Hugging Face Transformer model

## Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- PyTorch

## Model Used

This project uses the pre-trained model:

`distilbert-base-uncased-finetuned-sst-2-english`

The model performs binary sentiment classification:

- Positive
- Negative

## Project Structure

```text
Sentiment-Analysis/
│
├── app.py
├── README.md
└── requirements.txt
