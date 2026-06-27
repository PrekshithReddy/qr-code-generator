# QR Code Generator

A simple command-line application built with **Node.js** that generates a QR code image from a user-provided URL. The application also saves the entered URL into a text file for future reference.

## 🚀 Features

- Accepts a URL through the command line.
- Generates a QR code image (`qr_img.png`).
- Saves the entered URL to `URL.txt`.
- Built using popular Node.js npm packages.

## 🛠️ Technologies Used

- Node.js
- JavaScript (ES6 Modules)
- Inquirer
- qr-image
- File System (`fs`) Module

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/PrekshithReddy/qr-code-generator.git
```

2. Navigate to the project directory:

```bash
cd qr-code-generator
```

3. Install the required dependencies:

```bash
npm install
```

## ▶️ Usage

Run the application using:

```bash
node index.js
```

Enter a valid URL when prompted.

Example:

```
Type in your URL:
https://www.google.com
```

The application will generate:

- `qr_img.png` – QR code image
- `URL.txt` – Stores the entered URL

## 📁 Project Structure

```
qr-code-generator/
│── index.js
│── package.json
│── package-lock.json
│── .gitignore
│── README.md
```

## 📚 Dependencies

- inquirer
- qr-image

## 👨‍💻 Author

**Prekshith Reddy**

GitHub: https://github.com/PrekshithReddy

## 📄 License

This project is open source and available under the MIT License.
