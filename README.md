# assignment_project-.ipynb
%%writefile rag_pdf_project/README.md
# PDF Question Answering using RAG (Fully Free)

This project implements a Retrieval-Augmented Generation (RAG) system
to answer questions from PDF documents using open-source models.

## Tech Stack
- LangChain
- ChromaDB
- HuggingFace (FLAN-T5)
- Sentence Transformers
- PyPDF

## Workflow
1. Load PDF
2. Split text into chunks
3. Create vector embeddings
4. Store in ChromaDB
5. Retrieve relevant chunks
6. Generate answers using LLM

## How to Run
```bash
pip install -r requirements.txt
