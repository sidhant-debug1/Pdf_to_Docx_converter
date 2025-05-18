# PDF to DOCX Converter 📝

This is a simple Python utility to convert PDF files into editable DOCX (Microsoft Word) documents using the `pdf2docx` library.

## 📌 Features

- Convert PDF documents to DOCX format with ease
- Lightweight and easy to use
- Suitable for academic reports, scanned PDFs, and structured documents

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.6+
- `pdf2docx` library

Install `pdf2docx` using pip:

```bash
pip install pdf2docx
from pdf2docx import Converter

# Specify input and output file paths
pdf_file = "path_to_input_pdf.pdf"
docx_file = "output_docx.docx"

# Convert the PDF to DOCX
cv = Converter(pdf_file)
cv.convert(docx_file)
cv.close()
