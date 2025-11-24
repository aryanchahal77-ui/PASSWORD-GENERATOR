# 🔒 Secure Password Generator

A Python script utilizing the `secrets` module to generate **cryptographically secure, randomized passwords**. The generator allows users to customize the password length and the inclusion of specific character types (uppercase, lowercase, digits, and symbols), ensuring the generated password meets complex security requirements.

## ✨ Features

* **Cryptographically Secure:** Uses Python's built-in `secrets` module, which is suitable for generating data for security-sensitive contexts, such as passwords, authentication tokens, and keys.
* **Guaranteed Complexity:** Ensures that the generated password includes **at least one character** from every selected character set (e.g., if you select uppercase and digits, the password will be guaranteed to contain at least one uppercase letter and one digit).
* **Customizable:** Users can define the password length (8 to 32 characters) and select which character types to include.
* **Command-Line Interface (CLI):** Provides an interactive interface for easy password generation.

## 🛠️ Requirements

* Python 3.6+ (Standard library modules `secrets` and `string` are used, no external dependencies).

## 🚀 How to Run

### 1. Save the Code

Save the provided Python code into a file named `password_generator.py`.

### 2. Execute from Terminal/CLI

Run the script directly from your terminal:

```bash
python password_generator.py

