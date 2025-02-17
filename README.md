# PRODIGY_CS_02

# Image Encryption and Decryption using Pixel Manipulation

## 📌 Overview
This Python program encrypts and decrypts images using **pixel manipulation and XOR operation**. It generates a unique encryption key for each image and ensures secure decryption using the same key.

## 🚀 Features
- Encrypt images by modifying pixel values.
- Generate and store an encryption key for later use.
- Decrypt encrypted images using the saved key.
- Ensures secure encryption using XOR-based pixel transformation.
- Handles errors for missing files and incorrect inputs.

## 🛠 Requirements
- Python 3.x
- Pillow (`pip install pillow`)
- NumPy (`pip install numpy`)

## 📌 How It Works
1. **Encryption:**
   - Loads an image.
   - Generates a random encryption key and stores it (`encryption_key.npy`).
   - Applies XOR operation to pixel values.
   - Saves the encrypted image as `encrypted_image.png`.

2. **Decryption:**
   - Loads the encrypted image and stored key.
   - Applies XOR operation again to restore the original image.
   - Saves the decrypted image as `decrypted_image.png`.

## 📜 Usage
1. **Run the script:**
   ```sh
   python image_encryption.py
   ```
2. **Enter the path** to your image when prompted.
3. The program will automatically **encrypt and decrypt** the image.

## 📂 Output Files
- `encrypted_image.png` (Encrypted version of the image)
- `decrypted_image.png` (Decrypted image, identical to the original)
- `encryption_key.npy` (Stored encryption key for decryption)

## ⚠️ Important Notes
- The **same key is required** for decryption. If the key file is lost, decryption will not work.
- The encryption is **not meant for high-security applications** but serves as an educational tool.

## 📧 Contact
For any questions or improvements, feel free to reach out!

Happy Coding! 🚀
