# Project Name

Text Extraction from Images using OpenCV

## Description

This project aims to extract text from images and applies basic functions of OpenCV to enhance the text and obtain more accurate results. It is a useful tool that saves time and effort by eliminating the need to manually type text from images.

## Installation

To run this project, you need to have Python 3.9+ installed on your system. Additionally, the following libraries are required:

- Requests
- Pytesseract
- wand
- OpenCV
- Numpy
- PIL

Tested with:
- requests: 2.32.3
- pytesseract: 0.3.10
- opencv-python: 4.9.0.80
- numpy: 1.26.4
- pillow: 10.3.0

You can install these libraries by running the following command:

```
pip install requests pytesseract opencv-python numpy pillow
```
OR

```
pip install requests==2.32.3 pytesseract==0.3.10 opencv-python==4.9.0.80 numpy==1.26.4 pillow==10.3.0
```

### Aside Note:
Please install and setup tesseract-ocr libtesseract-dev libmagickwand-dev on your system and set the PATH variables

## Instructions

1. Install the required libraries mentioned above.
2. Download the "ind.traineddata" file required for tesseract-ocr by running the provided code snippet in the project.
3. Run the project by executing the code in a Python environment.
4. The project will prompt you to provide the URL of the image from which you want to extract text. Enter the URL when prompted.
5. The program will download and process the image.
6. The extracted text will be displayed on the console.
7. Additional image transformations and operations will be performed to enhance the text and identify specific patterns or words.
8. The final processed image with rectangles around the text and specific patterns will be displayed.
9. You can modify the code to perform additional operations or customize the text extraction process as per your requirements.

## Limitations

- The accuracy of text extraction depends on the quality and clarity of the input image.
- Complex images with overlapping text or noisy backgrounds may result in less accurate text extraction.
- The program may encounter difficulties in recognizing certain fonts or handwritten text.

## Conclusion

This project provides a solution for extracting text from images using OpenCV. It demonstrates various image transformations and operations that can be applied to enhance text extraction. It can be used by organizations and individuals to extract useful information from images and automate the process of transcribing text.

## Scope

The scope of this project extends to various industries and domains where text extraction from images is required. It can be utilized in data entry, document processing, image recognition, and other applications that involve extracting text from images.