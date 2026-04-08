# phishing-simulation-lab
Ethical phishing simulation lab using Gophish to analyze user vulnerability and security awareness.

# Ethical Phishing Simulation Lab | Gophish

## 📌 Project Overview
This project consists of a controlled phishing simulation environment designed to study social engineering attack vectors and assess user security awareness. The goal was to demonstrate how easily attackers can compromise credentials and to provide actionable insights for security training.

## 🛠️ Technologies Used
* **Gophish:** Open-source phishing framework.
* **Linux (Ubuntu):** Hosting the simulation server.
* **HTML/CSS:** For crafting realistic email templates and landing pages.
* **Networking:** Configured SMTP relay and sending profiles.

## 🚀 Lab Implementation Steps
1. **Environment Setup:** Installed and configured Gophish on a Linux instance.
2. **Template Design:** Created high-fidelity email templates mimicking common corporate alerts (e.g., password reset, urgent IT notifications).
3. **Landing Page Creation:** Developed a "clone" login page to capture simulation metrics.
4. **Campaign Launch:** Defined target groups and executed the sending profile.
5. **Data Analysis:** Monitored real-time statistics (Email Sent, Opened, Link Clicked, Data Submitted).

## 📊 Key Findings & Metrics
* **Engagement:** Tracked how many users bypassed visual red flags (sender address, URL mismatches).
* **Vulnerability Gap:** Identified the specific types of hooks that led to the highest credential submission rates.

## ⚖️ Ethical Disclaimer
This lab was conducted in a strictly controlled environment for educational and ethical purposes only. No actual sensitive data was collected, and all simulations were performed following ethical hacking guidelines.

---
*Developed as part of my Cybersecurity studies at City College Dublin.*


## 📸 Visuals from the Lab

### Campaign Dashboard
![Gophish Dashboard](dashboard.png)

### Email Template used
![Phishing Email](email.png)
