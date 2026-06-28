# 🏥 MedAI – Medical Intelligence Assistant

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-green?style=for-the-badge)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge)
![Ollama](https://img.shields.io/badge/AI-Ollama-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)

## A Modern Offline-First Medical AI Desktop Assistant

AI-powered Medical Assistant built using **Python**, **CustomTkinter**, **SQLite**, and **Ollama**.

</div>

---

# 📖 Overview

MedAI is a modern desktop Medical Intelligence Assistant that combines Local AI, Offline Medical Knowledge, and Secure Authentication into one application.

The application allows users to chat with locally running AI models using Ollama while also downloading medical knowledge for complete offline access.

---

# ✨ Features

## 🤖 AI Assistant

- AI-powered medical conversations
- Streaming responses
- Multiple Ollama model support
- Automatic model detection
- Online Mode
- Offline Mode
- Intelligent conversation management

---

## 🔐 Authentication

- Local Registration
- Local Login
- Secure Password Hashing
- Optional Google Sign-In
- Session Management
- Automatic Login

---

## 💬 Chat System

- Beautiful Chat Interface
- Streaming AI Responses
- Multiple Chat Sessions
- Automatic Chat Titles
- Chat History
- Persistent Conversations

---

## 📥 Offline Medical Knowledge

Download medical knowledge for offline usage.

Available categories include:

- Anatomy & Physiology
- Pharmacology
- Microbiology
- Pathology
- Cardiology
- Neurology
- Surgery
- Pediatrics
- Dermatology
- Psychiatry
- Emergency Medicine
- Internal Medicine
- Infectious Diseases
- Oncology
- Endocrinology
- And many more...

---

## 🗄 Database

SQLite stores:

- Users
- Login Sessions
- Chat History
- Medical Downloads
- Preferences
- Settings

---

## 🎨 Modern UI

- Dark Theme
- Responsive Layout
- Sidebar Navigation
- Download Manager
- Settings Window
- Chat Interface
- Professional Medical Theme

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| CustomTkinter | Desktop GUI |
| SQLite | Local Database |
| Ollama | Local AI Models |
| Requests | API Communication |
| Google OAuth | Optional Authentication |
| JSON | Data Storage |
| Threading | Background Tasks |

---

# 📁 Project Structure

```text
MedAI/
│
├── app.py
├── config.py
├── database.py
├── auth.py
│
├── core/
│   ├── __init__.py
│   └── engine.py
│
├── gui/
│   ├── login_screen.py
│   ├── chat_screen.py
│   ├── sidebar.py
│   ├── download_screen.py
│   ├── settings_screen.py
│   └── theme.py
│
├── data/
│   ├── database/
│   ├── medical_fields/
│   └── cache/
│
├── auth/
│   └── client_secret.json
│
├── assets/
│
├── build_exe.bat
├── build_installer.bat
├── installer.iss
│
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/MedAI.git

cd MedAI
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Install Ollama

Download Ollama from:

https://ollama.com

---

## Download AI Model

Example:

```bash
ollama pull llama3.1
```

---

## Start Ollama

```bash
ollama serve
```

---

## Run Application

```bash
python app.py
```

---

# 🔑 Google Login

Google Authentication is optional.

If you want Google Sign-In:

1. Create a Google Cloud Project.
2. Enable OAuth.
3. Download `client_secret.json`.
4. Place it inside the `auth` folder.

If the file is missing, the application will automatically use Local Authentication.

---

# 📸 Application Modules

- Login Screen
- Registration Screen
- Chat Screen
- Sidebar
- Download Manager
- Settings Screen
- Medical Knowledge Manager
- Database Manager
- AI Engine

---

# 🔒 Privacy

MedAI keeps your data private.

✔ Local AI Processing

✔ Local SQLite Database

✔ Offline Medical Knowledge

✔ No Mandatory Cloud Storage

✔ User Data Remains Local

---

# ⚠ Medical Disclaimer

MedAI is intended for **educational and informational purposes only**.

It is **NOT** a replacement for licensed healthcare professionals.

Always consult qualified medical professionals before making medical decisions.

If you are experiencing a medical emergency, contact your local emergency services immediately.

---

# 📈 Roadmap

- Voice Conversations
- Medical Image Analysis
- Laboratory Report Analysis
- Drug Interaction Checker
- Medical Citation Engine
- Cloud Synchronization
- Multi-language Support
- Plugin Support
- Better AI Model Management

---

# 👨‍💻 Author

Developed with ❤️ using

- Python
- CustomTkinter
- SQLite
- Ollama

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It helps support future development.

---

# 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for more information.

---

<div align="center">

## 🏥 MedAI

### Intelligent Medical Assistance • Offline First • Privacy Focused

Made with ❤️ in Python

</div>
