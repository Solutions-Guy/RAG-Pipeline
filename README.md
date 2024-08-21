# RAG-Pipeline


This project implements a Retrieval Augmented Generation (RAG) pipeline using Ollama for language model inference and Weaviate as a vector database. The setup allows for efficient data retrieval and processing, leveraging the capabilities of both tools.

## Prerequisites

Before you begin, ensure you have the following applications and libraries installed:

### Ollama
- **Download Ollama**: [Ollama Download Page](https://ollama.com/download)
- **Pull Models**:
  - Use the command `ollama pull {model}` to download the desired language model.
  - Use the command `ollama pull {embed model}` to download the embedding model.

### Weaviate
- **Quickstart Guide**: [Weaviate Quickstart](https://weaviate.io/developers/weaviate/quickstart)
- **Install Weaviate Client**:
  ```bash
  pip install -U weaviate-client

