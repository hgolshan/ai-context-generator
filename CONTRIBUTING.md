# Contributing to AI Context Profile Generator

First off, thank you for considering contributing to the **AI Context Profile Generator**! 🎉 

This project aims to make AI tools more effective and tailored for professionals across various industries. Whether you want to translate the UI into your native language, add industry-specific presets, or refine prompt templates, your help is welcome!

---

## 📜 Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [1. Adding Translations (Multi-lingual Support)](#1-adding-translations-multi-lingual-support)
  - [2. Adding Role & Discipline Presets](#2-adding-role--discipline-presets)
  - [3. Improving System Prompt Templates](#3-improving-system-prompt-templates)
- [Development Workflow](#development-workflow)
- [Submitting a Pull Request (PR)](#submitting-a-pull-request-pr)

---

## 🤝 Code of Conduct

Please help us keep this project open, welcoming, and inclusive. Treat all contributors with respect regardless of experience level, background, or domain expertise.

---

## 💡 How Can I Contribute?

### 1. Adding Translations (Multi-lingual Support)
We aim to make this tool accessible globally. Translations are stored as modular JSON objects under the `/locales` folder (e.g., `locales/en.json`, `locales/de.json`, `locales/fa.json`).

To add a new language:
1. Duplicate `locales/en.json` and rename it using the appropriate ISO 639-1 code (e.g., `fr.json` for French, `es.json` for Spanish).
2. Translate all string values (do **not** change the JSON keys).
3. Add the new language option to the language selection dropdown in `index.html`.

---

### 2. Adding Role & Discipline Presets
We want pre-filled context presets for as many fields as possible (e.g., IT Systems & Networking, Electrical Engineering, Software Engineering, Civil Engineering, ESL Practice, Project Management).

To add a new preset button/template:
1. Define the role title, typical tools/tech stack, preferred tone, and common domain constraints.
2. Add the preset configuration into `app.js` (or the preset mapping section in `index.html`).
3. Ensure the preset adheres to real-world practices for that discipline (e.g., referencing relevant standards like ISO, IEEE, or specific OS/tool environments).

---

### 3. Improving System Prompt Templates
If you have discovered a high-leverage prompt structure or custom instruction layout that yields better results in ChatGPT, Claude, or Gemini:
* Open an issue discussing your proposed changes.
* Provide a **Before vs. After** example showing how the updated output improves AI responses.

---

## 🛠️ Development Workflow

Because this project is a zero-dependency static application built with pure HTML/CSS/JS, getting started is straightforward:

1. **Fork the Repository:** Click the **Fork** button at the top right of the page.
2. **Clone Your Fork:**
   ```bash
   git clone [https://github.com/hgolshan/ai-context-generator.git](https://github.com/hgolshan/ai-context-generator.git)
   cd ai-context-generator
3. **Make Your Changes:** Edit index.html, style.css, or locale files directly.

4. **Test Locally:** Open index.html in any modern web browser to test your changes.

###🚀 Submitting a Pull Request (PR)

1. Create a descriptive branch for your feature:
  git checkout -b feature/add-german-translation

2. Commit your changes with a clear message:
  git commit -m "feat: add German translation (de.json)"

3. Push the branch to your fork:
  git push origin feature/add-german-translation

4. Open a **Pull Request** against the main branch of hgolshan/ai-context-generator.

5. Briefly describe your changes and link any relevant issues.

Thank you for helping build a better tool for the community! 🚀
