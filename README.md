# JupyterUM
 Final project of Python: Pillow, Tesseract and OpenCV from University Of Michigan

## About the project
 This repository contains 2 assignments:
 1. **Colors**: The program takes an image and creates **9** different variants with modified intensity values for certain channels (r, g, b)
 2. **Faces**: The program takes an image and creates a new image with the faces detected in said image.

## Built with
1. [Python 3.9](https://docs.python.org/3.9/whatsnew/3.9.html)

## Resources
1. [Pillow Libary](https://pypi.org/project/Pillow/)
2. [Tesseract](https://github.com/tesseract-ocr/tesseract/wiki#windows)
3. [Pytesseract](https://pypi.org/project/pytesseract/)
4. [Open CV](https://pypi.org/project/opencv-python/)
5. [Open CV Haarcascades](https://github.com/opencv/opencv/tree/master/data/haarcascades)
6. [Pycharm Professional](https://www.jetbrains.com/es-es/pycharm/download/#section=windows)

## Prerequisites
1. Install [Pycharm Professional](https://www.jetbrains.com/es-es/pycharm/download/#section=windows)
2. Install [Tesseract](https://github.com/tesseract-ocr/tesseract/wiki#windows), if you are in a windows machine download the file from the [download](https://github.com/tesseract-ocr/tesseract/wiki/Downloads) page, then, add `C:\Program Files\Tesseract-OCR` to your path, also add a variable called `TESSDATA_PREFIX` with path in `C:\Program Files\Tesseract-OCR\tessdata`. To make sure it works write `tesseract` in the command line, if it recognizes it the installation was successful.

## Run the project
1. Clone the repo
2. Open the project's folder in Pycharm. Make sure to have the Jupyter's package installed