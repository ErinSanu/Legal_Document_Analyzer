# BrevityLaw

Bringing simplicity to legal documents.

## Overview
**BrevityLaw** is a Streamlit-based web application that simplifies legal documents by:
- Extracting text from uploaded PDF files.
- Summarizing the extracted content using a transformer model (`nsi319/legal-led-base-16384`).
- Translating the summarized text into multiple regional languages.
- Converting the translated summary into speech using `gTTS`.

This project leverages Hugging Face Transformers, PyMuPDF, Google Translate, and text-to-speech technology to assist users in navigating complex legal documents.

---

## Features
- **PDF Upload**: Upload legal documents in PDF format.
- **Text Extraction**: Automatically extract text from the uploaded document.
- **Summarization**: Generate concise and structured summaries of lengthy documents.
- **Translation**: Translate summaries into multiple Indian languages:
  - Hindi
  - Kannada
  - Telugu
  - Tamil
  - Malayalam
- **Text-to-Speech**: Convert translated summaries into audio for better accessibility.

---

## Tech Stack
- **Frontend**: Streamlit
- **Backend**: Hugging Face Transformers, Google Translate, gTTS
- **PDF Parsing**: PyMuPDF (`fitz`)
- **Programming Language**: Python

---

## Installation
### Prerequisites
Ensure the following are installed:
- Python 3.8 or higher
- Pip


