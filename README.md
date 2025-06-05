# 📚 Text- Based Question Answering using LLM + RAG (LangChain + HuggingFace)

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using **LangChain** and a **Hugging Face LLM** to answer questions from **PDF documents**.

> ✅ Built in Google Colab using Python

---

## 🔍 What It Does

- 📄 Reads and parses content from a PDF file  
- ✂️ Splits the document into manageable chunks  
- 🧠 Converts text to embeddings and stores them in a FAISS vector store  
- 🔎 Retrieves relevant chunks based on user queries  
- 🤖 Uses an LLM (e.g., BLOOM) to generate answers from those chunks  

---

## 🧠 Technologies Used

- [LangChain](https://github.com/langchain-ai/langchain)
- [Transformers (Hugging Face)](https://huggingface.co/transformers/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [PyPDF](https://pypi.org/project/pypdf/)
- Google Colab (runtime environment)

---

## 🚀 How to Run (in Colab)

1. **Install required packages**:
```python
!pip install -U langchain langchain-community faiss-cpu transformers huggingface_hub pypdf
