Secure Data Hiding in Images using Steganography (Python)                       


1.This project demonstrates a simple implementation of image steganography using Python and OpenCV.
2.Provides a secure and user-friendly way to encrypt and decrypt messages within images using steganography and password protection.

*Features
Data Hiding (Encryption):
1.Embed a secret text message into a cover image. 
2.The program writes each character's ASCII value into the image pixels (using a diagonal embedding method) and saves the modified image as a lossless PNG file to preserve data integrity.

Decryption:
Retrieve the hidden message from the modified image by providing the correct passcode and the message length.
