****RAG QnA Chatbot – Constitution of Pakistan****
A Retrieval-Augmented Generation (RAG) based Question Answering chatbot that allows users to ask questions about the Constitution of Pakistan.
The chatbot retrieves relevant information from a PDF dataset and generates accurate answers using a Large Language Model (LLM).
This project demonstrates how RAG architecture can be used to build domain-specific AI assistants.

****Project Overview****

This chatbot is designed to:
Load a PDF dataset containing the Constitution of Pakistan
Convert the text into vector embeddings
Store embeddings in a vector database
Retrieve the most relevant document chunks when a user asks a question
Generate answers using an LLM
The system ensures that responses are grounded in the actual document instead of hallucinating answers.

****Architecture
The project follows the RAG (Retrieval-Augmented Generation) pipeline:**
**
**Document Loading**
Load the Constitution of Pakistan PDF

**Text Chunking**
Split the document into smaller chunks

**Embedding Generation**
Convert chunks into vector embeddings

**Vector Storage**
Store embeddings for similarity search

**User Query**
User asks a question

**Retrieval**
Retrieve the most relevant chunks

**LLM Response Generation**
Generate the final answer using retrieved context

**Dataset**
The chatbot uses:

****Constitution of Pakistan (PDF)****
File included in repository:
Constitution of pakistan-unlocked.pdf

**Project Structure**
RAG-QnA-Chatbot---PDF
│
├── Constitution of pakistan-unlocked.pdf   # Dataset
├── Pdf.py                                  # Main chatbot logic
├── requirements.txt                        # Required libraries
├── README.md                               # Project documentation
├── LICENSE
└── .gitignore

**Technologies Used**

Python
Retrieval Augmented Generation (RAG)
Large Language Models (LLMs)
LangChain
Vector Embeddings
PDF Document Processing
