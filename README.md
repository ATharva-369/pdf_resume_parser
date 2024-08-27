# Resume Parser

## Overview

The Resume Parser is a tool designed to extract and analyze key information from resume PDFs. Its a simple proof of work, self project. Meant to be a gear in the cog for a bigger one.
## Features

- **Extract Text:** Reads text from PDF resumes.
- **Skill Extraction:** Identifies and extracts skills from the resume.
- **Experience Extraction:** Identifies and extracts job roles and companies.
- **Data Normalization:** Cleans and formats extracted text for easier analysis.

## Installation

To get started with the Resume Parser, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/ATharva-369/pdf_resume_parser.git
    cd pdf_resume_parser
    ```

2. **Set Up a Virtual Environment (Optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the **parser.py** and put in the path of a **OCR** pdf.
2. You will get a **parsed_resume.json** file.
