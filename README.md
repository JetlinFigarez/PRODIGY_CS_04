## 🛡️ PRODIGY_CS_04 — Cybersecurity Task 4: Simple Keylogger

    ⚠️ For Educational & Ethical Use Only
    🧠 Part of the PRODIGY_CS Cybersecurity Series
    🔍 Python | Pynput | Kali Linux | Virtual Environment (PEP 668 Safe)

## 📖 Overview

The objective of this task is to create a basic Python-based keylogger for authorized and ethical learning environments.
This implementation demonstrates how keystroke logging works at a low level using the pynput library, and emphasizes cybersecurity awareness, privacy, and proper boundaries.

## 🎯 Objectives

    🧠 Understand how input capturing works at the OS level.

    💻 Implement a basic keylogger in Python.

    📝 Log keyboard activity to a plain text file.

    ✅ Ensure ethical use and compliance with system safety using a virtual environment.

## ⚙️ Setup Instructions (Recommended: Virtual Environment)

To safely install dependencies without breaking system Python (especially on Kali Linux 2024+), use a virtual environment:
 
# 1. Clone the Repository

 git clone https://github.com/Jetlin Figarez/PRODIGY_CS_04_Simple-Keylogger.git
 cd PRODIGY_CS_04_Simple-Keylogger

# 2. Create & Activate a Virtual Environment

 python3 -m venv venv
 source venv/bin/activate

# 3. Install Required Dependencies

 pip install pynput

# 4. Run the Keylogger

 python keylogger.py

# Press keys in any application to log them. To stop the script, press Ctrl + C in the terminal.

## 📁 Project Structure
 File/Folder	Description
 keylogger.py	Main script that captures keystrokes
 keylog.txt	Output log file (generated at runtime)
 README.md	
 
# 🧪 Example Output

 Here’s what your keylog.txt might look like:

 h e l l o   [Key.space] w o r l d [Key.enter]
 
## ⚖️ Ethical Usage

This tool is for educational, research, and authorized penetration testing environments only.

## ✅ Use Cases:

    Educational labs

    Cybersecurity training environments

    Authorized testing with consent

## 🚫 Prohibited:

    Unauthorized surveillance

    Spying on others’ activity

    Deployment without permission

Violation of these terms may lead to legal consequences and goes against the ethics of cybersecurity practice.

## 🧠 Learning Outcomes

 By completing this task, learners gain:

    Practical understanding of input listeners in Python

    Awareness of keylogger behavior and its risks

    Familiarity with safe Python development practices on hardened systems (like Kali Linux)
