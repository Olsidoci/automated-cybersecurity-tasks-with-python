# 🔐 IP Address Access Control Automation

As a security analyst, managing IP access lists is a common task. In this project, I will show you how to automate the process of updating an "allow list" of IPs using Python.

## 📌 Scenario
You're maintaining a file (`allow_list.txt`) of IP addresses with access to sensitive data. Over time, some IPs need to be revoked. This script reads the file, removes disallowed IPs, and updates the list automatically.

## 📂 Files
- `allow_list.txt`: Contains the original list of allowed IPs.
- `access_control.ipynb`: Google Colab notebook that performs automated removal.
- `access_control.py`: Script version for local use.

## 💻 Key Concepts
- File I/O with Python (`read()`, `write()`)
- String manipulation
- Conditional filtering
- Function definition



