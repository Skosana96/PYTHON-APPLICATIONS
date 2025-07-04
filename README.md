# 🧾 User Registration System

A simple and efficient Python-based system for registering users, storing user information securely, and validating input. Created by **Mthokozisi Skosana**.

---

## 🔍 Overview

This project is designed to handle user registration functionality, including:
- Capturing user details (username, email, password, etc.)
- Validating inputs (e.g. email format, password strength)
- Saving user data to a file or database
- (Optional) Checking for duplicate users

It can be used as a standalone application or integrated into larger systems.

---

## 🚀 Features

- 📥 User input via terminal or script
- 🔐 Password validation and masking
- 📁 Save data to local file (JSON, CSV, or SQLite)
- ✅ Duplicate email/username check
- 🔄 Easy to integrate into web apps or APIs

---

## 📁 Project Structure

```bash
user-registration/
├── src/
│   ├── __init__.py
│   └── register.py         # Core registration logic
├── data/
│   └── users.json          # Stored user data
├── tests/
│   └── test_register.py    # Unit tests
├── requirements.txt
├── main.py                 # Entry point script
└── README.md

