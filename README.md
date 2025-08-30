# 📌 Prompting LLMs for Sentiment Analysis
**IMDB Movie Reviews using Claude 3.5 Sonnet and LLaMA-3-70B-Instruct**

---

## 📄 Overview
This project explores the application of large language models (LLMs) for zero-shot and few-shot sentiment analysis using the IMDB movie reviews dataset. It compares the performance, fluency, and efficiency of two cutting-edge instruction-tuned LLMs:

- [Claude 3.5 Sonnet](https://www.anthropic.com/news/claude-3-5-sonnet) – API hosted by Anthropic  
- [Meta LLaMA-3-70B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-70B-Instruct) – via Hugging Face

---

## 🚀 Key Highlights

- ✅ **Model Prompting**: Different prompt formats evaluated, including system messages and dynamic task injection.
- 📊 **Inference**: Batch prediction of sentiment on IMDB reviews using both models on a `g4dn.xlarge` instance.
- 🔍 **Evaluation**: Accuracy, latency, and cost-per-token comparisons between Claude and LLaMA-3.
- 🧠 **Observations**: Insights on how model size and prompt design influence output quality.

---

## 🛠️ Tech Stack

- Python
- Hugging Face Transformers
- Claude API (Anthropic)
- Pandas, Matplotlib, Seaborn
