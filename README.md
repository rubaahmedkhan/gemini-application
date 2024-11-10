# Multi-Functional AI Systems - Voice Assistant, PDF Tools, and Chatbot

This project implements multiple AI-powered tools including a **Voice Assistant**, **PDF MCQ Generator**, **PDF Question Answering**, and a **Chatbot with Chat History**. These tools leverage **Google's Gemini** language model (or equivalent) to provide seamless and intelligent functionality for educational and interactive use cases.

## Features

### 1. **Voice Assistant**
The Voice Assistant allows users to interact with the system using voice commands. It can perform various tasks such as:
- Answering user questions.
- Executing basic commands like opening tools or processing documents.
- Interacting with the PDF tools or chatbot functionalities.

### 2. **PDF MCQ Generator**
This tool extracts text from a PDF and generates multiple-choice questions (MCQs) based on the content. Features include:
- Extraction of text from educational PDFs.
- Generation of relevant MCQs based on the text.
- Option to customize difficulty level for generated questions.

### 3. **PDF Question Answering**
This tool enables users to ask specific questions based on a PDF file. The system uses the extracted text from the PDF to find relevant answers. Features include:
- PDF text extraction.
- Answering user queries based on PDF content using the Gemini model.
- Works with textbooks, research papers, and other educational documents.

### 4. **Chatbot with Chat History**
The chatbot maintains a conversation history to provide context-aware responses over time. Features include:
- Continuously tracks the conversation.
- Responds intelligently based on previous exchanges.
- Allows users to retrieve and review past conversations.

## Technology Stack

- **Gemini Language Model** (for natural language understanding and processing)
- **Python** (for backend development)
- **SpeechRecognition** (for voice-to-text functionality)
- **PyPDF2 / PDFMiner** (for PDF text extraction)
- **Flask / FastAPI** (optional, for serving APIs)
- **SQLite / JSON** (for storing chat history)

## Prerequisites

Before running the project, ensure you have the following Python libraries installed:

- Python 3.x
- `gemini` or equivalent API (check for access to the model)
- `SpeechRecognition`
- `PyPDF2` or `PDFMiner`
- `flask` or `fastapi` (optional, for web APIs)
- SQLite or JSON (for storing chat history)

You can install the dependencies using:

```bash
pip install -r requirements.txt
