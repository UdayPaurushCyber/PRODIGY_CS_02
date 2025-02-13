# PRODIGY_CS_02

# Image Encryption Tool : Pixel Manipulation

This tool provides a simple yet effective way to encrypt and decrypt images using pixel manipulation techniques. It allows users to securely alter image data using a key-based encryption method.

## Features

- **Encryption**: Encrypt images by scrambling pixel positions and applying mathematical operations.
- **Decryption**: Decrypt previously encrypted images to restore them to their original state.
- **Command-Line Interface**: Easy-to-use CLI for interacting with the tool.

![Example image](https://github.com/UdayPaurushCyber/PRODIGY_CS_02/blob/main/image.jpeg))
## How It Works

### Encryption Process

1. **Load Image**: Load the input image.
2. **Pixel Manipulation**: Randomly swap pixel positions and apply mathematical operations.
3. **Save Encrypted Image**: Save the modified image to a new file.

### Decryption Process

1. **Load Encrypted Image**: Load the previously encrypted image.
2. **Reverse Pixel Manipulation**: Undo the pixel swaps and mathematical operations.
3. **Save Decrypted Image**: Save the restored image to a new file.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/kur1an/PRODIGY_CS_02.git
   cd PRODIGY_CS_02
   ```

2. **Install Dependencies**:
   Make sure you have Python installed on your system. Additionally, install the required libraries using pip:
   ```bash
   pip install pillow
   ```

## Usage

1. **Encrypt an Image**:
   - Run the script: `python image_tool.py`
   - Choose the encryption mode.
   - Provide the input image path.
   - Specify the output path for the encrypted image.
   - Enter the encryption key.

2. **Decrypt an Image**:
   - Run the script: `python image_tool.py`
   - Choose the decryption mode.
   - Provide the input image path (encrypted image).
   - Specify the output path for the decrypted image.
   - Enter the decryption key.

## Example

Encrypt an image:

```bash
python image_tool.py
Choose mode (encrypt/decrypt)e/d: e
Enter the input image path: input_image.jpg
Enter the output image path: encrypted_image.jpg
Enter the encryption key: 12345
```
![Example image](https://github.com/UdayPaurushCyber/PRODIGY_CS_02/blob/main/encrypted_image.jpeg))

Decrypt an image:

```bash
python image_encryption_tool.py
Choose mode (encrypt/decrypt)e/d: d
Enter the input image path: encrypted_image.jpg
Enter the output image path: decrypted_image.jpg
Enter the decryption key: 12345
```
![Example image](https://github.com/UdayPaurushCyber/PRODIGY_CS_02/blob/main/decrypted_image.jpeg)

