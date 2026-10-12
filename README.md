# Universal Data Table Viewer 📊

A blazing-fast, lightweight, single-file client-side application designed to instantly parse, view, filter, and interact with tabular data (CSV, tab-delimited files, custom-separated text) directly in your browser.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?logo=tailwind-css&logoColor=white)

---

## ✨ Features

* **⚡ Zero Build Steps:** Built as a single, self-contained `index.html` file—no complex bundlers, servers, or npm installations required. Just open it in any browser!
* **🔄 Flexible Separators:** Instantly switch between **Comma (`,`)**, **Semicolon (`;`)**, **Tab (`\t`)**, **Pipe (`|`)**, or type a custom separator on the fly.
* **🌓 Monochromatic Dark Mode:** Features a modern, high-contrast pure black and zinc dark mode toggle with smooth color transitions.
* **🔍 Global Real-Time Search:** Instantly filter rows across all columns with the built-in search bar.
* **📋 Granular Copy Actions:** 
  * Copy individual cells.
  * Copy entire columns with a single click.
  * Copy entire rows for quick data extraction.
* **📜 Synced Dual Scrollbars:** Features a custom top horizontal scrollbar mirror alongside the standard table container for effortless navigation through wide datasets.
* **📂 Local File Upload or Raw Paste:** Easily upload `.csv` or `.txt` files via the file picker.
* **🏷️ SEO & Schema.org Ready:** Fully optimized with built-in JSON-LD schema markup and semantic author meta tags.

---

## 🚀 Getting Started

### Prerequisites
All you need is a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari) and an internet connection to load the Tailwind CSS CDN.

### Running Locally
1. Clone this repository or download the `index.html` file.
2. Double-click `index.html` to open it directly in your browser, or serve it locally using any static file server:
   ```bash
   # Using Python
   python3 -m http.server 8000

   # Using Node.js (npx)
   npx serve
   ```

---

## 🛠️ Tech Stack

* **HTML5 / CSS3** (Semantic layout and custom styling)
* **Tailwind CSS v3** (Utility-first CSS framework via CDN with custom Tailwind configuration)
* **Vanilla JavaScript** (Zero-dependency DOM manipulation, custom CSV parsing engine, and clipboard API integration)

---

## 👤 Author & Credits

* **Author:** [Muhammad Tharif Zhafran Aziz (Thorif Zhafran)](https://thorifzhafran.com)
* **Publisher:** [Webinesia](https://webinesia.com)
* **GitHub:** [@thorifzhafran](https://github.com/thorifzhafran/)
* **LinkedIn:** [thorifzhafran](https://www.linkedin.com/in/thorifzhafran)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
