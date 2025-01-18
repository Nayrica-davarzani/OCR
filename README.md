# OCR Image Processing and Text Extraction

This project demonstrates Optical Character Recognition (OCR) techniques using Tesseract OCR and OpenCV for processing images. It extracts text from various image formats, performs text localization, and supports multi-language text extraction.

---

## Features

- **Text Extraction**:
  - Extracts text from images using Tesseract OCR.
  - Handles thresholding and noise reduction for better OCR accuracy.
  
- **Text Localization**:
  - Identifies and draws bounding boxes around recognized text in images.

- **Multi-Language Support**:
  - Includes support for Persian (Farsi) text recognition.

---

## Prerequisites

- **Python**: Ensure Python 3.6 or higher is installed.
- **Tesseract OCR**:
  - Download and install [Tesseract OCR](https://github.com/tesseract-ocr/tesseract).
  - Update the path to `tesseract.exe` in the script:
    ```python
    pytesseract.pytesseract.tesseract_cmd = "C:/Program Files/Tesseract-OCR/tesseract.exe"
    ```

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Nayrica-davarzani/OCR.git
