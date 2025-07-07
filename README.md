# My First Sentiment Analysis Project with DistilBERT

## Project Overview

This is my hands-on NLP project where I fine-tuned a pre-trained DistilBERT model for sentiment analysis. My goal was to classify movie reviews as positive or negative, getting practical experience with transformer models.

## What I Did & Learned

*   **Fine-tuning DistilBERT:** Applied transfer learning by adapting `DistilBERT-base-uncased` to a specific text classification task.
*   **Text Data Handling:** Gained experience with tokenization, padding, and truncation using the Hugging Face `tokenizer`.
*   **Efficient Training:** Used the Hugging Face `Trainer` API for streamlined model training and evaluation.
*   **Practical Optimization:** Consciously optimized for speed by choosing a smaller model, using a data subset, leveraging Google Colab's GPU, and enabling mixed precision (`fp16`) training.

## Tools & Libraries Used

*   Python
*   Hugging Face Transformers & Datasets
*   PyTorch
*   Google Colab

## How to Run This Project

You can run this project easily on Google Colab:
1.  Open `sentiment_analysis_with_distilbert.ipynb` in Colab.
2.  Ensure `GPU` runtime is selected (`Runtime > Change runtime type`).
3.  Run all cells.

## Project Files

*   `sentiment_analysis_with_distilbert.ipynb`: The core notebook.

---

I'm excited about this learning experience!
