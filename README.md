# QR Code Generator 🖼️📱

## Overview

Welcome to the QR Code Generator project! This is a simple web application that allows you to create QR codes for any URL or text. Built using HTML, CSS, and JavaScript, it offers an easy way to generate QR codes with just a click. 🌟

## Features

- **Enter URL or Text**: Simply type or paste your URL or text into the input field.
- **Generate QR Code**: Click the button to generate a QR code.
- **Responsive Design**: The interface adapts to various screen sizes for a seamless experience. 📱💻

## How It Works

1. **Enter URL or Text**: Type or paste the URL or text you want to convert into a QR code.
2. **Generate QR Code**: Click the "Click here to Generate QR Code" button.
3. **Display QR Code**: The generated QR code will appear below the button.

## QR Code Generation API

The QR code is generated using the [ https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=Example ](https://api.qrserver.com/v1/create-qr-code/). Here’s how you can use it:

**API URL Format:**
https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=YOUR_DATA


- **`size`**: The dimensions of the QR code (e.g., `150x150`).
- **`data`**: The content to encode (replace `YOUR_DATA` with your URL or text).

**Example:**

To generate a QR code for the URL `https://www.example.com`, use the following API URL:

https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://www.example.com


## Project Files

- **`index.html`**: The HTML file for the QR Code Generator interface.
- **`style.css`**: The CSS file for styling the interface.
- **`app.js`**: The JavaScript file that handles QR code generation.

## How to Use

1. **Clone or Download**: Clone or download this repository.
2. **Open in Browser**: Open `index.html` in a web browser.
3. **Generate QR Code**: Enter a URL or text and click the button to generate a QR code. 📤



