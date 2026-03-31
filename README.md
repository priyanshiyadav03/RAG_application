overview
This project implements a PDF-based Retrieval-Augmented Generation (RAG) system that allows users to extract, process, and query information from PDF documents using Large Language Models (LLMs).

The system converts PDF content into structured chunks, stores them in a vector database, and retrieves relevant context to generate accurate, context-aware responses.
            
            Architecture
PDF → Text Extraction → Chunking → Embeddings → Vector DB
                                      ↓
User Query → Embedding → Similarity Search → Context
                                      ↓
                             LLM → Final Answer


                             Key Features
 Upload and process PDF documents (multi-page support)
 Intelligent text chunking (page-wise / heading-wise)
 Semantic search using embeddings
 LLM-based answer generation
 Handles noisy OCR-extracted text
 Fast retrieval using vector databases
 Optional image extraction from PDFs
