# OCR PDF Reader

This project is a simple OCR-based PDF reader that extracts text from scanned or image-based PDFs. It’s useful when standard text extraction doesn’t work (for example, scanned documents).

---

## What it does

* Reads PDF files (including scanned PDFs)
* Converts pages into images
* Uses OCR to extract text from each page
* Outputs the extracted text

---

## How it works

1. Load a PDF file
2. Convert each page into an image
3. Run OCR on each image
4. Combine the extracted text

---

## Tech Used

* Python
* Tesseract OCR
* OpenCV
* Pillow (PIL)
* pdf2image / PyMuPDF

---

## Project Structure

```
OCR-PDF-Reader/
├── main.py
├── requirements.txt
└── README.md
```

---

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

---

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Install Tesseract

This project requires Tesseract OCR installed separately.

* Mac:

```bash
brew install tesseract
```

* Ubuntu:

```bash
sudo apt install tesseract-ocr
```

* Windows:
  Download from: https://github.com/tesseract-ocr/tesseract

---

### 4. Run the script

```bash
python main.py
```

Update the script with your PDF file path if needed.

---

## Notes

* Works best with clear scanned PDFs
* OCR accuracy depends on image quality
* Preprocessing can improve results

---

## Future Improvements

* Add a simple UI
* Support batch processing
* Export results to text or CSV
