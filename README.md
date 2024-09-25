# Local RAG (Retrieval Augmented Generation) Demo

## Implementing a RAG system using LLMs running locally, with LangChain 🦜🔗 and Ollama 🦙.
---

The purpose of this demo is to explore the implementation of a RAG system running locally.

The general pipeline is as follows:

- Load the LLM and its embedding model
- Define a prompt template for the LLM
- Load and parse the PDF document
- Split the document text into smaller chunks
- Create the vector embeddings for each text chunk
- Store the embeddings in a vector store (vector database)
- Query the model 

We will test the performance of 3 top LLMs: **Llama 3.1**, **Gemma 2** and **GPT-4o**

