# Python-Mini-Project
QR Code Generator Using Python
About the Project
This project is created using Python to generate QR codes for text, URLs, and UPI payment details.

It also includes an experiment with extracting text from images using Python.

Technologies Used
Python
qrcode
Pillow
pytesseract (for the OCR experiment)
Features
1. Text QR Code
Generates a QR code from user-provided text or data.

2. URL QR Code
Creates a QR code for a URL and checks whether it starts with HTTP or HTTPS.

3. Colorful QR Code
Generates a customized QR code using different foreground and background colors.

4. UPI QR Code
Creates a payment QR code using a UPI ID and payee name.

5. UPI QR Code with Amount
Generates a payment QR code containing the UPI ID, payee name, and amount.

6. Image Text Extraction
Includes an OCR experiment using pytesseract to extract text from an image.

Installation
Install the required libraries:

pip install "qrcode[pil]"
pip install pytesseract
The OCR experiment also requires the Tesseract OCR application to be installed separately.

#How to Run
Install the required dependencies.
Open QRcodeproject.ipynb in Jupyter Notebook.
Run the cells in order.
Enter the requested text, URL, or UPI details.
The generated QR code is saved as a PNG image.
#Learning Outcomes
Working with Python libraries
Taking user input
Using conditional statements
Validating URLs
Generating and saving images
Creating customized QR codes
Understanding basic OCR functionality
