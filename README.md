# OWASP Juice Shop Security Testing

## Overview
Performed web application security testing on OWASP Juice Shop to identify common web vulnerabilities and understand practical exploitation techniques.

## Objectives
- Understand SQL Injection attacks
- Practice request interception using Burp Suite
- Analyze HTTP requests and responses
- Learn authentication bypass techniques

## Tools Used
- Burp Suite
- OWASP Juice Shop
- Kali Linux
- Chromium Browser

## Vulnerabilities Tested
- SQL Injection
- Authentication Bypass
- Input Validation Issues

## SQL Injection Demonstration
Used Burp Suite to intercept login requests and modified the email parameter with SQL Injection payloads to bypass authentication.

### Example Payload
```sql
' OR 1=1--
```

## Screenshots

### OWASP Juice Shop Environment
![Juice Shop](/juice-shop-home.png.png)

### Burp Suite Request Interception
![Burp Suite](/burp-suite-sql-injection.png.png)

### Request Analysis
![Request Analysis](/request-analysis.png.png)

## Learning Outcomes
- HTTP request manipulation
- Web application vulnerability analysis
- Authentication security concepts
- Practical use of Burp Suite

## Disclaimer
This project was performed in a legal lab environment (OWASP Juice Shop) for educational and learning purposes only.
