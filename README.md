# 💬 Django Chat App

A real-time **Chat Application** built with **Python Django** and **WebSockets**.  
This app allows users to create chat rooms, join with a username, and exchange messages in **real time**.  
Supports **private chatting with friends** and **group chats**.

---

## 🚀 Features

- 🔹 Create or join chat rooms by entering a room name & username.  
- 🔹 Real-time messaging using **WebSockets** (Django Channels).  
- 🔹 Group chat & one-to-one conversation support.  
- 🔹 Messages aligned left/right depending on sender.  
- 🔹 Auto-scroll to latest messages.  
- 🔹 Modern UI using **Tailwind CSS**.  
- 🔹 Responsive design for mobile & desktop.  

---

## 🛠️ Tech Stack

- **Backend:** Django, Django Channels, Python  
- **Frontend:** HTML5, Tailwind CSS, JavaScript (AJAX/jQuery)  
- **WebSockets:** Channels, Redis (for production)  
- **Database:** SQLite (default), PostgreSQL/MySQL (optional)  

---

## 📂 Project Structure

chat-app/
│
<br>
├── chat/ # Chat app (Django app)
<br>
│ ├── migrations/
<br>
│ ├── templates/ # HTML templates
<br>
│ │ ├── home.html
<br>
│ │ └── room.html
<br>
│ ├── views.py
<br>
│ ├── models.py
<br>
│ ├── urls.py
<br>
│ └── consumers.py # WebSocket logic
<br>
│
<br>
├── chatapp/ # Project root (settings, asgi, urls)
<br>
│ ├── settings.py
<br>
│ ├── urls.py
<br>
│ └── asgi.py # WebSocket entry point
<br>
│
<br>
├── manage.py
<br>
└── README.md
<br>

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/jainambharvad9/Chat-App.git
   cd chat-app
Create virtual environment & activate


python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
Install dependencies



Apply migrations


python manage.py migrate
Run server


python manage.py runserver
Open in browser → http://127.0.0.1:8000/


🖼️ Screenshots
🔹 Home Page (Create/Join Room)
![Demo Screenshot](https://github.com/jainambharvad9/Chat-App/blob/main/Chat%20App/Screenshot%202025-08-23%20234908.png)

🔹 Chat Room
![Demo Screenshot](https://github.com/jainambharvad9/Chat-App/blob/main/Chat%20App/Screenshot%202025-08-23%20235000.png)

🔮 Future Improvements
✅ Add user authentication system

✅ Add online/offline user status

✅ Support file/image sharing

🤝 Contributing
Fork the project

Create a new feature branch (git checkout -b feature-name)

Commit your changes (git commit -m "Added new feature")

Push to your branch (git push origin feature-name)

Open a Pull Request

📜 License
This project is licensed under the MIT License – feel free to use and modify.

👨‍💻 Author Jainam Saraiya
📧 jainamsaraiya9@example.com
🌐 GitHub https://github.com/jainambharvad9

---
