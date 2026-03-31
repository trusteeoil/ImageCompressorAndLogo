# 🖼️ Image Compressor + Logo Overlay

A lightweight, browser-based tool for compressing images and adding a logo watermark — all done **locally with no uploads**.

---

## 🚀 Features

- 📦 Compress images to a target file size (KB)  
- 📏 Automatically resize images while keeping proportions  
- 🖼️ Add a logo to the bottom-right corner  
- 🎚️ Adjustable logo size, position, and margins  
- 💾 Remembers your logo in the browser (localStorage)  
- ⚡ Fully client-side — no server required  
- 🔒 No data leaves your computer  

---

## 🧰 How It Works

1. Select or drag in your main image  
2. Upload a logo (saved for future use)  
3. Adjust compression and logo settings  
4. Click **Render + Compress**  
5. Download the final image  

---

## 📸 Use Cases

- Blog images (WordPress optimization)  
- Product images for eCommerce  
- Watermarking images with branding  
- Reducing image sizes for faster websites  

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- Vanilla JavaScript  
- Canvas API  

> No frameworks, no dependencies.

---

## 🔐 Privacy & Security

- ✅ Runs entirely in your browser  
- ✅ No uploads or external requests  
- ✅ No tracking or analytics  
- ✅ Files never leave your device  

---

## ⚙️ Configuration Options

- **Max Width/Height** – Limits image dimensions  
- **Target Size (KB)** – Attempts to compress under this size  
- **Format** – JPG (smaller) or PNG (higher quality)  
- **Logo Scale** – Size relative to image  
- **Offsets & Margin** – Fine-tune logo placement  

---

## 💡 Notes

- JPG compression uses a binary search to find the best quality under your target size  
- PNG output does not compress as aggressively as JPG  
- Logo is stored in your browser using localStorage  

---

## 📦 Getting Started

Just open the HTML file in your browser:

```bash
# No installation needed
open index.html
```

Or simply double-click the file.

---

## 📄 License

MIT License — feel free to use and modify.

---

## 🙌 Contributing

Pull requests are welcome.  
If you have ideas for improvements, feel free to open an issue.

---

## ⭐ Optional Improvements

You could add:
- Screenshots or a demo GIF  
- A live demo link (GitHub Pages)  
- Before/after compression examples  
