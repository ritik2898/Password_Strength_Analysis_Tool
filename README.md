# 🔐 Password Strength Analysis Tool

A powerful and context-aware password strength analyzer built with Python. This tool simulates real-world cracking tactics by evaluating entropy, detecting common patterns, and identifying the use of personal information in passwords. It also supports bulk password analysis, strong password generation, and secure report handling.

---

## 🚀 Features

- **Entropy-Based Strength Estimation**
  - Calculates password entropy to measure true randomness and strength.
  
- **Pattern Recognition**
  - Detects repeated characters, sequences, and common keyboard patterns.

- **Personal Info Checks**
  - Flags passwords containing names, birthdates, or emails.

- **File-Based Scanning**
  - Analyzes `.txt` or `.csv` files of passwords.
  - Redaction and SHA-256 encryption support.
  - Flags duplicates and weak entries.

- **Human-Readable Feedback**
  - Provides actionable suggestions and crack time estimates.

- **Strong Password Generator**
  - Generates secure passwords using uppercase, lowercase, numbers, and symbols.

- **CLI Interface**
  - Menu-driven terminal utility with intuitive user prompts.

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/password-strength-analysis-tool.git
cd password-strength-analysis-tool
python Password_tool_.py
