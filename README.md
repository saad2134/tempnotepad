# 📝 Temp Notepad

**Temp Notepad** is a lightweight, privacy-focused notepad app built as a client-side web application. It's designed for quickly jotting down temporary notes directly in your browser—no signups, no syncing, no servers.

> ⚠️ **Important:** All notes are saved in your browser's **Local Storage**. Clearing your browser history, cache, or using Incognito/Private mode will **delete all notes**. Always back up important information manually.

---

## 🚀 Features

- ✅ **Client-side & Offline** — works completely without internet connection.
- ✅ **Zero Data Tracking** — your notes never leave your local device.
- ✅ **Instant Startup** — blazing-fast loading and smooth theme switching.
- ✅ **Persistent Notes** using Local Storage.
- ✅ **Download Individual Notes** — save any note as a .txt file.
- ✅ **Download All Notes** — export all notes as a single .zip file.
- ✅ **Import Notes** — import one or multiple .txt files in a single click.

---

## 📥 Getting Started

### 🔹 Option 1: Use via GitHub Pages
> 🌐 **Live Web App:** [Temp Notepad on GitHub Pages](https://saad2134.github.io/tempnotepad/)

### 🔹 Option 2: Run Locally
Open web/index.html directly in your browser or start a static server:
`ash
# Python
python -m http.server 8080 --directory web

# Node.js
npx serve web
`

---

## 📁 File Architecture

`	ext
tempnotepad/
├── .github/
│   ├── workflows/
│   │   └── static.yml    # GitHub Pages deployment workflow (deploys /web)
│   └── FUNDING.yml       # GitHub Sponsors, Buy Me a Coffee & NOWPayments
├── web/
│   ├── index.html        # Main application layout, JSON-LD Schema & GA4 tag
│   ├── icon.png          # App icon
│   ├── favicon.ico       # Favicon
│   ├── manifest.json     # PWA & mobile discoverability manifest
│   ├── robots.txt        # Search engine crawler directives
│   └── sitemap.xml       # XML sitemap
├── LICENSE               # License
└── README.md             # Project documentation
`

---

## 🛡️ Privacy & Security

- Your notes are stored **only on your device**.
- No cookies or server databases.
- 100% open-source and inspectable.

---

## ☕ Support & Sponsorship

If you find Temp Notepad helpful, consider supporting its development:
- **GitHub Sponsors**: [github.com/sponsors/saad2134](https://github.com/sponsors/saad2134)
- **Buy Me a Coffee**: [buymeacoffee.com/saad1inc](https://buymeacoffee.com/saad1inc)
- **NOWPayments (Crypto)**: [nowpayments.io/donation/saad1inc](https://nowpayments.io/donation/saad1inc)

---

## 📄 License & Attribution

© 2024 Note Taking App. Made by [Saad (@saad2134)](https://github.com/saad2134). Licensed under the [MIT License](./LICENSE).
