Simple Image Encryption Tool
A basic image encryption and decryption tool in Python using pixel manipulation.
This project demonstrates how images can be encrypted using simple operations like XOR with a key and row swapping, and then decrypted back to the original.

Features
Encrypt any image (PNG/JPG) using a numeric key.
Decrypt the encrypted image using the same key.
Simple pixel-level manipulation (XOR + row flip).
Requirements
Python 3.x
Libraries:
Pillow
numpy
Install dependencies using:

pip install pillow numpy
Usage
Place your image in the project folder.
Open terminal/PowerShell and navigate to the project folder:
cd C:\Users\ASUS\OneDrive\Desktop\vit
Run the script:
python image_encryption.py
Follow the interactive menu:
===== Simple Image Encryption Tool =====
1. Encrypt Image
2. Decrypt Image
Enter your choice:

1 to encrypt
2 to decrypt
Enter the image file name (with extension, e.g., input_image.png) and numeric key (e.g., 123).

The output files will be created in the same folder:

encrypted.png → encrypted image
decrypted.png → decrypted image (restored original)
Example
Enter your choice (1 or 2): 1
Enter image file name (with extension, e.g., photo.png): input_image.png
Enter numeric key for encryption/decryption (e.g., 123): 123
 Image encrypted and saved as encrypted.png
Enter your choice (1 or 2): 2
Enter image file name (with extension, e.g., photo.png): encrypted.png
Enter numeric key for encryption/decryption (e.g., 123): 123
 Image decrypted and saved as decrypted.png


## Notes

* Use the **same key** for encryption and decryption.
* Works with **RGB images** and **grayscale images**.
* The algorithm is simple and for **educational purposes only**.

---

## Author

Divyanshi Khare
