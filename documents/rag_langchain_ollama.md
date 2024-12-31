# RAG and Ollama

## RAG

- RAG is Retrieval-Augmented Generation, a framework that combines the strengths of retrieval-based models and generative models to improve the quality, relevance, and factual accuracy of generated content.
- Retrieval Step: fetches relevant documents or context form a knowledge base, database, or other external source based on a query or input.
- Generation Step: uses the retrieved context to generate output that is more accurate, detailed, and contextually relevant.

## LangChain

- LangChain is a framework for building applications that integrate with LLMs in a modular and flexible way.
- Features:
  - Integration with external data
  - Chain building
  - Retrieval-Augmented Generation
  - Memory Management
  - Tool and Plugin Integration
  - Customizability
  - Support for Multiple LLMs
- Components
  - Chains
  - Agents
  - Prompts
  - Memory
  - Tools/Integrations

## Ollama

- Ollama is an AI platform designed for integration with LLM on local devices or in controlled environments.
- Features:
  - Local execution
  - Privacy and security
  - Customizable models
  - Efficient resource usage
  - Integration capabilities
  - Offline functionality

## RAG Tutorial

### Steps

1. Original Data Source
2. Text Splitter
3. Chunks of Text
4. Embeddings
5. Store in a Vector Database
6. Input query
7. Query Embedding
8. Fetch the most relevant entries form the database
9. Put the entries into the prompt
10. Get final response from a Generative AI

### Details
- Dependencies: lanchain, chromadb, pypdf, pytest