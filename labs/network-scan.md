
# 🧪 Lab: Thinking Like an Attacker & Directory Enumeration

## 🎯 Objective
To understand the mindset of an attacker and use directory enumeration to discover hidden web pages.

---

## 🛠 Tools Used
- Dirb

---

## ⚙️ Methodology
1. Identified a target web application
2. Used Dirb to perform directory brute-forcing
3. Sent requests to discover hidden directories and files
4. Analyzed the responses to identify valid pages
5. Accessed discovered pages via browser

---

## 🔍 Findings
- Discovered hidden directories and pages not visible on the main website
- Some pages were accessible without authentication
- These pages could expose sensitive functionality or data

---

## ⚠️ Impact
- Hidden endpoints increase the attack surface
- Attackers can find:
  - Admin panels
  - Backup files
  - Sensitive data
- This can lead to unauthorized access or further exploitation

---

## 🛡 Recommendations
- Restrict access to sensitive directories
- Implement authentication where necessary
- Remove unused or exposed files
- Use proper access controls and security headers

---

## 🧠 What I Learned
- Attackers don’t rely only on visible links
- Directory brute-forcing helps uncover hidden attack surfaces
- Small misconfigurations can expose critical parts of a system
