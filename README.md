# LLM RAG and Agents Project

This repository is a collection of notebooks and resources for learning and experimenting with various concepts related to Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and Autonomous Agents.

The project covers a wide range of topics, including:
*   **Data Ingestion:** Parsing various file formats like PDF, CSV, Excel, JSON, and databases.
*   **Embeddings and Vector Databases:** Creating embeddings and using vector stores like ChromaDB, FAISS, Datastax, and Pinecone.
*   **Advanced Chunking and Retrieval:** Techniques like Semantic Chunking, Dense-passage retrieval, and re-ranking.
*   **Query Expansion and Transformation:** Methods like query decomposition and HyDE.
*   **Agentic RAG:** Building agentic systems with concepts like ReAct, Chain of Thought, and self-reflection.
*   **Multi-Agent Systems:** Exploring corrective RAG and cache-augmented RAG.

This project uses `uv` for managing virtual enviro nments and packages.

## Setup

1.  **Create a virtual environment:**
    ```bash
    uv venv
    ```

2.  **Activate the virtual environment:**
    - On macOS and Linux:
      ```bash
      source .venv/bin/activate
      ```
    - On Windows:
      ```bash
      .venv\Scripts\activate
      ```

3.  **Install the required packages:**

    You can install the packages using either of the following commands:

    - Using `uv pip`:
      ```bash
      uv pip install -r requirements.txt
      ```

    - Using `uv` directly:
      ```bash
      uv install -r requirements.txt
      ```
