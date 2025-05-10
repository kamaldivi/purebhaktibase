# 📁 Shared Folder – PureBhaktiBase

This folder contains **shared resources, libraries, and configurations** that are used across different modules of the PureBhaktiBase project.

## ✨ Purpose

The `/shared` folder is designed to:

- 🛠️ **Centralize common code and assets**  
  (e.g., utility functions, data schemas, shared styles)

- 🗂️ **Avoid duplication** across:
  - `pdf-extraction`
  - `ai-agent`
  - `web-ui`

- 🔄 **Provide consistency** in data formats, naming conventions, and reusable logic.

---

## 📑 Current & Planned Contents

| 📁 **Subfolder / File**   | 📄 **Description**                                                        |
|--------------------------|----------------------------------------------------------------------------|
| `/data-models/`          | JSON/YAML schemas for structured data (e.g., chapter metadata, indexing)  |
| `/utils/`                | Common utility scripts (e.g., text cleaning, language detection)          |
| `/styles/` (optional)    | Shared CSS or design tokens for UI consistency                            |
| `/constants.py / .js`    | Project-wide constants (e.g., language codes, book IDs)                   |
| `/README.md`             | This documentation file                                                   |

---

## 🚀 Usage Example

- **Python (pdf-extraction or ai-agent):**
    ```python
    from shared.utils.text_cleaner import clean_text
    ```

- **Node.js (web-ui):**
    ```js
    const { cleanText } = require('../../shared/utils/textCleaner');
    ```

---

## ✅ Best Practices

- Keep shared modules **generic and reusable.**
- Update this README if you add new **subfolders or tools.**
- If a module becomes **too large or specific,** consider moving it back to its package.

---

✍️ *Last updated: [Month Year]*  
