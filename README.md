# 🩺 AI Assisted Telemedicine 

AI Assisted Telemedicine  is an intelligent and interactive AI-based healthcare platform designed to simulate real-time medical consultation using multimodal inputs—text, voice, and images. It bridges the gap between users and healthcare professionals, enabling faster and more accessible diagnosis, health event discovery, and doctor communication.

---

## 🚀 Key Features

### 🧠 AI Consultation (Multi-Modal)
- **Text Input**: Describe symptoms through a textbox.
- **Voice Input**: Speak symptoms using speech-to-text.
- **Image Upload**: Upload prescriptions or symptom-related photos.
- **Camera Input**: Capture live images during consultation.

### 📋 Smart AI Diagnosis
- Uses **NLP** and **Computer Vision** to process user input.
- Provides possible diagnoses and health suggestions.
- Recommends tests or home remedies.
- Alerts if a human doctor should be consulted.

### 🎙️ Live Voice-Based AI Assistant
- Real-time **two-way voice conversation** with the AI.
- Integrated with **ElevenLabs API** for realistic spoken replies.
- Mute/unmute options for better user control.

### 👨‍⚕️ Doctor Dashboard
- Doctor **signup/login** with profile management.
- View past patient consultations.
- Access AI-generated session summaries.

### 🧬 NGO & Health Organization Portal
- NGOs can register and **post upcoming events** (blood donation camps, awareness programs, etc.).
- Users can view events on a public **/events** page with map integration.

---

## 🧑‍💻 Technology Stack

| Component     | Tech Used                                |
|---------------|-------------------------------------------|
| Frontend      | React.js, HTML, CSS, JavaScript           |
| AI Backend    | Python, Flask, OpenAI/Groq API, ElevenLabs |
| App Backend   | Node.js, Express.js                       |
| Database      | MongoDB                                   |
| Maps & Location | OpenStreetMap                           |
| Other Tools   | Gradio (initial prototyping), Web APIs    |

---

## 🗂️ Project Structure
AI Assisted Telemedicine 
│
├── client/ # React frontend
├── server/ # Node.js backend for doctors & NGOs
├── flask-backend/ # Python Flask AI engine
└── README.md


---

## ⚙️ How It Works

1. **User** logs in or signs up from the frontend.
2. Inputs symptoms via **text**, **voice**, **camera**, or **image upload**.
3. The input is sent to **Flask (Python)** backend for AI processing.
4. The assistant provides a **consultation summary** in text and voice.
5. Session data is saved to **MongoDB**.
6. **Doctors** can log in to view patient summaries.
7. **NGOs** can register and list health events viewable by all users.

---

## 🔐 Backend Details

### 🩺 AI Engine (Flask – Python)
- `app.py` handles all AI logic and routes.
- Integrates:
  - **OpenAI/Groq API** for NLP-based health consultation.
  - **Image Analysis** model for analyzing symptom images.
  - **ElevenLabs API** for realistic voice response.

### 👨‍⚕️ App Backend (Node.js)
- REST APIs for doctor and NGO registration/login.
- Stores user data, events, and consultation summaries in MongoDB.

---

## 💾 Setup Instructions

### 🔧 Prerequisites
- Node.js and npm
- Python 3.x and pip
- MongoDB (local or Atlas)

### 🖥️ Frontend Setup
cd client
npm install
npm start

🌐 Node.js Backend (Doctor/NGO)
cd server
npm install
node index.js

Python Flask Backend (AI Engine)
cd flask-backend
pip install -r requirements.txt
python app.py

📈 Future Scope
SMS/Email reminders
Appointment bookings with real doctors
Integration with wearable health devices (e.g., smartwatches)
Chronic disease tracking and health analytics
Health record uploads and history

📜 License
This project is for educational and research purposes. Commercial use without permission is not allowed.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

✨ Acknowledgements
OpenAI
ElevenLabs
MongoDB
React
Node.js
Python Flask
OpenStreetMap

📫 Contact
Created by Tejas Auti
For queries or collaboration: https://www.linkedin.com/in/tejasauti1 | tejas.auti2204@gmail.com
