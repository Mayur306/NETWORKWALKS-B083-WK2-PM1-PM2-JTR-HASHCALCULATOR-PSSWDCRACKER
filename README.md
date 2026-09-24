# 🔐 Password Cracking Labs — Cybersecurity & Ethical Hacking

This repository documents two hands-on password cracking labs completed as part of a Cybersecurity & Ethical Hacking training project (Week 3). Both labs focus on recovering the password of a locked PDF file using different tools and techniques, demonstrating how password hashes can be extracted and cracked using dictionary attacks.

> ⚠️ **Disclaimer:** These labs were performed in a controlled, educational environment on a file provided for training purposes only. Password cracking should only ever be performed on systems/files you own or have explicit authorization to test.

---

## 📁 Labs Included

### 1. Password Cracking with JTR (John the Ripper)
**Module:** Week 3 – Project Module 1

- Tools used: **John the Ripper (JTR)** and **Johnny** (GUI for JTR)
- Extracted the PDF hash using an online `pdf2john` hash extractor
- Loaded the hash into Johnny and ran a dictionary/brute-force attack
- Successfully recovered the PDF password

📄 [`W3-PM1_-_Week3_-_Project_Module1_-_Password_Cracking_with_JTR_v1.pdf`](./W3-PM1_-_Week3_-_Project_Module1_-_Password_Cracking_with_JTR_v1.pdf)

### 2. Password Cracking with NetworkWalks Tools
**Module:** Week 3 – Project Module 2

- Tools used: **NetworkWalks Hash Calculator** and **NetworkWalks Password Cracker** (browser-based, no install required)
- Extracted the `$pdf$...` hash directly from the locked PDF using the Hash Calculator
- Ran a dictionary attack via the Password Cracker to recover the password
- Verified the recovered password by unlocking the PDF

📄 [`W3-PM2_-_Week3_-_Project_Module2_-_Password_Cracking_with_NW_Tools_v1.pdf`](./W3-PM2_-_Week3_-_Project_Module2_-_Password_Cracking_with_NW_Tools_v1.pdf)

---

## 🧠 Key Concepts Covered

- **Hashing vs. Encryption** — hashing is a one-way function used to validate information, while encryption is reversible with the correct key
- **Hash Extraction** — pulling a crackable hash out of a password-protected file (PDF, ZIP, Office docs)
- **Dictionary Attacks** — testing a wordlist of common passwords against a hash until a match is found
- **Why weak passwords fail fast** — short/common passwords (e.g. `password1`) can be cracked in seconds to minutes, while long, complex passwords resist cracking for years

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| John the Ripper (JTR) | Core password cracking engine |
| Johnny | GUI front-end for JTR |
| NetworkWalks Hash Calculator | Extracts crackable hashes from locked PDFs (browser-based) |
| NetworkWalks Password Cracker | Runs dictionary attacks against extracted hashes (browser-based) |
| OnlineHashCrack (pdf2john) | Online PDF hash extraction utility |

---

## ✅ Outcome

Both labs successfully cracked the password of the same protected PDF file (`My Locked PDF1.pdf`), reinforcing the same lesson through two different toolsets — a locally installed cracking suite (JTR/Johnny) versus lightweight browser-based tools (NetworkWalks).

---

## 📚 Credits

Labs designed by **NetworkWalks Academy** as part of their Cybersecurity & Ethical Hacking training program.
🔗 [www.networkwalks.com](https://www.networkwalks.com)
