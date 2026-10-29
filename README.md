# RAG Document Q&A Application

A Retrieval-Augmented Generation (RAG) application that allows users to upload documents and ask questions about their content using open-source language models.

## Features
- Upload PDF, TXT, Markdown, and HTML documents.
- Split documents into chunks with configurable overlap.
- Generate embeddings using Sentence Transformers.
- Store and retrieve document vectors using FAISS.
- Generate context-based answers using Hugging Face FLAN-T5.
- Display answers and retrieved source excerpts.
- Interactive interface built with Streamlit.

## Tech Stack
- Python
- Streamlit
- LangChain
- FAISS
- Hugging Face Transformers
- Sentence Transformers


##  How It Works

1. Upload documents.
2. Extract text and split it into chunks.
3. Generate embeddings and store them in FAISS.
4. Retrieve relevant chunks for the user's question.
5. Generate an answer using the retrieved context and FLAN-T5.

##  Future Improvements
- Add page-level source citations.
- Implement hybrid search and reranking.
- Save vector indexes for future sessions.
- Deploy the application online.

