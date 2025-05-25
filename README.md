# NLP Project - Sentiment Analysis on Tweets (with Gradio Demo)

This project performs sentiment analysis on tweets using a fine-tuned BERT model and compares it with a Logistic Regression baseline using TF-IDF features. A simple Gradio interface is included to test the model in real time.

## 🧠 Models Used
- **BERT (`bert-base-uncased`)** for deep learning classification
- **Logistic Regression** with TF-IDF features as baseline

## 📊 Dataset
- Sentiment140 Dataset: https://www.kaggle.com/datasets/kazanova/sentiment140
- Preprocessed to remove mentions and URLs

## 📦 Requirements
- `transformers`
- `torch`
- `pandas`
- `scikit-learn`
- `gradio`
- `tqdm`

Install them with:

```bash
pip install transformers torch pandas scikit-learn gradio tqdm
