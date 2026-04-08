# Multi-Factor Authentication (MFA) System

## Overview

Designed and implemented a secure multi-factor authentication system to enhance user authentication security. The project demonstrates how MFA protects against brute force attacks, credential compromise, and unauthorized access using OTP-based verification.

---

## Objectives

* Identify weaknesses in password-based authentication
* Implement OTP-based multi-factor authentication
* Simulate real-world attack scenarios
* Prevent unauthorized access using MFA
* Improve session security

---

## Tools & Technologies

* Burp Suite
* DVWA (for attack simulation)
* Python (OTP logic simulation)
* Web Application (Login system)

---

## Methodology

### 1. Vulnerability Analysis (Without MFA)

* Tested login system without MFA
* Performed brute force attacks using Burp Suite

### 2. MFA Implementation

* Added OTP-based authentication layer
* Implemented email-based and authenticator-based OTP

### 3. Attack Simulation

* Brute force attack on login
* Credential compromise test
* OTP brute force attempt
* MFA bypass attempt

### 4. Security Fixes

* Implemented server-side validation
* Fixed session management issues
* Enforced OTP verification

---

## Key Findings

* Password-only systems are highly vulnerable
* MFA prevents unauthorized access even with stolen credentials
* OTP significantly reduces brute-force success
* Proper session management is critical


---

## Impact

* Prevents account takeover
* Protects against credential theft
* Reduces phishing attack impact
* Strengthens authentication security

---

## Mitigation / Security Benefits

* Multi-layer authentication
* Secure session handling
* OTP-based verification
* Improved access control

---

## Key Learning

* Importance of layered authentication
* Real-world attack prevention using MFA
* Role of OTP in security
* Fixing MFA bypass vulnerabilities

---

## Full Report

Detailed documentation available in: [report.pdf]
