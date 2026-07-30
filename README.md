## Overview
Task 2 focuses on setting up a functional penetration testing lab and deploying Damn Vulnerable Web Application (DVWA) inside an isolated environment. This setup forms the foundation for all exploitation and web‑security testing in later tasks.

## Objectives
Configure Kali Linux as the attacker machine

Deploy DVWA as the vulnerable target

Install and configure Apache2 and MariaDB

Verify DVWA functionality

Ensure the lab is fully isolated and operational

## Environment
Attacker Machine: Kali Linux

Target Application: DVWA

Web Server: Apache2

Database Server: MariaDB

Browser: Firefox

Network Mode: Host‑Only / NAT (isolated)

## Activities Completed
## 1. Kali Linux Lab Setup
Installed Kali Linux in VirtualBox/VMware

Configured network isolation

Verified connectivity between attacker and target machines

## 2. DVWA Deployment
Installed Apache2 and MariaDB

Placed DVWA files under /var/www/html/dvwa

Created DVWA database and user

Updated DVWA configuration file (config.inc.php)

Initialized DVWA database tables

## 3. DVWA Verification
Accessed DVWA through browser

Logged in using default credentials

Set DVWA security level to Low

Verified modules such as SQL Injection load correctly

## Evidence
All screenshots for Task 2 are stored in the Task2_Screenshots directory.

Included screenshots:

DVWA Login Page

DVWA Dashboard

DVWA Security Level (Low)

DVWA SQL Injection Module

## Notes
A summary of installation steps and verification details is included in:


NovaShyld_Task_2/
│
├── Task2_Notes.md
│
└── Task2_Screenshots/
    ├── Kali Linux_Login_Page.png
    ├── DVWA_Login_Page.png
    ├── DVWA_Dashboard.png
    ├── DVWA_Security_Level_Low.png
    └── DVWA_SQL_Injection_Module.png
## Status
Task 2 successfully completed.
DVWA is fully functional and ready for reconnaissance and enumeration activities in Task 3.
