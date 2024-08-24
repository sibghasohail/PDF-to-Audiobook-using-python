PDF to Audiobook Converter
This project provides a Python script to convert text from PDF files into audiobooks using text-to-speech technology. It extracts text from a PDF file, processes it, and generates an audiobook in MP3 format.

Features:
Extracts text from PDF files.
Converts extracted text to speech.
Handles large PDFs by splitting text into manageable chunks.
Optionally combines audio chunks into a single file.



Requirements:
Before running the script, ensure you have the following Python libraries installed:

pdfplumber for extracting text from PDF files.
gTTS (Google Text-to-Speech) for converting text to speech.
pydub for combining audio chunks (optional).