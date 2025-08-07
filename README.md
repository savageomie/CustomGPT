# 🧠 Darija LLM – Training a Custom Language Model on WhatsApp Chat Data

This project demonstrates how to build and train a small Large Language Model (LLM) using **WhatsApp-style chat data** in a low-resource language — in this case, **Darija**, the Moroccan Arabic dialect.

Although I’m an Indian developer and don’t speak Darija, I chose this dataset intentionally to explore how transformer models behave when trained on underrepresented, conversational languages. The techniques shown here apply equally well to **Hinglish, Hindi, Marathi**, and other code-mixed or Indian vernaculars.

This project serves as a practical guide for anyone looking to create their own LLM — from scratch — in any language.

---

## 📚 Project Highlights

- ✅ WhatsApp-style chat dataset used for training
- ✅ End-to-end training: from tokenization to fine-tuning
- ✅ Custom GPT-style Transformer model
- ✅ LoRA-based instruction tuning
- ✅ Lightweight and fast training (~42M parameters)
- ✅ Adaptable to **any language** (e.g., Hinglish, Hindi, Bengali)

---

## 📦 Repository Structure

```bash
.
├── notebooks/             # Jupyter notebooks for each pipeline stage
├── transformer/           # Custom GPT-style transformer code
├── minbpe/                # Minimal BPE tokenizer
├── data/                  # Training data (Darija chat samples)
├── assets/                # Chat samples, screenshots
├── Slides.odp             # Slides used in video walkthrough
├── requirements.txt       # Python dependencies
└── README.md              # This file
