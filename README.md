# Simple ML Chatbot

## Overview

This repository contains a lightweight machine learning (ML) chatbot built in Python. The chatbot is trained on a small intents dataset, learning to classify user inputs and generate appropriate responses. While simple, it demonstrates the fundamentals of designing, training, and evaluating conversational AI models.

## Features

* **Intent classification**: Trains a model to recognize user intents from text.
* **Model training**: Includes an epochs-based training loop with loss tracking.
* **Prediction**: Generates responses based on predicted intent.
* **Notebook format**: Implemented in a Jupyter Notebook (`ChatBot.ipynb`) for clarity and reproducibility.

## Why This Matters

This project showcases my ability to:

* Translate product ideas into working ML prototypes.
* Structure and train simple Natural Language Processing (NLP) models.
* Document and share projects in a reproducible way.
* Consider next steps for scaling from demo to production.

## Tech Stack

* Python
* TensorFlow / Keras (for training)
* Numpy, Scikit-learn
* Jupyter Notebook

## Repository Structure

```bash
simple-ml-chatbot/
│
├── README.md            # Project overview
├── requirements.txt     # Dependencies
│
├── notebooks/           # Jupyter notebooks
│   └── ChatBot.ipynb
│
├── data/                # Training data (e.g., intents.json)
│   └── README.md
│
├── models/              # Saved model files after training
│   └── README.md
│
└── src/                 # Source code scripts
    └── README.md
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/juanocampo400/simple-ml-chatbot.git
   cd simple-ml-chatbot
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Download NLTK resources (run this once inside Python):

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```
4. Open the notebook:

   ```bash
   jupyter notebook ChatBot.ipynb
   ```

## Future Enhancements

* Expand training data for better coverage.
* Add word embeddings for improved text understanding.
* Build a web app interface with Flask or FastAPI.
* Explore transformer-based models (e.g., BERT).

## Notes

This is not a production system. It is intended as a **demonstration of ML applied to conversational AI**.
