# Secure Data Hiding in Image Using Steganography

## 📌 Project Overview
This project implements **Least Significant Bit (LSB) Steganography** with **AES Encryption** to securely hide and extract data inside images. It ensures message confidentiality while maintaining image quality and supports **Google Colab execution** for seamless cloud-based processing.

## ✨ Features
- **LSB Steganography**: Hides secret messages inside images with minimal distortion.
- **AES Encryption**: Adds an extra layer of security before embedding the message.
- **Randomized Pixel Selection**: Prevents easy detection of hidden data.
- **Supports Multiple Formats**: Works with **PNG, BMP, and JPEG**.
- **Google Colab Compatible**: Runs without any local setup.

## 🛠️ Technologies Used
- **Programming Language**: Python 3
- **Libraries**:
  - Pillow (PIL) : Image processing
  - NumPy : Pixel manipulation
  - PyCryptodome : AES Encryption
  - Base64 : Encoding encrypted messages
- **Platform**:
  - Google Colab (Cloud Execution)

## 🚀 Installation & Setup
### 1️ Clone the Repository**

git clone https://github.com/Liharika03/Steganography
cd Steganography-Project


### 2️ Install Dependencies**
```
pip install pillow numpy pycryptodome
```

## 🔹 Usage Guide
### **🔹 Hiding Data in an Image**
```python
from steganography import embed_data
embed_data("input.png", "Hello, Secure World!", "securekey123", "output.png")
```

### **🔹 Extracting Hidden Data**
```python
from steganography import extract_data
hidden_message = extract_data("output.png", "securekey123")
print("Hidden Message:", hidden_message)
```


## 🔮 Future Scope
- AI-powered **steganography detection resistance**.
- **Kotlin-based Android app** for secure image-based messaging.
- **Hybrid steganography** combining LSB & DCT for better security.
- **Blockchain-based verification** for authentication.

## 🤝 Contributors
- **A.Liharika** 

## 📜 License
This project is **open-source** under the MIT License.

---
### 💡 *Feel free to contribute and improve the project!* 🚀
