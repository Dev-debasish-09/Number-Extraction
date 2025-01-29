OCR Model Review

Features

Image preprocessing using OpenCV (grayscale conversion, thresholding, noise removal).
Detection of text regions using contour detection.
OCR extraction using Tesseract OCR.
Output of extracted numbers stored in a CSV file
```
OCR-System/
├── input_images/          # Folder for input images
├── output.csv             # Output CSV file with extracted numbers
├── preprocessing.py       # Image preprocessing functions
├── ocr_processing.py      # OCR-related functions
├── main.py                # Main script to process images
├── requirements.txt       # List of dependencies
├── README.md              # Project documentation
├── .gitignore             # Ignore unnecessary files
```
Installation

Requirements
Below are the required dependencies for this project:
```
opencv-python
pytesseract
easyocr
numpy
```

Usage

1. Prepare Images
Place images containing numeric data in the input_images/ folder.

2. Run the OCR Processing
Execute the script:
```
python main.py
```
3. Output
Extracted numbers are saved in output.csv in the format:
```
Image Name, Extracted Numbers
image1.png, , 678.90
image2.jpg, 456.78
```
