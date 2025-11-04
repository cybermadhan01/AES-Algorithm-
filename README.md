# AES-Algorithm-
The Advanced Encryption Standard (AES) is a symmetric key encryption algorithm used worldwide to secure data. It encrypts and decrypts data in fixed 128-bit blocks using keys of 128, 192, or 256 bits, providing strong confidential protection. AES works through multiple rounds of substitutions, permutations, and mixing of plaintext bytes.
# 0xCipherLink

## Secure File Transfer Tool

**0xCipherLink**, a secure file transfer tool designed by 0x4m4. This tool ensures your files are transferred safely and confidentially over the network using strong encryption methods.

### Features

- **AES-256 Encryption**: Ensures that your files are encrypted with one of the strongest encryption standards.
- **PBKDF2 Key Derivation**: Uses a robust key derivation function with salt and multiple iterations to protect your password.
- **User-Friendly Interface**: Simple and intuitive GUI built with Tkinter.
- **File Integrity**: Maintains file name and integrity during transfer.

### Why 0xCipherLink?

Unlike other online file sharing tools that might expose your files to security vulnerabilities or data breaches, **0xCipherLink** ensures end-to-end encryption. Your files are encrypted locally on your machine before being sent over the network, ensuring that only the intended recipient can decrypt and access them. It also works on all platforms, weather its an windows machine, linux, mac, or an android phone.

### Requirements

To run 0xCipherLink, you need to have the following installed:

- Python 3.x
- Required Python libraries:
  - `tkinter`
  - `socket`
  - `cryptography`

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/0x4m4/0xCipherLink.git
    cd 0xCipherLink
    ```

2. **Install the Required Libraries**:
    ```sh
    pip install cryptography
    ```
    ```sh
    pip install socket
    ```
    ```sh
    pip install tkinter
    ```

### Usage

1. **Run the Tool**:
    ```sh
    python 0xCipherLink.py
    ```

2. **Sending a File**:
    - Open **0xCipherLink** and select "Send".
    - Enter the recipient's host address and port.
    - Choose the file you want to send.
    - Enter a secure password.
    - Click "Execute" to send the file.

3. **Receiving a File**:
    - Open **0xCipherLink** and select "Receive".
    - Enter the port to listen on.
    - Enter the password that the sender will use.
    - Click "Execute" to start listening for incoming files.

### Example Usage

