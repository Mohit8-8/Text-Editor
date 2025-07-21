# 📝 Rich Text Editor – Web-Based WYSIWYG Editor

A fully functional, responsive **Rich Text Editor** built using HTML, CSS, and JavaScript. This project offers a WYSIWYG (What You See Is What You Get) editing experience with various formatting options, ideal for note-taking, blogging, or document-style editing directly in the browser.

## ✨ Features

- 🅱 Bold, subscript, superscript formatting
- 📃 Ordered and unordered lists
- 🔄 Undo / Redo functionality
- 🔗 Add and remove hyperlinks
- 📐 Text alignment (Left, Center, Right, Justify)
- ↔️ Indent / Outdent control
- 🖍 Font selection and size control
- 🎨 Font color and background highlighter
- 📦 Clean and responsive interface with modern icons

## 🛠 Tech Stack

- **HTML5** – Structure and layout
- **CSS3** – UI styling
- **JavaScript (ES6)** – Core logic and formatting behavior
- **Font Awesome 6** – Toolbar icons

## 💡 How It Works

- Uses `document.execCommand()` to apply formatting commands to a `contenteditable` `div`.
- Dynamically populates font and size dropdowns on load.
- Active formatting buttons get visually highlighted for better UX.
- Fully client-side, no dependencies other than Font Awesome CDN.

## 🚀 Potential Add-ons

- Save/Export as `.txt` or `.docx`
- Word count / character count tracker
- Cloud storage integration (e.g., Firebase)
- Theming support (Light/Dark mode)
