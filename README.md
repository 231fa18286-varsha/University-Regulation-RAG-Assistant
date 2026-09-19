# University Regulation RAG Assistant

A Retrieval-Augmented Generation (RAG) based question-answering system
for university regulations and academic rules.

## Features

- PDF document processing
- Text extraction and preprocessing
- Text chunking
- Sentence Transformer embeddings
- FAISS vector similarity search
- Similarity threshold for unrelated questions
- Grounded answer generation using Qwen
- Source document and page display
- "Information not found" response for unavailable information

## Technologies Used

- Python
- Google Colab
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- Qwen2.5-0.5B-Instruct
- PyPDF

## RAG Pipeline

PDF Documents
→ Text Extraction
→ Text Chunking
→ Embeddings
→ FAISS Vector Database
→ Similarity Search
→ Retrieved Context
→ Qwen LLM
→ Final Answer

## Example Questions

- What is the attendance requirement?
- What happens if there is an attendance shortage?
- What is the distribution of formative and summative assessment marks?
- What are the examination rules?

The system also tests questions outside the uploaded documents and
returns an information-not-found response when appropriate.
