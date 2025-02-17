📖 Gemma Model Document Q&A - Streamlit App

📌 Overview

This project is a Streamlit-based document Q&A system that uses LangChain, FAISS, and Google Generative AI Embeddings to provide accurate answers based on uploaded documents. It leverages vector embeddings for retrieval-augmented generation (RAG) and supports GROQ Llama 3 model for natural language responses.

🔍 Key Features

🚀 Document Ingestion & Processing:

Uploads PDFs and processes text using PyPDFDirectoryLoader.

Splits documents into chunks using RecursiveCharacterTextSplitter.

📊 Embedding & Retrieval:

Uses Google Generative AI Embeddings to create high-quality vector embeddings.

Stores and retrieves document vectors using FAISS.

🤖 Question Answering:

Queries documents through LangChain’s retrieval chain.

Uses GROQ-powered Llama 3 model for precise responses.

🛠 Future Enhancements

✅ Integrate OpenAI and Anthropic models for comparison.

✅ Add database storage (PostgreSQL) for persistent document retrieval.

✅ Improve UI with better document visualization tools.
