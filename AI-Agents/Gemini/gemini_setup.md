# 🤖 Gemini CLI Setup Guide

A quick reference for installing and using Gemini CLI from the terminal.

---

## 📋 Requirements

* Node.js
* npm
* Google account

Check Node.js:

```bash
node --version
```

Check npm:

```bash
npm --version
```

---

## 📦 Installation

Install Gemini CLI globally:

```bash
npm install -g @google/gemini-cli
```

Check installation:

```bash
gemini --version
```

---

## 🚀 Start Gemini CLI

Run:

```bash
gemini
```

Follow the authentication instructions shown in the terminal.

---

## 🔑 Authentication

Depending on the current Gemini CLI authentication options, you may authenticate using your Google account or an API key.

For API-key based authentication, configure the appropriate environment variable according to the current Gemini CLI documentation.

---

## 💻 Using Gemini in a Project

Open your project folder:

```bash
cd your-project
```

Then start Gemini:

```bash
gemini
```

Gemini can then be used as a coding assistant inside the project environment.

---

## 🛠️ Updating Gemini CLI

```bash
npm update -g @google/gemini-cli
```

---

## 🗑️ Uninstall

```bash
npm uninstall -g @google/gemini-cli
```

---

## 📌 Notes

Keep Node.js and Gemini CLI updated.

Never expose API keys or other credentials in source code or Git repositories.

Always check the official Gemini CLI documentation for the latest installation and authentication instructions.
