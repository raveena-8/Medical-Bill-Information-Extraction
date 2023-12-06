# Medical-Bill-Information-Extraction

# Libraries Used
pdf2image: Used for converting PDF pages to images for OCR.
pytesseract: Employed for OCR (optical character recognition) to extract text from images.
Regular Expressions (regex): Utilized for pattern matching and text extraction.
PyMuPDF: For PDF parsing and text extraction.
pdfplumber: For extracting table data and structured information from PDFs.
poppler-utils: External tool used by pdfplumber for efficient PDF parsing.

# Usage
Input: Multi-page PDF medical bills.
Output: JSON format containing extracted information (header, table data, etc.).

# Code Overview
The code uses PyMuPDF to split the multi-page PDF into individual bills.
It employs pdfplumber and pytesseract for text extraction and table data extraction from each bill.
The extracted information is formatted into JSON for each bill separately.

# Instructions
Place your multi-page PDF containing medical bills in the /content/ directory.
Update the bill_files list with the correct paths to your bill files.
Run the code to extract and format information from the provided medical bills.
