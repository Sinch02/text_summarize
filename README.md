Start editing…# 🤖 LLM-Based Web Page Summarizer & Chatbot using Hugging Face

This project showcases two different approaches to working with Large Language Models (LLMs) using the Hugging Face `transformers` library inside Google Colab. It demonstrates both:

- 🔹 **Web page summarization using BART (`facebook/bart-large-cnn`)**
- 🔹 **Chat/Q&A style interaction using FLAN-T5 (`google/flan-t5-base`)**

---

## 📌 Project Overview

| Model                | Task Type       | Description                                                  |
|----------------------|------------------|--------------------------------------------------------------|
| `facebook/bart-large-cnn` | Summarization   | Extracts `<p>` tags from any public webpage and summarizes the content. |
| `google/flan-t5-base`     | Chat/Q&A / Inference | Acts like a lightweight chatbot or instruction-following model. |

Both models are open-source and run **locally in Colab** using PyTorch backend — ✅ no API keys required.

---

## 🧰 Tech Stack

- Python
- Hugging Face Transformers
- Google Colab
- BeautifulSoup4 (for web scraping)
- IPython Markdown display

---

## 📂 File Structure
├── README.md
├── summarizer_bart.ipynb # Web summarizer using BART
├── flan_qa_chat.ipynb # QA/chat-style prompts using FLAN-T5
├── requirements.txt (optional)


---

## 🚀 How to Run in Google Colab

1. **Open Colab**
2. Upload `.ipynb` file or open directly from GitHub
3. Run cells from top to bottom
4. For summarization, pass any public URL (like Wikipedia)
5. For FLAN, type a question like:  



---

## 🔍 Example URLs to Test

- https://en.wikipedia.org/wiki/Artificial_intelligence
- https://en.wikipedia.org/wiki/Natural_language_processing

---

## ✨ Example Outputs

### ✅ BART Summary


### 💬 FLAN Chat
Q: What is deep learning?
A: Deep learning is a subfield of machine learning that uses neural networks to learn from data.


---

## 📦 Requirements

Install necessary dependencies:

```bash
pip install transformers sentencepiece bs4
