# 📚 Conversational PDF Chatbot with Gemini

This repository contains a Jupyter Notebook that builds an **AI-powered chatbot** to interact with PDF manuals.  
The chatbot uses **LangChain**, **FAISS**, **HuggingFace embeddings**, and **Google Gemini models** to provide accurate, source-cited answers to user queries.

---

## 🚀 Features
- 📂 Load and process multiple PDF manuals
- ✂️ Split documents into chunks for efficient retrieval
- 🔎 Store embeddings in a FAISS vector database
- 🤖 Conversational chatbot powered by **Gemini**
- 📖 Answers include **citations** (document name & page number)

---

## 🛠️ Tech Stack
- [LangChain](https://www.langchain.com/) – framework for building LLM applications  
- [HuggingFace Transformers](https://huggingface.co/) – embeddings (`all-MiniLM-L6-v2`)  
- [FAISS](https://github.com/facebookresearch/faiss) – vector search database  
- [Google Gemini](https://ai.google.dev/) – large language model for response generation  
- [PyPDFLoader](https://python.langchain.com/docs/modules/data_connection/document_loaders/pdf) – PDF ingestion  

---

## 📂 Project Structure
