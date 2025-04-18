# ❓ Question Answering System Using Transformers

A powerful and efficient Question Answering (QA) system built using the **ALBERT-base-v2** transformer model. It leverages Hugging Face's `transformers` and `datasets` libraries, fine-tuned on the **SQuAD 2.0** dataset to answer questions given a context passage.

---

## 🚀 Features

- 🧠 Fine-tuned ALBERT model for extractive question answering
- 📚 Trained on SQuAD 2.0 (Stanford Question Answering Dataset)
- ✅ Supports "no answer" questions as well
- 🧪 Evaluated with EM (Exact Match) and F1 metrics
- 📎 Easily test the model with custom context and questions

---

## 🛠️ Tech Stack

- Python 3.11
- Hugging Face Transformers
- Datasets (`squad`)
- PyTorch
- Google Colab (GPU T4 - free tier)

---

## 🧑‍🏫 Model Architecture

The model used is:

> `albert-base-v2` – A Lite BERT optimized for performance and low memory usage, ideal for Colab environments.

---

## 📊 Evaluation Metrics

- **Exact Match (EM)** – Measures how many predictions match the ground truth exactly.
- **F1 Score** – Harmonic mean of precision and recall between predicted and actual answers.

Example output:
```text
Exact Match (EM): 74.12
F1 Score: 80.37
