# RAG Tutorial Collection

Welcome to the comprehensive RAG (Retrieval-Augmented Generation) tutorial collection! This website contains detailed Jupyter notebooks covering various aspects of building RAG systems using LangChain, LangGraph, and related technologies.

## 📚 Content Overview

This collection is organized by folders, with each folder containing related tutorials on specific topics:

- **0-DataIngestionParsing**: Data ingestion and parsing techniques (PDF, DOC, CSV, JSON, databases)
- **1-VectorEmbeddingAndDatabases**: Vector embeddings and database integration
- **2-Vector Store**: Vector database implementations (ChromaDB, FAISS, Pinecone, DataStax)
- **3-AdvancedChunkingAndPreprocessing**: Advanced chunking strategies including semantic chunking
- **4-HybridSearchStrategies**: Dense/sparse retrieval, reranking, and MMR
- **5-QueryEnhancement**: Query expansion, decomposition, and HyDE techniques
- **6-MultiModalRag**: Multi-modal RAG implementations with OpenAI
- **7-langgraph Basics**: LangGraph fundamentals (graphs, chatbots, agents, chains)
- **8-langgraph advance**: Advanced LangGraph features (streaming)
- **10- Workflows**: Workflow patterns (prompting, parallelization, routing, orchestrator-worker)
- **11-HumanintheLoop**: Human-in-the-loop implementations
- **12-RAGS**: Advanced RAG techniques (Agentic RAG, Corrective RAG, CoT RAG, Adaptive RAG)
- **13-AgenticRag**: Comprehensive agentic RAG implementations (ReAct, query planning, multi-agent)
- **14-RAG EVALUATION**: RAG system evaluation methodologies
- **15-Q&A WITH GRAPHDB**: Graph database integration for Q&A systems
- **pydantic**: Pydantic introduction and usage

## 🌐 Website

This repository is automatically built into a website using [Jupyter Book](https://jupyterbook.org/) and deployed via GitHub Pages.

**Website URL**: [https://jagadeshchilla.github.io/RAG/](https://jagadeshchilla.github.io/RAG/)

## 🚀 Usage

All notebooks are organized by folder in the navigation. Each notebook includes:
- Code examples with outputs
- Explanatory markdown cells
- Images and diagrams where applicable

The notebooks are displayed as-is without re-execution, preserving all original outputs and visualizations.

## 📖 Navigation

The website navigation mirrors the folder structure, making it easy to find tutorials on specific topics. Each folder is organized as a separate section with individual notebooks listed within.

## 🛠️ Local Development

To build the website locally:

```bash
# Activate virtual environment
.venv/Scripts/activate

# Install dependencies
pip install -r requirements.txt

# Build the website
jupyter-book build .

# View the website
# Open _build/html/index.html in your browser
```

## 📝 Structure

- Each folder contains related Jupyter notebooks
- Images are stored in `images/` subdirectories within folders
- Configuration files: `_config.yml` and `_toc.yml`
- Build output: `_build/html/`

## 🔄 Auto-Deployment

The website is automatically rebuilt and deployed on every push to the `main` branch via GitHub Actions.
