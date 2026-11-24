\# Advanced RAG (Retrieval-Augmented Generation)



\## Overview

This project implements a Retrieval-Augmented Generation (RAG) application that allows users to retrieve relevant information from documents and generate context-aware answers using an LLM.



\## Features

\- PDF document ingestion

\- Text extraction and chunking

\- Embedding generation

\- Vector database for document retrieval

\- Context-aware question answering

\- LLM integration

\- Python-based application



\## Tech Stack

\- Python

\- LangChain

\- FAISS

\- Hugging Face

\- Groq

\- Streamlit (if used in the application)



\## Project Structure

```text

advance\_rag/

├── src/

│   ├── chains.py

│   ├── config.py

│   ├── prompts.py

│   └── rag\_pipeline.py

├── api.py

├── app.py

├── ingest.py

├── main.py

├── requirements.txt

├── .env.example

└── .gitignore

```



\## Installation



Clone the repository:



```bash

git clone https://github.com/AnumalaSumanth/advance\_rag.git

cd advance\_rag

```



Install dependencies:



```bash

pip install -r requirements.txt

```



\## Environment Variables



Create a `.env` file in the project root and add your required API keys:



```env

GROQ\_API\_KEY=your\_groq\_api\_key

```



Never commit your actual API keys.



\## Usage



Run the application using the appropriate entry point:



```bash

python app.py

```



\## Security

API keys, environment files, private documents, virtual environments, and generated vector stores are excluded from version control.



\## Author

Sumanth



