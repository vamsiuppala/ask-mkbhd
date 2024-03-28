# Building a RAG application from scratch

This is a step-by-step guide to building a simple RAG (Retrieval-Augmented Generation) application using OpenAI's API. The application will allow you to ask questions about any document present in the autofocus/ folder

## Setup

Create a virtual environment and install the required packages:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

## Pinecone

There is reference code to utilizing Pinecone, but most of the example relies on using local vector stores