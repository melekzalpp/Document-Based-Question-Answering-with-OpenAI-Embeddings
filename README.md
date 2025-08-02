# Document-Based Question Answering System (RAG) with LangChain & AstraDB

This project implements a PDF and text document question-answering system based on Retrieval-Augmented Generation (RAG) using OpenAI embeddings, LangChain, and AstraDB’s vector database capabilities. It enables semantic search over uploaded documents to provide accurate answers to user queries.

---

## 🚀 Features

- Process `.pdf` and `.txt` documents by extracting and chunking text
- Generate semantic embeddings using OpenAI’s `text-embedding-ada-002`
- Store and query embeddings in AstraDB, a serverless vector-capable NoSQL DB built on Cassandra
- Retrieve semantically relevant text chunks using similarity search
- Generate answers using GPT language models based on retrieved context

---

## 🧰 Technologies & Tools

- **Python** — Core programming language
- **LangChain** — Document loading, splitting, and vector store integration
- **OpenAI API** — Embeddings and GPT response generation
- **AstraDB / Apache Cassandra** — Serverless vector database for embeddings
- **scikit-learn** — Cosine similarity for semantic search

