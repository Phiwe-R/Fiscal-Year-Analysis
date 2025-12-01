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
1. **Save documents on your Google Drive and Open Notebook in Colab**
   - Make sure the DATA_PATH variable in the notebook points to the RAG_files folder from Google Drive  path where **analysis doc** PDF is located.
   - copy the path of the folder and assign it to DATA_PATH
   - Follow these intructions , otherwise the pyPDFDirectory function  from the notebook will not load the pdf because it  wants a real directory folder not a temporary session path
3. **Add Your Mistral API Key**  
   - Create a [Mistral API key](https://www.mistral.ai/)  
   - Add it to **Colab Secrets** and give it a secret name and allow notebook access using the toggle button.

4. **Install Dependencies**  

```bash
!pip install -r requirements.txt
