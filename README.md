# Hybrid RAG + LLM AI Assistant

## Overview
This project is a mini ChatGPT-style assistant built using Python, Groq, LangChain, ChromaDB, and HuggingFace embeddings.

It works in two intelligent modes:

- **RAG Mode** → Uses uploaded/custom documents to answer questions
- **General LLM Mode** → Answers open-ended general knowledge questions

## Tech Stack
- Python
- Jupyter Notebook
- Groq API
- LangChain
- ChromaDB
- HuggingFace Embeddings

## Features
- Document-based question answering
- General AI assistant behavior
- Semantic search
- Vector database retrieval
- Hybrid fallback architecture
- Beginner-friendly GenAI project

## Example Questions
- What is RAG?
- Explain machine learning
- Who is Lionel Messi?
- What tools does a data analyst use?

## How It Works
1. Load documents
2. Split text into chunks
3. Convert chunks into embeddings
4. Store in ChromaDB
5. Retrieve relevant context
6. Use LLM to generate answers
7. Fall back to general LLM if needed

## Future Improvements
- PDF upload support
- Streamlit UI
- Chat history memory
- Multi-document support
- Deployment

## Author
Kiran Abhinav
