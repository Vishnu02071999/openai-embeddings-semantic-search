# openai-embeddings-semantic-search
This project demonstrates how to build a simple semantic search system using OpenAI's text-embedding-3-large model and cosine similarity. Instead of matching exact keywords, semantic search understands the meaning and context of the query to retrieve the most relevant document.

# Features
Generate vector embeddings using OpenAI Embeddings.

Convert documents and user queries into numerical representations.

Calculate similarity scores using cosine similarity.

Retrieve the most relevant document based on semantic meaning.

Lightweight and beginner-friendly implementation.

# Technologies Used
LangChain OpenAI
OpenAI Embeddings (text-embedding-3-large)
Scikit-learn
NumPy
Python
 # How It Works
Load environment variables containing the OpenAI API key.

Create embeddings for a collection of documents.

Convert the user's query into an embedding.

Compute cosine similarity between the query and document embeddings.

Identify and return the document with the highest similarity score.

# Example

Query: tell me about bumrah

Result:
The system retrieves the document related to Jasprit Bumrah because its semantic meaning is closest to the user's query.

# Learning Outcome

This project provides a practical introduction to vector embeddings, semantic search, and the foundation of Retrieval-Augmented Generation (RAG) systems used in modern AI applications.
