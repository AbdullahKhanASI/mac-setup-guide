# Agentic AI Development Environment Setup

Your laptop is now fully configured for agentic AI development! Here's what has been installed:

## Core Development Tools
- **Homebrew** (4.5.13) - Package manager for macOS
- **Python** (3.13.5) via pyenv - Latest Python version
- **Node.js** (v22.18.0) via nvm - JavaScript runtime
- **Azure CLI** (2.76.0) - Azure cloud development tools

## AI/ML Infrastructure
- **Ollama** (0.11.0) - Local LLM inference server
- **Virtual Environment**: `~/agentic-ai-env` - Isolated Python environment

## Agentic AI Libraries Installed
- **LangChain & LangChain Community** - LLM application framework
- **LangGraph** - Multi-agent workflows and state management
- **LangSmith** - LLM application observability
- **CrewAI** - Multi-agent collaboration framework
- **AutoGen (AG2)** - Microsoft's multi-agent conversation framework

## Web Development & UI Frameworks
- **Streamlit** - Data app framework
- **Gradio** - ML model web interfaces
- **FastAPI** - Modern web API framework
- **Jupyter** - Interactive development environment

## ML/AI Libraries
- **PyTorch** (2.7.1) - Deep learning framework
- **Transformers** - Hugging Face transformer models
- **ChromaDB** - Vector database for embeddings
- **OpenAI** - OpenAI API client

## Getting Started

### 1. Activate your agentic AI environment:
```bash
source ~/agentic-ai-env/bin/activate
```

### 2. Start Ollama server (for local LLMs):
```bash
ollama serve
```

### 3. Install local models (optional):
```bash
ollama pull llama3.2:3b
ollama pull qwen2.5-coder:7b
```

### 4. Create your first agentic AI project:
```bash
mkdir ~/my-agentic-project
cd ~/my-agentic-project
```

### 5. Test installations:
```python
# Test LangChain
from langchain.llms import OpenAI
from langchain.agents import initialize_agent

# Test CrewAI
from crewai import Agent, Task, Crew

# Test AutoGen
import autogen

# Test Streamlit
import streamlit as st

# Test local models with Ollama
from langchain_community.llms import Ollama
```

## Environment Variables to Set
Consider adding these to your `~/.zshrc` or `~/.bashrc`:

```bash
# Activate agentic AI environment by default
# source ~/agentic-ai-env/bin/activate

# API Keys (add your actual keys)
export OPENAI_API_KEY="your-openai-key"
export ANTHROPIC_API_KEY="your-anthropic-key"
export LANGCHAIN_API_KEY="your-langsmith-key"
export LANGCHAIN_TRACING_V2=true
export LANGCHAIN_PROJECT="agentic-ai-dev"
```

## Useful Commands

- **Start Jupyter**: `jupyter lab` or `jupyter notebook`
- **Start Streamlit app**: `streamlit run app.py`
- **Start Gradio interface**: `python gradio_app.py`
- **List Ollama models**: `ollama list`
- **Azure CLI login**: `az login`

## Next Steps
1. Set up your API keys for OpenAI, Anthropic, etc.
2. Explore the example projects in each framework
3. Start building your first multi-agent system!

Your agentic AI development environment is ready! 🚀