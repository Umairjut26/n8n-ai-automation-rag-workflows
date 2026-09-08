# n8n AI Automation & Conversational RAG Workflows

AI-powered automation workflows built with n8n for document ingestion, vector storage, and conversational RAG.

## Workflows

### 1. Document Ingestion Pipeline

Google Drive Trigger → Download File → Data Loader → Recursive Character Text Splitter → Google Gemini Embeddings → Pinecone Vector Store

This workflow automates document ingestion, processes the content, generates embeddings using Google Gemini, and stores the data in Pinecone Vector Store for retrieval.

### 2. Conversational RAG Agent

Chat Message → AI Agent → Google Gemini Chat Model + Simple Memory + Pinecone Vector Store

This workflow uses an AI Agent with Google Gemini, memory, and Pinecone Vector Store to provide context-aware responses based on retrieved knowledge.

## Technologies

- n8n
- Google Gemini
- Pinecone Vector Store
- Retrieval-Augmented Generation (RAG)
- AI Agents
- Google Drive
- Vector Embeddings
- Document Processing

## Workflow Screenshot

![n8n AI Automation & RAG Workflows](n8n-rag-workflows.png)
