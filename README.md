# Project 14-Optical_Character_Recognition System

In this project, the proposed challenge involves the recognition and extraction of text from images, along with the application of functions to enhance and achieve more accurate results.

⚙ Development Tools:
- Programming Language: Python 3.11.4
- IDE: Visual Studio Code (VS Code)

⚙️ Used Libraries:
- PIL (Python Imaging Library - Pillow): Used for image manipulation in Python.
It was used to load, resize, and save images. In the developed code, it is used to open the 'pbIdS.png' image, resize it, and save it as 'sample.png'.

- pytesseract: A Python wrapper for the Tesseract-OCR library, which is an optical character recognition tool.
It was used to extract text from images. It is applied to the image file using specified configurations and returns the text contained in the image.

- cv2 (OpenCV - Open Source Computer Vision Library): A computer vision library used for processing and analyzing images and videos.
It was used to perform image processing, color conversions, filtering, segmentation, edge detection, and pattern recognition.

- numpy: Used for numerical computation. Provides data structures and functions for mathematical operations.
It was used to work with numerical arrays and matrices, which is useful for mathematical operations and manipulations on image data, such as mean and median calculations.

- pytesseract - Output: The pytesseract library has an Output module that provides constants for different types of Tesseract-OCR output, such as extracted text and bounding boxes.
It was used to specify the desired output type when extracting information from images.

- re (Regular Expressions): Allows working with regular expressions, which are patterns of character sequences used for text search and manipulation.
It was used to manipulate and process the extracted text from images. It was used to remove certain unwanted characters from the extracted text.

### What the Algorithm Is Doing?
1) It starts by downloading an essential file for Tesseract OCR.
2) It prepares the environment by creating local directories.
3) It uses Tesseract and OpenCV to extract and enhance text from images, perform noise removal, thresholding, and skew correction.
4) It identifies patterns and draws rectangles around them.

### Practical Applications:
Imagine the efficiency of automatically converting text-containing images into digital information? This project is useful for:

1) Document scanning.
2) Converting images into editable text.
3) Identifying keywords or patterns in images.
