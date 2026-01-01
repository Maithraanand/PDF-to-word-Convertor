# PDF-to-word-Convertor
This project implements an automated PDF to Word document conversion system using Python in a Google Colab environment. The system is designed to handle both text-based PDFs and scanned/image-based PDFs by integrating Optical Character Recognition (OCR) techniques.

The workflow begins by allowing users to upload a PDF file directly in Colab. For text-based PDFs, the document is converted into an editable Word (.docx) format using structured PDF parsing, preserving layout and formatting. For scanned or image-heavy PDFs, the system extracts images from each page and applies OCR to recognize and convert embedded text into machine-readable form.

The project uses PyMuPDF for PDF processing, pdf2docx for direct PDF-to-Word conversion, and Tesseract OCR for extracting text from images. Once conversion is complete, the generated Word document is automatically made available for download or saved to Google Drive for easy access.

Key Features

Supports both digital and scanned PDFs

Automatic OCR-based text extraction

Converts PDFs into editable Word documents

Runs fully on Google Colab

Simple upload-and-download workflow

Reduces manual effort in document retyping and editing

Applications

Digitizing scanned documents

Academic and research document conversion

Legal and business document editing

Archival and record management systems

This project demonstrates practical use of document processing, OCR, and automation, making it a useful real-world solution for efficient document digitization and conversion.
