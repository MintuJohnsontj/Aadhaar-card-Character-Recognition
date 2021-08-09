# Aadhaar-card-Character-Recognition

Here, we are going to use OCR technology to recognize the characters printed on the card. This project extracts text from a picture of an Aadhar Card. It takes an image (i.e. a jpg or png file) as an argument to the command and validates if the image is an Aadhar Card or not by providing the Aadhar number from the image. It extracts information from the image like name of the card holder, date of birth or year of birth, whichever is available and the Aadhar card number.

## Features
1. OCR using Python.

## Requirements:
OpenCv
pytesseract
numpy

## What is Aadhaar
Aadhaar is a 12-digit unique identity number that can be obtained voluntarily by residents or passport holders of India, based on their biometric and demographic data. The data is collected by the Unique Identification Authority of India (UIDAI), a statutory authority established in January 2009 by the government of India. Aadhaar is the world’s largest biometric ID system. The Aadhaar card consists of key information on the person such as the name, gender, and date of birth in plain text as well as a QR code. UIDAI has introduced a new Secure QR Code which contains demographic details of a resident like name, address, date of birth, gender and masked Aadhaar number as well as a photograph of the Aadhaar number holder.

## pytesseract
Pytesseract is a Python package that allows you to extract text from images. If you have a picture that has some text in it, pytesseract can pull out the text into a Python program. That's pretty cool. Pytesseract is a wrapper around a program from Google called tesseract. It's tesseract that extracts the text from pictures. Pytesseract is there to help you use tesseract in your Python programs.
### tesseract
Tesseract is a command-line application created by Google that can be used to pull text out of pictures. It is an example of an OCR application, which stands for Optical Character Recognition. Which is just a fancy way of saying using a computer to read text. Tesseract is capable of reading text in many different languages. It works best with computer-generated text like text in PDFs or pictures of receipts and invoices. It has a tougher time with images that contain handwritten words.
### How to install pytesseract
Tesseract installer for Windows:
https://github.com/UB-Mannheim/tesseract/wiki
