# RAG Tutorial Collection

<div align="center">

**Comprehensive tutorials for building Retrieval-Augmented Generation (RAG) systems**

[![Website](https://img.shields.io/badge/Website-Live-brightgreen)](https://jagadeshchilla.github.io/RAG/)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue)](https://pages.github.com/)
[![Jupyter Book](https://img.shields.io/badge/Built%20with-Jupyter%20Book-orange)](https://jupyterbook.org/)

</div>

---

## 📑 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Content Structure](#content-structure)
- [Getting Started](#getting-started)
- [Website](#website)
- [Project Structure](#project-structure)
- [Development](#development)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

This repository contains a comprehensive collection of Jupyter notebooks demonstrating advanced techniques for building production-ready Retrieval-Augmented Generation (RAG) systems. The tutorials cover everything from data ingestion and vector database management to advanced agentic RAG implementations and evaluation methodologies.

The collection is designed as a learning resource for developers, data scientists, and AI engineers working with LangChain, LangGraph, and modern RAG architectures.

### Key Highlights

- **50+ Practical Notebooks** covering all aspects of RAG development
- **Production-Ready Examples** with real-world use cases
- **Step-by-Step Tutorials** with detailed explanations
- **Interactive Learning** through Jupyter notebooks with preserved outputs
- **Modern Tech Stack** using LangChain, LangGraph, and leading vector databases

---

## ✨ Features

- 📚 **Comprehensive Coverage**: From basic data ingestion to advanced agentic RAG systems
- 🔄 **Interactive Notebooks**: All code examples with preserved outputs and visualizations
- 🖼️ **Rich Media**: Includes diagrams, images, and visual explanations
- 📖 **Organized Structure**: Content organized by topics and difficulty levels
- 🌐 **Web-Ready**: Automatically compiled into a beautiful website using Jupyter Book
- 🚀 **CI/CD Integration**: Automatic deployment via GitHub Actions
- 🔍 **Search Functionality**: Built-in search across all notebooks
- 📱 **Responsive Design**: Mobile-friendly website interface

---

## 🛠️ Technologies

### Core Frameworks
- **[LangChain](https://www.langchain.com/)** - Framework for developing LLM applications
- **[LangGraph](https://langchain-ai.github.io/langgraph/)** - Build stateful, multi-actor applications with LLMs
- **[LangChain Community](https://python.langchain.com/docs/community/)** - Community integrations

### Vector Databases & Embeddings
- **ChromaDB** - Open-source embedding database
- **FAISS** - Facebook AI Similarity Search
- **Pinecone** - Managed vector database
- **DataStax** - Enterprise vector database solutions
- **Sentence Transformers** - State-of-the-art sentence embeddings
- **OpenAI Embeddings** - Text embedding models

### Data Processing
- **PyPDF** / **PyMuPDF** - PDF processing
- **python-docx** / **docx2txt** - Word document handling
- **Pandas** / **OpenPyXL** - Data manipulation (CSV, Excel)
- **Unstructured** - Document parsing and preprocessing

### Additional Tools
- **Jupyter Book** - Documentation and website generation
- **Matplotlib** - Data visualization
- **TikToken** - Token counting and text processing
- **Rank BM25** - Sparse retrieval algorithms

---

## 📁 Content Structure

The tutorials are organized into the following modules:

| Module | Topic | Description |
|--------|-------|-------------|
| **0-DataIngestionParsing** | Data Ingestion | PDF, DOC, CSV, JSON, and database parsing techniques |
| **1-VectorEmbeddingAndDatabases** | Embeddings | Vector embedding generation and database integration |
| **2-Vector Store** | Vector Databases | ChromaDB, FAISS, Pinecone, and DataStax implementations |
| **3-AdvancedChunkingAndPreprocessing** | Chunking Strategies | Semantic chunking and advanced preprocessing techniques |
| **4-HybridSearchStrategies** | Search Methods | Dense/sparse retrieval, reranking, and MMR algorithms |
| **5-QueryEnhancement** | Query Processing | Query expansion, decomposition, and HyDE techniques |
| **6-MultiModalRag** | Multi-Modal RAG | Image and text processing with OpenAI |
| **7-langgraph Basics** | LangGraph Fundamentals | Graphs, chatbots, agents, and chain implementations |
| **8-langgraph advance** | Advanced LangGraph | Streaming and advanced workflow patterns |
| **10- Workflows** | Workflow Patterns | Prompting, parallelization, routing, orchestrator-worker |
| **11-HumanintheLoop** | Human Integration | Human-in-the-loop implementations and feedback |
| **12-RAGS** | Advanced RAG | Agentic, Corrective, CoT, and Adaptive RAG patterns |
| **13-AgenticRag** | Agentic Systems | ReAct, query planning, multi-agent, and memory systems |
| **14-RAG EVALUATION** | Evaluation | Metrics and methodologies for RAG system evaluation |
| **15-Q&A WITH GRAPHDB** | Graph Databases | Knowledge graph integration for Q&A systems |
| **pydantic** | Data Validation | Pydantic models for data validation |

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.11+** (recommended)
- **Git** for cloning the repository
- **Virtual Environment** (venv or conda)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jagadeshchilla/RAG.git
   cd RAG
   ```

2. **Create and activate a virtual environment**
   ```bash
   # Windows
   python -m venv .venv
   .venv\Scripts\activate
   
   # Linux/Mac
   python -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables** (if needed)
   ```bash
   # Create a .env file with your API keys
   cp .env.example .env  # If available
   # Add your OPENAI_API_KEY, GROQ_API_KEY, etc.
   ```

---

## 🌐 Website

### Live Website

🔗 **Website URL**: [https://jagadeshchilla.github.io/RAG/](https://jagadeshchilla.github.io/RAG/)

The website provides:
- 📖 Interactive notebook viewer with preserved outputs
- 🔍 Full-text search across all content
- 📱 Responsive design for all devices
- 🎨 Clean, professional interface
- 🔗 Easy navigation between related topics

### Website Features

- **No Code Execution**: Notebooks are displayed as-is, preserving all outputs and visualizations
- **Rich Media Support**: Images, diagrams, and visualizations are automatically included
- **Table of Contents**: Easy navigation through all modules and notebooks
- **Search**: Built-in search functionality to find specific topics
- **Mobile Responsive**: Optimized for viewing on all device sizes

---

## 📂 Project Structure

```
RAG/
├── 0-DataIngestionParsing/        # Data ingestion tutorials
│   ├── *.ipynb                     # Jupyter notebooks
│   ├── data/                       # Sample data files
│   └── *.svg                       # Diagrams and images
├── 1-VectorEmbeddingAndDatabases/  # Embedding tutorials
├── 2-Vector Store/                 # Vector database tutorials
├── ...                             # Other modules
├── _config.yml                     # Jupyter Book configuration
├── _toc.yml                        # Table of contents structure
├── README.md                       # This file
├── requirements.txt                # Python dependencies
└── .github/
    └── workflows/
        └── deploy.yml              # GitHub Actions deployment
```

### Key Files

- **`_config.yml`**: Jupyter Book configuration (theme, settings, etc.)
- **`_toc.yml`**: Website navigation structure organized by folders
- **`requirements.txt`**: All Python package dependencies
- **`.github/workflows/deploy.yml`**: Automated deployment pipeline

---

## 💻 Development

### Running Notebooks Locally

1. **Start Jupyter Notebook or JupyterLab**
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

2. **Navigate to any folder** and open the `.ipynb` files

3. **Run cells** interactively to experiment with the code

### Building the Website Locally

```bash
# Activate virtual environment
.venv\Scripts\activate  # Windows
# or
source .venv/bin/activate  # Linux/Mac

# Install jupyter-book if not already installed
pip install jupyter-book

# Build the website
jupyter-book build .

# The website will be generated in _build/html/
# Open _build/html/index.html in your browser
```

### Rebuilding After Changes

```bash
# Clean previous build (optional)
jupyter-book clean .

# Rebuild
jupyter-book build .
```

---

## 🚢 Deployment

### Automated Deployment

The website is automatically deployed via **GitHub Actions** on every push to the `main` branch.

**Deployment Pipeline:**
1. Push to `main` branch triggers GitHub Actions
2. Workflow installs dependencies and builds Jupyter Book
3. Generated HTML is deployed to GitHub Pages
4. Website updates within a few minutes

**Configuration:**
- **Source**: GitHub Actions (`.github/workflows/deploy.yml`)
- **Build Tool**: Jupyter Book
- **Hosting**: GitHub Pages
- **URL**: `https://jagadeshchilla.github.io/RAG/`

### Manual Deployment

If needed, you can deploy manually:

```bash
# Build the website
jupyter-book build .

# Deploy using ghp-import
ghp-import -n -p -f _build/html
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Make your changes** and test thoroughly
4. **Commit your changes** (`git commit -m 'Add amazing feature'`)
5. **Push to the branch** (`git push origin feature/amazing-feature`)
6. **Open a Pull Request**

### Guidelines

- Follow existing notebook structure and formatting
- Add clear markdown explanations
- Include example outputs where relevant
- Update `_toc.yml` if adding new modules
- Test locally before submitting

---

## 📄 License

This project is open source and available for educational and research purposes. Please respect individual notebook licenses and attributions where applicable.

---

## 🙏 Acknowledgments

- [LangChain](https://www.langchain.com/) for the excellent framework
- [LangGraph](https://langchain-ai.github.io/langgraph/) for stateful LLM applications
- [Jupyter Book](https://jupyterbook.org/) for website generation
- All open-source contributors and the AI community

---

## 📞 Contact & Support

- **Repository**: [https://github.com/jagadeshchilla/RAG](https://github.com/jagadeshchilla/RAG)
- **Website**: [https://jagadeshchilla.github.io/RAG/](https://jagadeshchilla.github.io/RAG/)
- **Issues**: Use GitHub Issues for bug reports and feature requests

---

<div align="center">

**Built with ❤️ for the AI/ML community**

⭐ Star this repo if you find it helpful!

</div>
