📊 Fiscal-Year-Analysis RAG Chatbot

AI-powered chatbot that analyzes financial PDFs (10-K filings) and provides insights using a Retrieval-Augmented Generation (RAG) pipeline.

✨ Features

Extracts and cleans financial data from multiple companies

Performs basic financial analysis: growth rates, profitability, ratios

Uses RAG pipeline with Chroma vectorstore + Mistral LLM

Interactive chatbot interface via Gradio

Summarizes and answers questions with context from the PDFs

🚀 Quick Start

Open Notebook in Colab

Make sure PDFs are in RAG_Files/ folder.

Add Your Mistral API Key

Create a Mistral API key

Add it to Colab Secrets or input via getpass in the notebook

Install Dependencies

!pip install -r requirements.txt


Run All Cells

Load PDFs → Chunk → Embed → Build Vectorstore → Launch Gradio UI

Ask Questions

Example: “Summarize Apple’s financial performance in 2024.”

📁 Folder Structure
Fiscal-Year-Analysis/
├── RAG_Files/           # PDF documents to analyze
├── chroma_rag_db/       # persisted vectorstore
├── notebook.ipynb       # Colab notebook
├── requirements.txt     # Python dependencies
└── README.md            # project overview

🛠 Tech Stack

Python 3.12

LangChain (RAG pipeline)

Chroma (vectorstore)

HuggingFace Sentence Transformers (embeddings)

Mistral LLM (question answering)

Gradio (chatbot UI)

📌 Notes

Ensure PDFs are placed in the RAG_Files/ folder before running the notebook.

Persisted vectorstore (chroma_rag_db/) speeds up future runs.

Users must provide their own Mistral API key; keys are not included in the repo.
