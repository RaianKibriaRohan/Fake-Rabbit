# 🐰 Fake Rabbit – Universal OSINT & Decryption Toolkit

**Fake Rabbit** is a multi-functional command-line tool designed for cybersecurity research, CTF practice, digital forensics, and language translation. It provides several utilities including message decryption, steganography, EXIF metadata analysis, reverse geolocation, and text translation—all packed into a single CLI interface.

> ⚠️ **Disclaimer**  
> This project is intended for **ethical, educational, and research purposes only**. The author does not support or condone the use of this tool for malicious activities.

---

## 🚀 Features

- 🔓 **Decryption Tools**
  - Caesar Cipher (shift = 3)
  - ROT13
  - Base64 Decoder
  - XOR Cipher
  - AES (CBC mode with base64 input)

- 🌐 **Text Translation**
  - Detects and translates any language to English using `googletrans`

- 🖼️ **Steganography**
  - Extracts hidden messages from images using LSB method

- 📷 **EXIF Data & GPS**
  - Extract camera make/model and GPS metadata from images
  - Converts GPS to human-readable location using `geopy` (Nominatim)

---

## 📦 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/fake-rabbit.git
cd fake-rabbit
pip install -r requirements.txt
```
---

## 🧪 Usage

Run the script:
```bash
python fake_rabbit.py
```
---

## 🛡️Notice

This tool must only be used in environments where you have explicit permission. Any misuse may be a violation of laws and regulations.

---

## 🧑‍💻 Author

Fake Rabbit maintained by Raian Kibria Rohan | 
Contact: rohanrkrr78@gmail.com | 
Linkedin: https://www.linkedin.com/in/raian-kibria-rohan-89997a323/
