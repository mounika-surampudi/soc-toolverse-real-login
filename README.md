# SOC ToolVerse - Centralized SOC Analyst Dashboard

🔗 **Live Demo:** https://soc-toolverse-real-login.onrender.com
👩‍💻 **Built by:** Mounika Surampudi | SOC Analyst Aspirant

## Overview
SOC ToolVerse is a centralized, secure dashboard for SOC Analysts to access 50+ security tools from a single platform. Designed with security-first approach.

## 🔐 Security Features
- **Password Hashing:** Uses `pbkdf2:sha256` (Werkzeug) - No plain text storage
- **Real Login Module:** Redirects to original tool's official login page in new tab
- **Session-Based Authentication:** Secure login/logout flow

## 🛠️ Integrated Tools
- **Phish Check:** Analyze suspicious URLs/emails (e.g., WhatsApp links)
- **IP Intel:** Check if IP is malicious/hacker
- **Password Lab:** Strength testing
- **QR Maker:** Secure QR generation
- **Hash Lab:** Hash generation & verification

## 💻 Tech Stack
- Backend: Python, Flask
- Security: Werkzeug Security
- Frontend: HTML5, CSS3, JavaScript
- Database: SQLite
- Deployment: Render

## 🚀 Deployment Files
- `app.py` - Main Flask application
- `requirements.txt` - Dependencies
- `Procfile` - Render deployment config

## 📸 Screenshots
Login, Register, Dashboard, Doubt Clear (SAFE/UNSAFE), IP Intel

## How to Run Locally
```bash
pip install -r requirements.txt
python app.py
