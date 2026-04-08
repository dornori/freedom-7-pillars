# 📚 Translations Directory

## ⚠️ IMPORTANT: DO NOT EDIT FILES IN THIS FOLDER DIRECTLY

This directory contains **auto-generated translations** from the master English documents.

### 📌 Source of Truth

- **Master Documents:** Located in the `/manifest` folder (English only)
- **This Folder:** Contains machine-generated translations

### 🔄 How It Works

1. English documents are edited in `/manifest/*.odt`
2. GitHub Actions automatically:
   - Converts English ODT → PDF + FODT
   - Generates translations to this folder
   - Creates PDF + FODT for each translation

### 📁 Structure
translations/
├── Persian/ # فارسی - Persian translations
├── Spanish/ # Español - Spanish translations
├── French/ # Français - French translations
└── README.md # This file


### 🚫 What NOT to Do

- ❌ **DO NOT** edit files directly in this folder
- ❌ **DO NOT** manually add or remove files here
- ❌ **DO NOT** use this folder as a source for edits

### ✅ What TO Do

- ✅ Edit the **English master** in `/manifest/` instead
- ✅ Let the auto-conversion workflow handle translations
- ✅ Report translation errors to the documentation team

### 🤖 Automatic Workflow

When you push changes to `/manifest/*.odt`:
1. Workflow `convert-manifest.yml` triggers
2. Converts English ODT → PDF + FODT
3. Workflow `convert-persian.yml` triggers
4. Updates Persian translations automatically

### 📝 Requesting New Translations

To add a new language:
1. Create a GitHub issue with the language request
2. The team will add the language to the workflow
3. **DO NOT** manually create translation folders

### 🔍 Viewing Translations

- **PDF files:** Human-readable, download and view
- **FODT files:** Machine-readable XML, view diff on GitHub

### ❓ Questions?

Contact the documentation team - do not edit files directly!

---

**Remember:** This folder is automatically managed. Your edits will be overwritten!
