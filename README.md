# PDF to Text Extractor with OCR

This project converts each page of a PDF file into images and then uses Optical Character Recognition (OCR) to extract text from those images. The extracted text is printed to the console.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.x.
- You have installed the required Python packages:
  - `pdf2image`
  - `pytesseract`
  - `opencv-python`
- You have `poppler` installed. You can download it from [Poppler for Windows](http://blog.alivate.com.au/poppler-windows/).
- You have Tesseract-OCR installed. You can download it from [Tesseract at UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki).

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/pdf-to-text-extractor.git
    cd pdf-to-text-extractor
    ```

2. Install the required packages:
    ```bash
    pip install pdf2image pytesseract opencv-python
    ```

3. Install Poppler:
   - Download the latest version of Poppler from [Poppler for Windows](http://blog.alivate.com.au/poppler-windows/).
   - Extract the contents and note the path to the `bin` folder.

4. Install Tesseract-OCR:
   - Download the latest version of Tesseract-OCR from [Tesseract at UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki).
   - Install Tesseract and note the installation path.

## Usage

1. Ensure you have the PDF file (`invoice.pdf`) in the project directory.

2. Open the `pdf_to_text.py` file and ensure the paths to Poppler and Tesseract are correctly set.

3. Run the script:
    ```bash
    python pdf_to_text.py
    ```

4. The script will:
    - Convert each page of `invoice.pdf` into an image.
    - Display each image (optional).
    - Extract text from each image and print it to the console.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`.
4. Push to the original branch: `git push origin <project_name>/<location>`.
5. Create the pull request.

## Contact

If you want to contact me, you can reach me at <ankitsrivastav.work@gmail.com>.

## Acknowledgements

- [pdf2image](https://github.com/Belval/pdf2image)
- [pytesseract](https://github.com/madmaze/pytesseract)
- [OpenCV](https://opencv.org/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
