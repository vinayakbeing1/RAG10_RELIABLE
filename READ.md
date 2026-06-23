# RAG Hallucination Detection and Document Grounding

This project demonstrates a Retrieval-Augmented Generation (RAG) workflow using LangChain and OpenAI. The pipeline retrieves relevant documents, generates answers, grades document relevance, detects hallucinations, and identifies supporting evidence.

## Features

* Document Retrieval using Vector Database
* OpenAI Embeddings (`text-embedding-3-small`)
* Answer Generation using GPT models
* Relevance Grading
* Hallucination Detection
* Document Lookup and Evidence Extraction
* Structured Outputs with Pydantic

## Tech Stack

* Python
* LangChain
* OpenAI
* ChromaDB
* Pydantic

## Installation

```bash
git clone <repository-url>
cd <repository-name>

pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
```

## Usage

Run the notebook or Python script:

```bash
jupyter notebook
```

or

```bash
python app.py
```

## Project Structure

```text
├── data/
├── notebooks/
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## License

MIT License
