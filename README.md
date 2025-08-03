
![Screenshot 2025-06-07 151228](https://github.com/user-attachments/assets/518a9e58-fd03-4fc1-8aab-69a792682ce5)

# Gdrive+Gmail AI Agent

## Overview
This project implements an AI-powered agent capable of retrieving PDFs from **Google Drive** and emails from **Gmail**, extracting text using **PyMuPDF (fitz)**, and generating summaries with the **Gemini 2.0 Flash**. **Gradio** for Chatbot UI. It provides seamless integration for document retrieval and processing, optimizing text extraction and summarization workflows.

## Features
- 📂 **Google Drive API Integration** – Search and retrieve PDFs directly from Google Drive and emails from Gmail
- 🔍 **Text Extraction** – Uses `fitz` (PyMuPDF) for efficient text extraction.
- 🤖 **AI-Powered Summarization** – Leverages **Ollama LLM** for document understanding.
- 🤖 **Langchain ReAct** - Agents ReAct framework for triggering right tools based on user query context
