# 📰 Headline Generator using mT5

This project generates short headlines from full-length articles using the `google/mt5-small` model, developed during a hackathon. While the initial model underperformed due to assumptions about multilingual capabilities, the project laid the groundwork for future improvement and deployment.

---

## 📌 Summary

- Model: `google/mt5-small` (Hugging Face `transformers`)
- Task: Article → Headline (Text Summarization)
- Framework: `Seq2SeqTrainer` from Hugging Face
- Dataset: Provided during the hackathon (article–headline pairs)
- Issue: Model struggled on English-only data, producing weak summaries

---

## 🚀 Planned Improvements

- Replace with a better-suited model (`t5-base`, `BART`, or `PEGASUS`)
- Fine-tune on robust summarization datasets (CNN/DailyMail, XSum)
- Add evaluation metrics (ROUGE, BLEU)
- Build a Streamlit/Gradio app for interactive headline generation

