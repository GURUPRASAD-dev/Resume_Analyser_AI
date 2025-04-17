# Resume Analyzer

This is a simple web application built with **Flask** that allows users to upload resumes in **PDF** or **DOCX** format. The resumes are processed using **Meta AI** to generate a score and provide feedback based on various categories such as **Skills**, **Education**, **Experience**, **Formatting**, and **Impact**. The results are presented to the user in an organized format with recommendations to improve the resume.

## Features

- Upload **PDF** or **DOCX** resumes.
- Process resumes using **Meta AI** for detailed analysis.
- Get a **resume score** out of 100.
- Receive detailed feedback, strengths, weaknesses, and recommendations.
- Beautiful and responsive user interface using **HTML**, **CSS**, and **Bootstrap**.

## Requirements

- **Flask**: Web framework for Python.
- **gunicorn**: WSGI server for running Flask applications.
- **pdfplumber**: Extract text from PDF resumes.
- **python-docx**: Extract text from DOCX resumes.
- **meta_ai_api**: Integration with Meta AI for resume analysis.

## Installation

To set up this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/resume-analyzer.git
   cd resume-analyzer
