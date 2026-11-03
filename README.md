AI Document QA Assistant using RAG

An AI-powered application that answers questions from PDF documents using Retrieval-Augmented Generation (RAG), semantic search, and Google Gemini.

Tech Stack

Python

Google Colab

PyPDF

NumPy

Sentence Transformers

Google Gemini API

Project Workflow

PDF text extraction

Text chunking with overlap

Text embedding generation

Cosine similarity

Top-K retrieval

Context-based prompt generation

LLM-based answer generation

Source page identification

Daily Progress

Day 1 – Basic RAG Pipeline

Implemented:

Extracted text from a 113-page PDF.

Created 271 text chunks using 1,000-character chunk size and 200-character overlap.

Generated 384-dimensional embeddings using all-MiniLM-L6-v2.

Implemented cosine similarity and Top-5 retrieval using NumPy.

Integrated Gemini 3.6 Flash for answer generation.

Created a reusable ask_question() function.

Challenges Faced:

Hugging Face API returned a 402 Payment Required error.

Gemini 3.8 and 3.7 encountered 503 high-demand errors.

Resolved variable overwriting between the embedding model and Gemini model listing.

Fixed function execution errors caused by incorrect variable references.

Outcome: Successfully implemented and tested a basic end-to-end RAG pipeline that generates answers from PDF content with retrieved source page numbers.
