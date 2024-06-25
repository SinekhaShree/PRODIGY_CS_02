## Image Encryption and Decryption Tool
## Overview
This project is developed as part of my Cyber Security internship with Prodigy InfoTech. It is a tool for encrypting and decrypting image files using Python, complete with a user-friendly GUI built with Tkinter. The tool enhances data privacy by securely encrypting image files, making it an essential component in the field of cyber security.

## Features
1)Image Encryption: Encrypts image files to protect sensitive information.
2)Image Decryption: Decrypts previously encrypted images back to their original form.
3)User-Friendly GUI: Built with Tkinter for easy selection of files and execution of encryption/decryption operations.
4)Support for Multiple Image Formats: Supports .jpg, .jpeg, .png, and .bmp file formats.

## Requirements
Python 3.x
Pillow

You can install the required packages using:
pip install Pillow

## Usage
## Running the Tool
1.Clone the repository:
git clone https://github.com/your-username/image-encryption-tool.git
cd image-encryption-tool

2.Run the 'main.py' script:
python main.py

## GUI Instructions
1.Select Image: Click the "Select Image" button to choose the image file you want to encrypt or decrypt.
2.Enter Key: Input an integer key for encryption or decryption.
3.Select Output Path: Choose the output path where the processed image will be saved.
4.Choose Mode: Select either "Encrypt" or "Decrypt".
5.Process Image: Click the "Process" button to perform the operation. A message will confirm the success of the operation.

## File Structure
image-encryption-tool/
│
├── main.py          # Main script to run the tool
├── README.md        # This readme file
└── requirements.txt # List of dependencies

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.
