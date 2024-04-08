# CV Text Extractor

## Overview
CV Text Extractor is a Python-based tool designed to extract essential information such as email IDs, contact numbers, and overall text content from CVs (curriculum vitae) in various formats. The tool is capable of processing CVs in PDF, DOCX, and DOC formats, ensuring comprehensive extraction of textual data regardless of the file type.

## Features
- Extracts email IDs and contact numbers from CVs
- Captures overall text content including information in table format
- Supports CVs in PDF, DOCX, and DOC formats
- Generates output in .XLS (Excel) format for easy access and analysis

## Usage
1. Ensure Python is installed on your system.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `cv_text_extractor.py` script, providing the paths to the CV files you want to process.
4. The extracted information will be saved in an Excel (.XLS) file named `cv_info.xlsx` on your desktop.

## Dependencies
- Python 3.x
- PyPDF2
- openpyxl
- docx
