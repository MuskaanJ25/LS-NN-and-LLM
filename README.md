# LS- NN & LLM Final Project: English to French Translator
## Task
Translation of text is very impoertant to communication. Most of us have needed a translator at some point. This project aims to build a simple English to French translator by leveraging the efficiency of the T5 (Text-to-Text Transfer Transformer) model to provide fast and accurate French text.

## Why T5?
T5 is a powerful and versatile language model architecture developed by Google Research. Unlike earlier transformer models that were designed for specific tasks (e.g., BERT for masked language modeling, GPT for autoregressive text generation), T5 follows a unified "text-to-text" framework. In this framework, both input and output are treated as sequences of text, allowing T5 to handle a wide range of natural language processing tasks by transforming one sequence into another.

## Dataset
We have used the opus_books Dataset from Hugging Face for training and evaluating our fine-tuned T5 model. This dataset contains a collection of parallel sentences in English and their corresponding translations in French.

[Link to HuggingFace Dataset- Opus Books](https://huggingface.co/datasets/opus_books)

## Challenges
- Finding the right packages needed with PyTorch. Some version problems lead to multiple errors
- Waiting time for the model to train :|

