

This project is a robust **RTF (Rich Text Format) to JSON Converter**, built using Python. It extracts structured data—including fonts, styles, headers, tables, and footnotes—from RTF files and outputs them in a clean JSON format. It also includes logging and a UI for easier file selection and conversion.

---

📌 Features

- 📄 Extracts:
  - Font and color tables
  - Page headers and titles
  - Table column headers and rows
  - Footnotes and source data
  - Style attributes (font, size, color, bold, italic, underline, etc.)
- 🔍 Uses configurable **regex expressions and tags** via a `config.ini` file.
- 📂 Batch processing for multiple `.rtf` files.
- 🧪 Built-in logging system for success and error tracking.
- 🖥️ User interface integration using `tkinter`.

---

## 🛠️ Tech Stack

- **Python 3**
- `re` (regex)
- `json`
- `configparser`
- `datetime`
- `tkinter` (for UI)
- Modular architecture

---

