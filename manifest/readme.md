
## 📄 Files in `/manifest/`

| File                          | Format                  | Purpose                                                                 | Best For                          | Git Diffs? |
|-------------------------------|-------------------------|-------------------------------------------------------------------------|-----------------------------------|------------|
| `freedom-framework.odt`       | **ODT** (OpenDocument Text) | **Main master source file** – the official editable document            | Editing in LibreOffice            | No (binary) |
| `freedom-framework.fodt`      | **FODT** (Flat OpenDocument Text) | Flat XML version of the document                                        | Collaboration & reviewing changes | **Yes** (readable) |
| `freedom-framework.pdf`       | **PDF**                 | Clean, fixed-layout version for reading and sharing                     | Final reading, printing, distribution | No (binary) |

### Quick Explanation

- **`freedom-framework.odt`**  
  This is the **primary source file**.  
  It is the standard OpenDocument Format (ISO/IEC 26300).  
  You should do all editing in this file using LibreOffice.

- **`freedom-framework.fodt`**  
  This is the same document, but saved as a single, uncompressed XML file.  
  Git can show **line-by-line differences**, making it much easier for collaborators to review changes.  
  Generated automatically from the `.odt` file.

- **`freedom-framework.pdf`**  
  A clean, read-only version optimized for viewing and sharing.  
  Best for readers who just want to read the Framework without editing.  
  Also generated automatically.

**Workflow Recommendation:**
- Edit → `freedom-framework.odt`
- Review changes → look at the `.fodt` in Pull Requests
- Read / Share → use the `.pdf`
