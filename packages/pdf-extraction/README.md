# 📄 PDF Extraction – PureBhaktiBase

This package handles the **batch extraction of content** from Śrīla Gurudev’s books (PDF format) to prepare the knowledge base for AI processing.

---

## ✨ Purpose

The `pdf-extraction` module is responsible for:

- 🔍 **Parsing PDFs:**
  - Extracting text **by chapter, page number, or section**
  - Retaining metadata like **headings, page numbers, and references**

- 🗂️ **Content Structuring:**
  - Converting raw text into **structured JSON/CSV formats**
  - Tagging key elements (e.g., slokas, translations, commentaries)

- 🧹 **Preprocessing:**
  - Cleaning text (e.g., remove OCR noise, unwanted symbols)
  - Detecting language or transliteration where needed

---

## 🛠️ Tech Stack

| 🔧 **Tool/Library**      | 📄 **Usage**                                      |
|--------------------------|--------------------------------------------------|
| Python                   | Core language                                   |
| PyPDF2 / pdfminer.six    | Text extraction from PDF files                  |
| pandas                   | Data formatting/export                          |
| re (Regex)               | Parsing and text cleaning                       |
| langdetect / polyglot    | (Optional) Language detection                   |

---

## 📑 Folder Structure

| 📁 **Folder/File**       | 📄 **Description**                                              |
|--------------------------|-----------------------------------------------------------------|
| `/src/`                  | Python scripts for PDF parsing, extraction logic               |
| `/tests/`                | Unit tests for extraction scripts                              |
| `/sample-data/`          | Example PDFs for testing (if allowed)                           |
| `output/`                | Stores extracted structured data (JSON/CSV)                    |
| `requirements.txt`       | Python dependencies                                            |
| `README.md`              | This documentation file                                        |

---

## 🚀 Getting Started

1️⃣ **Set up virtual environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
