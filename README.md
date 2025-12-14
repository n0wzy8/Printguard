# printguard 🛡️

**printguard** is a lightweight, dependency-free Python library that helps prevent
accidental exposure of sensitive information such as **passwords, API keys,
tokens, and JWTs** when printing data during development or debugging.

It is designed to be simple, fast, and safe to use in any Python project.

This library is developed and maintained by **WupSoftware**.

---

## ✨ Features

- Automatically masks common secrets (passwords, tokens, API keys, JWTs)
- Recursively protects dictionaries, lists, and JSON strings
- Zero third-party dependencies
- Optional override of Python’s built-in `print()` function
- Context manager for scoped protection
- Support for custom masking patterns using regular expressions

---

## 📦 Installation

```bash
pip install printguard
