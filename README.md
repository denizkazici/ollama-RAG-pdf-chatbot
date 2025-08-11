#Ollama + ChromaDB RAG Chatbot
Project Purpose
This project is a Retrieval-Augmented Generation (RAG) system capable of extracting information from docx documents and providing relevant answers to user queries based on the documents.
It uses the Ollama LLM and the ChromaDB vector database.

Features
Upload and extract text from word files
Generate embeddings (nomic-embed-text)
Store and query data in ChromaDB
Context-based answer generation with Ollama LLM
Console-based question-answer interface

Technologies Used
Python
LangChain
ChromaDB
Ollama 


Workflow
1- Extract text from the word file
2- Split the text into chunks
3- Generate embeddings
4- Store vectors in ChromaDB
5- Generate embeddings for the query and retrieve the most relevant chunks
6- Produce an answer using Ollama LLM
