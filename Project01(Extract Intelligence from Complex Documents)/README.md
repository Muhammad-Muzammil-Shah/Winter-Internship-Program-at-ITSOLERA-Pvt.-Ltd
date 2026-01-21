# Extract Intelligence from Complex Documents

## Overview
This project is an **Intelligent Document Understanding and Summarization Platform** designed to process complex documents and extract meaningful intelligence. It leverages advanced NLP techniques and vector storage to provide executive summaries, actionable insights, and named entity recognition.

## Features
- **Document Processing**: Supports upload and processing of PDF and DOCX files.
- **Text Extraction**: efficient extraction of text content from uploaded documents.
- **Vector Storage**: Utilizes ChromaDB for efficient storage and retrieval of document chunks.
- **NLP Engine**: Powered by Groq API for high-speed natural language processing tasks.
  - **Executive Summaries**: Generates concise summaries of long documents.
  - **Actionable Insights**: Extracts key takeaways and actionable items.
  - **NER (Named Entity Recognition)**: Identifies entities such as people, organizations, and dates.
- **Contextual Q&A**:  RAG (Retrieval-Augmented Generation) pipeline allows users to query documents and get accurate answers based on context.

## Technology Stack
- **Backend**: Python, Flask
- **Database**: ChromaDB (Vector Store)
- **AI/LLM**: Groq API
- **Frontend**: HTML/CSS/JavaScript

## Setup and Installation
1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd "Project01(Extract Intelligence from Complex Documents)"
    ```
3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4.  **Set up Environment Variables**:
    - Create a `.env` file based on `.env.template`.
    - Add your Groq API Key.

5.  **Run the Application**:
    ```bash
    python app.py
    ```

## Usage
- Open your browser and navigate to `http://localhost:5000`.
- Upload a document to start processing.
- View extracted insights and use the chat interface to query the document.
