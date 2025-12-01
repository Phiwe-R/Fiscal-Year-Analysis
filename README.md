# 📊 Fiscal-Year-Analysis RAG Chatbot

AI-powered chatbot that analyzes financial PDFs (10-K filings) and provides insights using a **Retrieval-Augmented Generation (RAG) pipeline**.

---

## ✨ Features

- Extracts and cleans financial data from multiple companies  
- Performs basic financial analysis: growth rates, profitability, ratios  
- Uses RAG pipeline with **Chroma vectorstore** + **Mistral LLM**  
- Interactive chatbot interface via **Gradio**  
- Summarizes and answers questions with context from the PDFs  

---

## 🚀 Quick Start

1. **Open Notebook in Colab**  
   - Make sure PDFs are in the `RAG_Files/` folder.
2. **Use Your Own Data Path**
   - If you have the downloaded PDF file stored locally (not on Google Drive), you just need to make sure your data path points to the folder where the PDF is.
2. **Add Your Mistral API Key**  
   - Create a [Mistral API key](https://www.mistral.ai/)  
   - Add it to **Colab Secrets** and give it a secret name and allow notebook access using the toggle button.

3. **Install Dependencies**  

```bash
!pip install -r requirements.txt
