
# 🧠 MeetSync – Smart AI-Powered Video Meeting Platform

MeetSync is a powerful video meeting application that combines **Django**, **ZegoCloud**, and **AI-powered tools** to create a modern, interactive meeting experience.  
It allows users to host or join secure video meetings with advanced features like gesture-based drawing, automated attendance, voice control, and note-taking.

---

## 🚀 Features

### 🎨 Air Canvas
- Draw or write in the air using hand gestures powered by **OpenCV** and **MediaPipe**.
- Host-exclusive feature for interactive explanations or brainstorming.

### 📋 Automatic Attendance (Excel Export)
- Detects participant faces during meetings using AI.  
- Saves attendance records automatically in an Excel file, identified by **Room ID**.

### 📝 Notes Making
- Integrated meeting notes system for saving important points or ideas discussed during meetings.
- Notes can be saved per meeting session.

### 🎙️ Voice Command System
- Control actions like **mute/unmute**, **camera on/off**, **screen sharing**, or **start/stop Air Canvas** using simple voice commands.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Django |
| **Frontend** | HTML, CSS, JavaScript |
| **Video SDK** | ZegoCloud UIKit Prebuilt |
| **AI Modules** | OpenCV, MediaPipe |
| **Database** | SQLite |
| **Other Tools** | Pandas, SpeechRecognition |

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/MeetSync.git
   cd MeetSync
   ```

2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add Your ZegoCloud API Credentials**
   - Update your ZegoCloud App ID and Server Secret in Django settings or `.env` file.

5. **Run the Server**
   ```bash
   python manage.py runserver
   ```

6. **Access the App**
   Open your browser and visit:
   ```
   http://127.0.0.1:8000/
   ```

---

## 📁 Project Structure

```
MeetSync/
│
├── templates/            # HTML files
├── static/               # CSS, JS, and images
├── aircanvas.py          # OpenCV-based gesture drawing module
├── facedetection.py      # Face recognition and attendance logic
├── voice_command.py      # Voice command integration
├── notes/                # Notes management module
├── manage.py
└── README.md
```

---

## 📸 Screenshots (Optional)

You can add your project screenshots like this:

```markdown
![Dashboard Screenshot](screenshots/dashboard.png)
![Air Canvas in Action](screenshots/aircanvas.png)
```

---

## 💡 Future Enhancements
- Add Google Calendar integration for scheduling.
- Implement AI-based meeting summary generation.
- Real-time transcription and translation features.

---

## 🤝 Contributing
Contributions are welcome!  
If you’d like to improve the project, feel free to fork the repo and submit a pull request.

---

## 🧑‍💻 Author
**Utkarsh Tripathi**  
Built with ❤️ using Django and ZegoCloud.

---

## 📜 License
This project is licensed under the **MIT License**.
