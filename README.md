# PRODIGY_GA_01
# 🧠 GPT-2 Text 

This project demonstrates how to use OpenAI's GPT-2 model (via Hugging Face Transformers) for text generation using various decoding strategies like greedy search, beam search, and sampling.

## 📌 Features

- Load pre-trained GPT-2 model and tokenizer
- Generate text using:
  - Greedy decoding
  - Beam search (with and without constraints)
  - Sampling methods (temperature, top-k, top-p)
- Generate multiple variations of the output
- Compare outputs from different strategies for the same prompt

## 🚀 Installation

Install required libraries using pip:

```bash
pip install transformers torch
