# OWASP-Juice-Shop-Security-Testing
Security assessment of OWASP Juice Shop using Kali Linux and Docker (Educational Purpose)

## Project Overview
This project demonstrates security testing of the OWASP Juice Shop vulnerable web application in a controlled lab environment using Kali Linux and Docker.

## Tools & Technologies
- Kali Linux
- Ubuntu Server
- Docker
- OWASP Juice Shop
- VirtualBox

## Environment Setup
- Attacker Machine: Kali Linux
- Target Machine: Ubuntu Server
- Application: OWASP Juice Shop (Dockerized)
- Network: Host-Only / NAT

## How to Run (Lab Setup)
Target (Ubuntu):
- docker pull bkimminich/juice-shop
- docker run -d --name juice -p 3000:3000 bkimminich/juice-shop

Attacker (Kali):
- Open http://<ubuntu-ip>:3000

## Vulnerabilities Tested
- Authentication Bypass
- SQL Injection
- Cross-Site Scripting (XSS)
- Broken Access Control

## Learning Outcomes
- Understanding vulnerable web applications
- Hands-on penetration testing practice
- Secure deployment using Docker
- Ethical hacking methodology

## Disclaimer
This project is created strictly for educational purposes in a controlled environment. No real-world systems were harmed or targeted.
