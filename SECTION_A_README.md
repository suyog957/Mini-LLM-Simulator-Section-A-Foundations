# 🧠 Mini-LLM Simulator – Section A: Foundations

A step-by-step educational notebook that simulates how Large Language Models (LLMs) process raw text in their earliest stages — tokenization, encoding, and vectorization — **without using any deep learning frameworks**.

This is part of a larger project that walks through how transformer-based LLMs work internally, using only `NumPy`, `Matplotlib`, and `Seaborn`.

---

## 📌 Section A: Foundations

This module simulates the **input processing pipeline** of an LLM using a small example:

> **Paragraph:** The cat sat on the mat. It was sunny outside.  
> **Question:** Where did the cat sit?

We trace how this text becomes a numerical form that models can work with.

---

### ✅ Topics Covered

| Step | Topic | Description |
|------|-------|-------------|
| 1️⃣ | **Whitespace Tokenization** | Basic split by space characters |
| 2️⃣ | **Simulated Subword Tokenization (BPE-like)** | Approximate BPE to split into subword units |
| 3️⃣ | **Token → ID Mapping** | Assign a unique ID to each token |
| 4️⃣ | **One-hot Encoding** | Sparse binary vector for each token |
| 5️⃣ | **🔍 Visualizations** | - Token ID heatmap<br>- One-hot encoding heatmap |

---

## 🔧 Requirements

- Python 3.8+
- `numpy`
- `matplotlib`
- `seaborn`

Install dependencies:

```bash
pip install numpy matplotlib seaborn

