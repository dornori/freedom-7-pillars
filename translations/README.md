# 🌐 Translations Directory

## ⚠️ IMPORTANT: DO NOT EDIT FILES IN THIS FOLDER DIRECTLY

This directory contains **auto-generated translations** from the master English documents.

### 📌 Source of Truth

- **Master Documents:** Located in `/manifest` folder (English only)
- **This Folder:** Contains machine-generated translations for all languages

### 🔄 How It Works

1. English documents are edited in `/manifest/*.odt`
2. GitHub Actions automatically:
   - Converts English ODT → PDF + FODT
   - Generates translations to this folder
   - Creates PDF + FODT for each translation

### 📁 Structure
translations/
├── Language1/ # Translations for Language 1
├── Language2/ # Translations for Language 2
├── Language3/ # Translations for Language 3
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
1. Workflow converts English ODT → PDF + FODT
2. Workflow triggers translations for all language folders
3. All translation files update automatically

### 📝 Requesting New Languages

To add a new language:
1. Create a GitHub issue with the language request
2. The team will add the language to the workflow
3. **DO NOT** manually create language folders

### 🔍 Viewing Translations

- **PDF files:** Human-readable, download and view
- **FODT files:** Machine-readable XML, view diff on GitHub

### ❓ Questions?

Contact the documentation team - do not edit files directly!

---

**Remember:** This folder is automatically managed. Your edits will be overwritten!

