# Universal OSINT 🔍

A lightweight, modular OSINT CLI tool built for quick lookups on emails, domains, and usernames using public APIs and data sources.

### 🚀 Why?
To help investigate digital footprints, suspicious activity, or scam indicators — especially in cybersecurity, scam awareness, and threat intel work.

---

## 🔧 Current Features (MVP)

✅ Email Lookup  
- Format validation  
- Breach check using HaveIBeenPwned (if API key available)  

✅ Domain Lookup  
- WHOIS data  
- Domain age & registrar info  

✅ Username Lookup  
- Cross-platform check (starting with GitHub, Reddit, Instagram)

---

## 🛠️ Tech Stack

- Python 3
- `requests`
- `argparse`
- `re`
- Public APIs : `HaveIBeenPwned`, `whoisxml`, `Namechk`, etc.

---

## 📦 Folder Structure

universal-osint/
├── main.py
├── modules/
│ ├── email_lookup.py
│ ├── domain_lookup.py
│ └── username_lookup.py
├── utils/
│ ├── validators.py
│ └── output.py
├── requirements.txt
└── README.md

 Future Features
 Phone number lookup



