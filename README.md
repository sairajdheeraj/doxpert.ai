# Doxpert.ai

Doxpert is a Retrieval-Augmented Generation (RAG) application that processes documents (PDF, Word, PPT) and uses embeddings to answer queries.

## Features

- Supports Multiple Docs
- Works with multiple document types (PDF, Word, PPT)
- Runs locally, uses relatively less resources.
- Accurate Answers in real time with the help of Gemini AI.

## Prerequisites

- Python 3.8
- PIP
- Google API Key

## To run the application, run the following commands

- Create a virtual environment
```bash
python -m venv doc_ai
```

- Activate virtual environment
```bash
doc_ai\Scripts\activate
```

- Install dependencies using:

```bash
pip install -r requirements.txt

```

- Configure you Google API Key

```bash
GOOGLE_API_KEY=your_google_api
```

- Run the application using 

```bash
streamlit run doc_ai.py
```
