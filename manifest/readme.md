## 📄 Files in `/manifest/`

This folder contains the core official documents of **The FREEDOM Framework**.

| File                          | Format                  | Purpose                                                                 | Best For                          | Git Diffs? |
|-------------------------------|-------------------------|-------------------------------------------------------------------------|-----------------------------------|------------|
| [`freedom-framework.odt`](https://github.com/dornori/freedom-7-pillars/tree/main/manifest/freedom-framework.odt) | **ODT** (OpenDocument Text) | **Main master source file** – the official editable document            | Editing in LibreOffice            | No (binary) |
| [`freedom-framework.fodt`](https://github.com/dornori/freedom-7-pillars/tree/main/manifest/freedom-framework.fodt) | **FODT** (Flat OpenDocument Text) | Flat XML version of the document                                        | Collaboration & reviewing changes | **Yes** (readable) |
| [`freedom-framework.pdf`](https://github.com/dornori/freedom-7-pillars/tree/main/manifest/freedom-framework.pdf) | **PDF**                 | Clean, fixed-layout version for reading and sharing                     | Final reading, printing, distribution | No (binary) |

### Quick Explanation

- **`freedom-framework.odt`**  
  This is the **primary source file**.  
  It follows the official OpenDocument Format (ISO/IEC 26300).  
  **All editing should be done in this file** using LibreOffice.

- **`freedom-framework.fodt`**  
  This is the same document saved as a single, uncompressed XML file.  
  Git can display **line-by-line differences**, making it much easier for collaborators to review changes.  
  It is automatically generated from the `.odt` file.

- **`freedom-framework.pdf`**  
  A clean, read-only version optimized for viewing and sharing.  
  Best for readers who want to read the Framework without editing it.  
  Also automatically generated from the `.odt` file.

### Workflow Recommendation

- **Edit** → `freedom-framework.odt`
- **Review changes** → Check the `.fodt` file (best for seeing diffs)
- **Read / Share** → Use the `.pdf` version

All files in the `manifest/` folder are kept in sync via automation.
