<p align="center">
  <img src="./logo.svg" alt="Call Log Explorer" width="120" />
</p>

<h1 align="center">📞 Call Log Explorer</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Plivo-15C35B?style=flat&logo=plivo&logoColor=white" alt="Plivo" />
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat" alt="License" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat" alt="PRs Welcome" />
</p>

<p align="center"><strong>Drag-and-drop Plivo CDR explorer — parse, filter, visualize, and export call logs in your browser.</strong></p>

---

## ✨ Features

- 📤 **Drag & Drop Upload** — Drop Plivo CDR JSON or CSV files directly onto the page
- 📋 **Smart Table** — Auto-detects CDR fields (direction, cost, duration, outcome) with color-coded badges
- 🔍 **Full-Text Search** — Filter across all fields instantly
- 📊 **Analytics Charts** — Call outcomes pie chart, direction breakdown, duration histogram (Canvas API)
- 📥 **CSV Export** — Export filtered results back to CSV
- 🎨 **Dark Theme** — Pleasant dark UI with orange accent
- ⚡ **Zero Dependencies** — Single file, no frameworks or build tools

## 🚀 Quick Start

```bash
git clone https://github.com/soumendrak/call-log-explorer.git
cd call-log-explorer
open index.html
```

Drag a Plivo CDR JSON or CSV file onto the page. That's it.

## 📁 Project Structure

```
call-log-explorer/
├── index.html      # The entire app
├── logo.svg        # App logo
├── LICENSE         # MIT
└── README.md       # You are here
```

## 🏗 Architecture

Single-file vanilla HTML/CSS/JS. Charts drawn with Canvas API. No frameworks, no CDNs, no build tools.

## 🤝 Contributing

PRs welcome! Keep the zero-dependency constraint.

## 📄 License

MIT © 2026 Soumendra
