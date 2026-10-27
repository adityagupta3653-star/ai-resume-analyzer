
# AI Resume Analyzer

A college project built using Python, Flask, HTML, CSS, and JavaScript.

## Features

- Upload PDF and DOCX resumes
- Extract resume text
- Detect known skills
- Compare a resume with a job description
- Calculate a text similarity score
- Identify matching and missing skills
- Display recommendations

## Requirements

- Python 3
- Internet connection for installing dependencies

## Installation

Open the terminal inside the project folder and run:

```bash
python -m pip install -r requirements.txt
```

## Run the application

```bash
python app.py
```

Open the local URL shown in the terminal, usually:

http://127.0.0.1:5000

## Notes

The score is an estimate based on text similarity and detected skills.
It is not a prediction of hiring outcomes. Scanned PDFs may require OCR.
