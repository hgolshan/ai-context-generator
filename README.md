# 🤖 AI Context Profile Generator

An interactive, open-source tool designed to help professionals create precise, high-leverage context profiles and custom instructions for AI assistants like ChatGPT, Claude, and Gemini.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 📌 Project Overview

Most users interact with AI models using default settings, resulting in generic, overly cautious, or unnecessarily verbose responses. While modern AI models perform significantly better when given background context, crafting effective system instructions manually can be time-consuming.

**AI Context Profile Generator** solves this by providing a lightweight, interactive web interface that asks targeted questions about your role, domain tools, technical expertise, and preferred output formats, then automatically generates a tailored, copy-pasteable context profile to drop directly into your AI settings.

---

## ✨ Features

* **⚡ Quick Setup:** Generate a custom context profile in under two minutes.
* **🎯 Role-Agnostic & Modular:** Tailored prompts for IT, Systems & Network Engineering, software development, civil/mechanical/electrical engineering, language learning, and management.
* **🔒 Privacy-Focused:** 100% client-side execution—no personal data or generated text is sent to external servers or databases.
* **🌍 Multi-lingual Ready:** Modular JSON structure designed for community localization and multi-language support.
* **🌐 Web-Based UI:** Built with zero dependencies (pure HTML/CSS/JS)—works natively on GitHub Pages.

---

## 🚀 Live Demo & How to Use

Try the generator live on [GitHub Pages](https://your-username.github.io/ai-context-generator/).

### Quickstart Guide:
1. Open the interactive form on the web page.
2. Enter your primary role, key tools/technologies, preferred communication style, and rules/constraints (e.g., *"skip introductions", "provide complete configs"*).
3. Click **Generate Profile**.
4. Click **Copy to Clipboard**.
5. Paste the output into your AI platform's custom instruction field (e.g., ChatGPT's *Custom Instructions*, Claude's *Project Instructions*, or Gemini's user preferences).

---

## 🛠️ Local Development & Deployment

Because this repository contains a zero-dependency static web app, no build steps (`npm`, `webpack`, etc.) are required.

### Running Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/ai-context-generator.git](https://github.com/your-username/ai-context-generator.git)
