# 🧰 Tools Directory

This folder contains tools used for developing and running **Puter**.  
Each folder inside `/tools` is an **npm workspace**, so it can have its own `package.json` and dependencies.

---

## 📚 Table of Contents
- [Overview](#overview)
- [Scripts](#scripts)
- [Utilities](#utilities)
- [Libraries](#libraries)
- [How to Contribute](#how-to-contribute)
- [Contact](#contact)

---

## 🧠 Overview
This directory includes small helper scripts, utilities, and libraries that make development, testing, and documentation easier.

Each tool is built as a mini npm project inside `/tools` and can run independently.

---

## ⚙️ Scripts

### 🏠 `run-selfhosted.js`
Used to start a **local version** of Puter for development.  
- Checks your Node.js version.  
- Loads modules for local file storage.  
- Starts the app locally.

**Run:**
```bash
node tools/run-selfhosted.js
