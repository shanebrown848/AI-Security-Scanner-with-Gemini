# 🔐 AI Security Scanner with Gemini

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Security](https://img.shields.io/badge/Security-AppSec-red)
![AI](https://img.shields.io/badge/AI-Gemini-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![NextWork](https://img.shields.io/badge/Built%20With-NextWork-purple)

An AI-powered vulnerability scanner built with Python and Google Gemini. This tool analyzes source code for common security flaws and returns structured findings with severity ratings and color-coded output.

Built as part of the NextWork AI Security Audit project.

---

## 🚀 Overview

This project demonstrates how artificial intelligence can be used to assist with application security reviews. The scanner uses the Gemini API to analyze Python files and detect vulnerabilities such as:

* SQL Injection
* Hardcoded credentials
* Weak cryptography
* Command injection
* Insecure password handling

Each finding includes:

* Vulnerability type
* Severity rating (Critical, High, Medium, Low)
* Human-readable explanation
* Color-coded output for fast triage

This simulates how modern security tools perform automated pre-production code reviews.

---

## 🛠 Tech Stack

* Python
* Google Gemini API
* python-dotenv
* Colorama
* OS

---

## 📂 Project Structure

```
.
├── scanner.py          # Main AI security scanner
├── vulnerable.py       # Sample vulnerable code for testing
├── documentation.md    # Full project documentation
├── .env                # API key configuration
├── requirements.txt    # Dependencies
└── README.md
```

---

## 📘 Documentation

For full technical documentation, architecture breakdown, prompt design, and security logic:

➡️ **See `documentation.md`**

This includes:

* Prompt engineering design
* Severity classification logic
* Scanner workflow
* File scanning process
* AI security methodology

---

## ⚙️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-security-scanner.git
cd ai-security-scanner
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Create your environment file

Create a `.env` file in the project root:

```
GOOGLE_API_KEY=your_gemini_api_key_here
```

---

## ▶️ Usage

### Scan a file for vulnerabilities

```bash
python scanner.py vulnerable.py
```

The scanner will:

* Send the file to Gemini
* Analyze for security issues
* Return structured findings
* Display color-coded severity levels

Example output:

```
[CRITICAL] SQL Injection
[HIGH] Hardcoded Credentials
[MEDIUM] Weak Hashing Algorithm
```

---

## 🎯 Features

* AI-powered vulnerability detection
* Severity classification (Critical, High, Medium, Low)
* Color-coded terminal output
* Real file scanning
* Structured security reporting

---

## 🔍 Why This Matters

Modern security teams use automated scanners to detect vulnerabilities before deployment. This project mirrors how real-world tools:

* Review source code
* Identify attack vectors
* Prioritize remediation
* Prevent insecure releases

This scanner demonstrates practical AppSec automation using AI.

---

## 🧠 What I Learned

* Secure API key handling with environment variables
* Prompt engineering for security analysis
* Structured AI responses for automation
* File-based static code analysis
* Security severity classification
* Building AI-assisted developer tools

---

## 📌 Future Improvements

* Web dashboard interface
* Batch directory scanning
* Export reports to JSON or PDF
* CI/CD pipeline integration
* Expanded language support

---

## 👨‍💻 Author

**Shane Brown**
Web Developer | Security Engineer | Founder of Sinister Gate Designs

Email: [shanebrown848@gmail.com](mailto:shanebrown848@gmail.com)

---

## 🏁 Project Link

NextWork Project:
[http://learn.nextwork.org/projects/ai-security-audit](http://learn.nextwork.org/projects/ai-security-audit)

---

## ⭐ If you like this project

Give it a star and follow for more security and cloud builds.

---

Built with discipline, curiosity, and a security-first mindset.
