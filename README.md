This repository contains a Question-Answering (QA) system that combines extractive and abstractive approaches using a Hybrid Retrieval-Augmented Generation (RAG) workflow.
It demonstrates how to:

Use a pre-trained language model for baseline QA.

Apply RAG to retrieve relevant context from large text documents using embeddings (Sentence Transformers) and FAISS.

Generate context-aware answers using a text-generation model.

This approach improves the accuracy and relevance of answers compared to using a single pre-trained model.

Features

Extractive retrieval from large text passages

Abstractive answer generation using pre-trained LLMs

Handles long paragraphs and overlapping text chunks

Interactive question-answer interface
