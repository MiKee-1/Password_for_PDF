# PDF Password Protector

This simple Python script allows you to secure any PDF file with a password, making it ideal for protecting sensitive or private documents.

### 📄 Description

The script reads an input PDF, copies all its pages, and saves a new password-protected version. It's useful for automating PDF security in personal, academic, or business environments.

### ⚙️ Requirements

* Python 3.x
* [PyPDF2](https://pypi.org/project/PyPDF2/)

Install the required library with:

```bash
pip install PyPDF2
```

### 🚀 Usage

```bash
python3 script.py <input_pdf> <output_pdf> <password>
```

**Example:**

```bash
python3 script.py myfile.pdf protected_file.pdf mySecret123
```

### 📌 Features

* Adds password protection to existing PDF files.
* Handles common errors like missing files or invalid PDFs.
* Easy to use from the command line.

