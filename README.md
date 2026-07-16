# Resume Parser

A simple AI-powered Resume Parser built using Python.

## Features

- Extracts text from PDF and DOCX resumes
- Parses resume content
- Displays extracted information
- Supports multiple resume formats

## Project Structure

```
day5/
├── main.py
├── resume_parser.py
├── resume/
├── pyproject.toml
├── uv.lock
└── README.md
```

## Installation

```bash
uv sync
```

or

```bash
pip install -r requirements.txt
```

## Run

```bash
python main.py
```

## Sample Input

Place resumes inside the `resume/` folder.

Supported formats:
- PDF
- DOCX

## Tech Stack

- Python
- PyPDF2 / pdfplumber
- python-docx