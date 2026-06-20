# SOP Chatbot

An AI-powered SOP (Standard Operating Procedure) chatbot built using n8n and Retrieval-Augmented Generation (RAG).

## Features

- Upload PDF or CSV files
- AI-powered question answering
- Retrieval-Augmented Generation (RAG)
- Vector Store for document search
- OpenRouter Llama 3.1
- OpenAI Embeddings
- n8n AI Agent workflow

## Technologies Used

- n8n
- OpenRouter
- OpenAI Embeddings
- Vector Store
- RAG

## Workflow

1. Upload SOP documents.
2. Documents are converted into embeddings.
3. Stored in Vector Store.
4. AI Agent retrieves relevant information.
5. Answers user questions using the uploaded SOP.

## Setup

1. Import `workflow.json` into n8n.
2. Configure your own OpenRouter credentials.
3. Configure your own OpenAI credentials.
4. Execute the workflow.
