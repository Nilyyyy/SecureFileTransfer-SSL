# 🔐 Secure File Transfer over Encrypted Channel

A Python-based secure file transfer system that allows encrypted file transmission between users.  
The system is designed with both functionality and security in mind, applying custom encryption logic and secure storage practices.

---

## 🚀 Features

- 📁 Secure file sending and downloading between clients.
- 🔐 Encrypted communication and local storage.
- 💾 Plain and encrypted file storage options.
- 🧪 Security assessment included.
- 📊 Project report & demonstration video provided.

---

## 🛠️ Technologies Used

- Python 3.8+
- Sockets (`socket`, `threading`)
- Custom encryption logic
- File I/O operations
- OS and Path libraries

---

## 📁 Folder Structure

```
secure-file-transfer-ssl/
│
├── source_code/              # All source .py files (client, server, etc.)
├── downloads/                # Received files directory
├── storage_plain/            # Plain storage for comparison
├── reports/                  # Project reports
│   ├── project_report.pdf
│   └── security_analysis.txt
│
├── demo_video.mp4            # Project demonstration video
├── contributors.txt          # List of team members
├── README.md
```

---

## ▶️ How to Run

### 🖥️ Run Server
```bash
python server.py
```

### 📦 Run Client
```bash
python client.py
```

Clients can send or receive files by selecting the corresponding action via terminal.

---

## 🧠 Security

The project includes a basic implementation of:
- Symmetric encryption logic (can be extended to AES)
- Secure file saving
- Simple threat modeling (see `security_analysis.txt`)

---

## 👥 Contributors

This project was developed as part of a university networking course by a team of 4 members.

For full list, see: `contributors.txt`

---

## 📎 Resources

- 📄 `project_report.pdf`: Full project report with architecture and evaluation
- 📄 `security_analysis.txt`: Risk evaluation and protection logic
- 🎥 `demo_video.mp4`: System demonstration video

---

## 📌 Disclaimer

This project is for academic purposes and **should not be used in production** without further security improvements.
