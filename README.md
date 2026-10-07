# Security Log Analysis & Suspicious Activity Detection

## 📌 Project Overview

This project is a cybersecurity system for analyzing security log data and detecting suspicious activities using predefined security rules.

The system processes security events such as failed logins, unusual login times, restricted resource access, repeated HTTP errors, multiple usernames from the same IP address, and flagged source IP addresses.

## 🎯 Objectives

- Analyze security log events.
- Detect suspicious user and network activities.
- Identify repeated failed login attempts.
- Detect restricted resource access.
- Identify suspicious IP addresses.
- Detect unusual login times.
- Generate security alerts with severity levels.

## 🛠️ Technologies Used

- Python
- Flask
- HTML
- CSS
- Log Analysis
- Cybersecurity Rule-Based Detection

## 🔍 Detection Rules

The system uses the following detection rules:

1. Multiple Failed Logins
2. Successful Login After Failures
3. Multiple Usernames From Same IP
4. Restricted Resource Access
5. High Request Frequency
6. Repeated HTTP Error Responses
7. Flagged Source IP
8. Unusual Login Time

## 📂 Project Structure

```text
Log-Analysis-Suspicious-Activity-Detection/
│
├── data/
│   └── sample_security.log
│
├── reports/
├── screenshots/
│
├── src/
│   ├── app.py
│   ├── analyzer.py
│   └── templates/
│       └── index.html
│
└── tests/
