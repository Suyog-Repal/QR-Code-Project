# 📦 QR Code Generator with Node.js

A simple yet powerful **QR Code Generator** built using **Node.js**. This application allows you to generate QR codes for any URL and saves them as image files locally.

---

## 🚀 Features

- ✅ Accepts user input for a URL
- 📷 Generates a QR Code in PNG format
- 💾 Saves the QR image to the local `qr_img/` folder
- 🌐 Command-line based interaction
- 🛠️ Built using native `readline` and third-party `qr-image` Node.js module

---

## 📁 Project Structure

qr-code-generator/
├── index.js # Main application file (QR generation logic)
├── solution.js # Optional file for alternate logic/testing
├── package.json # Project metadata and dependencies
├── package-lock.json # Locked versions of installed dependencies
├── URL.txt # Stores the entered URL (optional usage)
├── qr_img/ # Directory where generated QR code images are saved
│ └── <your_qr>.png # Example output image
└── node_modules/ # Installed Node.js dependencies
