# ⚡ DocConverter

A free, privacy-first document conversion tool that runs entirely in your browser. No file uploads, no servers, no sign-up.

## ✨ Features

| Conversion | Description |
|---|---|
| 🖼️ PDF → PNG | Renders every PDF page as a PNG image |
| 📄 Image → PDF | Embeds PNG/JPG into a real PDF file |
| 📑 Word → PDF | Converts DOCX documents to PDF |
| 📝 PDF → Word | Extracts PDF text into a .docx file |
| 🗜️ Compress | Reduces file size for PDFs and images |

## 🔒 Privacy

All processing happens locally in your browser using these open-source libraries:
- [pdf.js](https://mozilla.github.io/pdf.js/) — PDF rendering
- [pdf-lib](https://pdf-lib.js.org/) — PDF creation & compression
- [mammoth.js](https://github.com/mwilliamson/mammoth.js) — DOCX reading
- [docx.js](https://docx.js.org/) — DOCX creation
- [browser-image-compression](https://github.com/Donaldcwl/browser-image-compression) — Image compression

## 🚀 Deploy

### Netlify Drop (fastest)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the `index.html` file
3. Get a live URL instantly

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages → Source → main branch**
3. Live at `https://yourusername.github.io/repo-name`

## 🛠️ Local Use

Just open `index.html` in any modern browser. Requires an internet connection to load the conversion libraries from CDN.

## License

MIT — free to use, modify, and distribute.
