# 🤖 OpenAI Codex CLI Setup Guide

A quick reference for installing and using OpenAI Codex CLI from the terminal.

---

## 📋 Requirements

* Node.js
* npm
* OpenAI account

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

Install Codex CLI globally:

```bash
npm install -g @openai/codex
```

Check installation:

```bash
codex --version
```

---

## 🚀 Start Codex

Open your project directory:

```bash
cd your-project
```

Then run:

```bash
codex
```

Follow the authentication instructions shown in the terminal.

---

## 🔑 Authentication

Codex CLI may provide interactive authentication options depending on the current version and account setup.

If API-key authentication is used, configure the required credentials according to the current OpenAI documentation.

Never put API keys directly inside source code.

---

## 💻 Using Codex in a Project

Navigate to your project:

```bash
cd your-project
```

Start Codex:

```bash
codex
```

Codex can then assist with coding, debugging, refactoring, and understanding files within the project.

---

## 🔄 Updating Codex CLI

```bash
npm update -g @openai/codex
```

---

## 🗑️ Uninstall

```bash
npm uninstall -g @openai/codex
```

---

## 📌 Notes

Codex CLI features, authentication methods, and installation requirements may change over time.

Check the official OpenAI documentation for the latest information.

Never commit API keys, access tokens, passwords, or other sensitive credentials to GitHub.
