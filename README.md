# 🔍 Open Directory Finder

A powerful, modern web tool for finding direct download links from open directories across the web. Uses advanced search operators (Google Dorking) to locate files on public servers.

![Dark Mode](https://img.shields.io/badge/Theme-Dark%20%2F%20Light-7c3aed)
![Single File](https://img.shields.io/badge/Deploy-Single%20HTML%20File-3b82f6)
![No Backend](https://img.shields.io/badge/Backend-Not%20Required-10b981)

---

## ✨ Features

### 🎨 Modern UI
- **Dark mode by default** with glassmorphism design
- **Light/Dark theme toggle** with localStorage persistence
- **Fully responsive** - works on desktop, tablet, and mobile
- **Smooth animations** and micro-interactions

### 🔎 Search Engines
| Engine | Privacy | Notes |
|--------|---------|-------|
| Google | Low | Best results |
| DuckDuckGo | High | Privacy-focused |
| Bing | Low | Good alternative |
| Yandex | Medium | Russian search engine |
| Startpage | High | Anonymous Google |
| SearX | High | Meta search engine |
| FilePursuit | Medium | Dedicated file search |

### ⚙️ Advanced Options
- **Toggle query modifiers** - Enable/disable `intitle:index.of`
- **Exclusion filters** - Remove common non-download pages
- **Site filter** - Limit search to specific domain
- **Custom file extensions** - Add your own (e.g., `srt,sub,ass`)

### 📁 File Type Presets
- 🎬 Movies / TV Shows
- 📚 Books / eBooks
- 🎵 Music / Audio
- 💿 Software / Games / ISO
- 🖼️ Images

### 🚀 Productivity Features
- **Search History** - Last 10 searches saved locally
- **Open All Engines** - Search multiple engines with one click
- **Loading states** - Visual feedback during search

---

## 🛠️ Installation

No installation required! Just download and open.

```bash
# Clone the repository
git clone https://github.com/Daivik1520/opendirectory-finder.git

# Open in browser
open opendirectory-finder/index.html
```

Or simply download `index.html` and double-click to open.

---

## 📖 Usage

1. **Select file type** from the dropdown (or leave as "All Files")
2. **Choose search engine** (Google by default)
3. **Enter your search query** (e.g., `The.Office.S01`)
4. **Click Search** or press Enter
5. Results open in a new tab

### Advanced Usage

Click **"Advanced Options"** to:
- Toggle `intitle:index.of` operator
- Toggle exclusion filters
- Add a site restriction (e.g., `example.com`)
- Add custom file extensions

---

## 🔧 How It Works

The tool constructs search queries using Google Dorking techniques:

```
your_query +(mkv|mp4|avi) intitle:index.of -inurl:(jsp|pl|php|html)
```

This finds:
- Pages with "Index of" in the title (directory listings)
- Files matching your extensions
- Excludes dynamic pages and known spam sites

---

## 📱 Screenshots

| Dark Mode | Light Mode |
|-----------|------------|
| Modern glassmorphism UI | Clean light theme |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**. The developer is not responsible for how you use this tool. Always respect copyright laws and only download content you have the right to access.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Daivik Reddy**

- 📧 Email: [daivik1520@gmail.com](mailto:daivik1520@gmail.com)
- 📱 Phone: +91 7995456600
- 🐙 GitHub: [@Daivik1520](https://github.com/Daivik1520)

---

<p align="center">
  Made with ❤️ by Daivik Reddy
</p>
