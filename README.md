# Chat with Your PDFs

This Streamlit application allows users to upload multiple PDF files and ask questions based on the content of the uploaded documents. The application uses Google Gemini API for generative AI to provide accurate answers to user queries based on the analyzed PDFs.

## Features

- Upload multiple PDF files.
- Extract text from uploaded PDFs.
- Analyze the text and create embeddings using Google Generative AI Embeddings.
- Store the FAISS index in memory for the duration of the session.
- Answer user questions based on the content of the PDFs.
- Respond with "The relevant information is not found in the uploaded documents." if the question is out of context.
