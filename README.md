# AI Code Explorer: Chat with Your Codebase using RAG

An intelligent system for understanding and exploring codebases through natural language conversations, powered by Retrieval-Augmented Generation (RAG).

## Project Description

This project implements a smart coding assistant that allows developers to interact with and understand codebases through natural language queries. By leveraging RAG technology, the system provides contextually relevant answers based on the actual code content.

## Key Features

- Codebase embedding and vectorization using Pinecone database
- Intelligent code retrieval based on semantic similarity
- Natural language query processing using LLMs
- Slack integration via /ai-coding-agent-help command

## How It Works

1. Codebase content is embedded and stored in Pinecone vector database
2. User submits queries through Slack or command line interface
3. System retrieves relevant code snippets based on query similarity
4. LLM generates human-readable responses using retrieved context

## Use Cases

- Understanding complex codebases quickly
- Getting answers about code functionality and architecture
- Identifying areas for improvement and optimization
- Assisting with code reviews and documentation
