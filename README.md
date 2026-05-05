# Mirota Campus LLM Chatbot

This project is a Large Language Model fine-tuning project for building a question-answering chatbot about Mirota Kampus. The model is fine-tuned using instruction-based QA data and LoRA to make training more efficient.

## 📌 Overview

The goal of this project is to fine-tune an instruction-following language model so it can answer user questions related to Mirota Kampus clearly, politely, and accurately.

The dataset contains question-answer pairs about Mirota Kampus, including store information, shopping needs, student needs, product availability, and customer service responses.

## ✨ Features

- Load QA dataset from JSON file
- Validate instruction, input, and output fields
- Split dataset into train, validation, and test sets
- Format prompts using chat template
- Tokenize instruction-based dataset
- Build custom PyTorch Dataset and collate function
- Load base LLM from Hugging Face
- Fine-tune model using LoRA / PEFT
- Track training and validation loss
- Save LoRA adapter and tokenizer
- Generate responses on test data
- Save test predictions into JSON
- Evaluate model responses using an evaluator LLM
- Save evaluation scores and statistics

## Streamlit 

https://projekuaspmapingouin-ftgud4wkdgfypgf2982hv4.streamlit.app/

## 🧠 Model

Base model:

```txt
meta-llama/Llama-3.2-1B-Instruct
