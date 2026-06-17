<div align="center">

# 🤖 InternHuntAI

**AI-Powered LinkedIn Internship Auto-Apply Bot**

[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-Config-orange?style=flat-square)
![Ngrok](https://img.shields.io/badge/Ngrok-Remote_Access-blue?style=flat-square)

> An AI-powered LinkedIn automation bot that helps students and job seekers apply to internships with one click. Uses Python, Playwright, Flask, and LocalXpose/Ngrok to auto-fill applications, handle resumes, and give mobile access via a secure tunnel.

</div>

---

## ✨ Features

- 🔐 **Secure LinkedIn login** with Playwright
- 🧩 **Captcha detection** with manual assist
- 📄 **Auto-uploads role-specific resumes**
- 📊 **Flask dashboard** — accessible on phone via tunnel
- 🌐 **Remote access** using LocalXpose
- 📝 **Application log** saved for tracking

---

## 🎬 Demo Recordings & Screenshots

All project screenshots and step-by-step recordings are available here:

👉 **[View Demo Folder on Google Drive](#)**

This folder contains:
- 🎥 Start-to-End Screen Recordings of setup & usage
- 💻 Screenshots of Terminal & Mobile Access
- 📱 Final working demo of InternHuntAI

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core language |
| Playwright | Browser automation |
| Flask | Web dashboard API |
| LocalXpose / Ngrok | Remote tunneling |
| YAML + JSON | Configuration & logs |

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/saikumar1626/InternHuntAI.git
cd InternHuntAI

# 2. Create virtual environment
python -m venv venv
venv\Scripts\activate    # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure your LinkedIn login in agent_config.yaml

# 5. Start the Flask server
python server.py

# 6. Expose it online (using LocalXpose)
cd C:\localxpose
.\loclx.exe tunnel http 5000
```

---

## ⚙️ Configuration

Edit `agent_config.yaml` to set:
- LinkedIn credentials
- Target job roles
- Resume file paths
- Application filters (location, experience level)

> ⚠️ **Never commit your `agent_config.yaml` with real credentials.** Add it to `.gitignore`.

---

## 📁 Project Structure

```
InternHuntAI/
├── server.py              # Flask dashboard server
├── app.py                 # Main application entry
├── auto_apply.py          # Core auto-apply logic
├── auto_apply_service.py  # Background service
├── form_filler.py         # LinkedIn form automation
├── job_fetchers.py        # Job listing fetcher
├── agent_config.yaml      # Configuration file
├── requirements.txt       # Python dependencies
└── run_instructions.md    # Detailed run guide
```

---

## ⚠️ Disclaimer

This tool is intended for **educational and personal use only**. Automated interactions with LinkedIn may violate their Terms of Service. Use responsibly and at your own risk.

---

## 🗺️ Roadmap

- [ ] Multi-platform support (Internshala, Naukri)
- [ ] AI-powered cover letter generation
- [ ] Smart job filtering by skill match
- [ ] Email notifications for applications
- [ ] Dashboard analytics

---

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">

🤖 **InternHuntAI — Apply smarter, not harder.**

</div>
