# 🔐 Face & Gesture-Based Authentication System

A multi-factor authentication system that uses **face recognition**, **hand gestures**, and **OTP-based recovery** to authenticate users. Built entirely in a **Jupyter Notebook** using Python, OpenCV, MediaPipe, and smtplib.

---

# 📌 About the Project

This project was developed as part of the **Project Open House** at **RNS Institute of Technology**. It combines artificial intelligence, computer vision, and gesture recognition to create a secure and intuitive user authentication system.

---

# 🚀 Features

- 👤 Face recognition with MediaPipe Face Mesh  
- ✋ Hand gesture sequence authentication  
- 🔁 OTP-based gesture recovery system (via email)  
- 🛠 Admin controls to manage users and database  
- 🌐 Redirects to a welcome webpage that connects to WhatsApp Web after login

---
# 📓 File Info

|    File Name       |                   Description                        |
|--------------------|------------------------------------------------------|
| `main.ipynb`       | Main Jupyter Notebook with the entire system code    |
| `requirements.txt` | List of Python libraries to install                  |
| `welcome.html`     | Webpage template shown after login                   |
| `user_data/`       | Folder containing user Excel file and face encodings |
| `models/`          | Contains the trained face recognition model          |

---

# 🧠 Tech Stack

- Python  
- Jupyter Notebook (`.ipynb`)  
- OpenCV  
- MediaPipe  
- Scikit-learn (SVM)  
- Pandas & Excel  
- smtplib (for OTP via Gmail)

---

# ⚙️ How to Run This Project

✅ Prerequisites

- Python 3.8+  
- Jupyter Notebook installed (`pip install notebook`)  
- A working webcam  
- Gmail account for OTP (use an app password if 2FA is enabled)

📦 Installation

1. Clone the repository or download the `.zip`
   ```bash
   git clone https://github.com/YOUR_USERNAME/face-gesture-authentication.git
   cd face-gesture-authentication
