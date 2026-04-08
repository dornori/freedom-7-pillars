# ODT to PDF + FODT Auto-Converter

This repository automatically converts OpenDocument Text (`.odt`) files to both PDF (human-readable) and FODT (machine-readable XML) formats whenever changes are pushed.

## 🚀 How It Works

When you push changes to any `.odt` file in a monitored folder, GitHub Actions automatically:
1. **Converts to PDF** - For human reading and sharing
2. **Converts to FODT** - For version control and diff checking
3. **Commits both files** back to the repository

## 📁 Monitored Folders

Currently monitored folders:
- `manifest/` - Manifest files
- `translations/Persian/` - Persian translations (with Persian font support)
- `translations/Spanish/` - Spanish translations

## 🛠️ Architecture

This uses a **parent-child workflow pattern**:
