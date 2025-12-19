## LangChain

This repo is related to langchain framework 

## Getting Started

* Create a conda virtual environment

```

conda create -n langchain_env python=3.10

conda activate langchain_env

pip3 install -r requirements.txt

```

* Create a .env file and add the API keys

```
GROQ_API_KEY="gsk_**********************************************"

OPENAI_API_KEY="sk-********************************************"

GEMINI_API_KEY="AI********************************************"

MISTRAL_API_KEY="yF********************************************"

LANGSMITH_API_KEY="ls********************************************"

```

## LangChain Components:

1. [Document Loaders](01_document_loaders)

2. [Text Splitters](02_text_splitters)

3. [Models](03_models)

4. [Vector Stores](04_vector_stores)
