LLaMA Text Summarizer: 
A lightweight AI-powered application that leverages the LLaMA language model (via Ollama) to generate concise summaries from longer text passages.

This project includes:
 - A FastAPI backend for handling summarization requests
 - A Streamlit frontend for a clean and interactive user interface
 - A locally running LLaMA model via Ollama

Setup Instructions:
  - Clone the repository: 
       git clone <your-repo-url>, 
       cd llama-text-summarizer
  - Install dependencies: 
       pip install -r requirements.txt
  - Start the backend (FastAPI): 
       uvicorn backend.main:app --reload
  - Launch the frontend (Streamlit): 
       streamlit run frontend/app.py

