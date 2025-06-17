# Hackthone_Team_Coders

🧠 Healer'sHub – Mood Detection Based Emotional Assistant
Developed at the 7th RIT Hackathon 2025

👥 Team: Sanika Desai, Vaishnavi Shelar, Prathamesh Patil, Uday Yadav

💡 Focus: Mood-based emotional support using ML and personalized messages

📌 Project Overview
Healer'sHub is a full-stack web application that detects a user's emotional mood using a machine learning model and responds with a supportive letter-style message based on the predicted emotion.

This project aims to offer emotional comfort through the power of tech and empathy, developed in just 24 hours during RIT Hackathon 2025.

🎯 Features

🤖 ML-Based Mood Detection: Python model analyzes input text or parameters to detect emotion.

💌 Personalized Letters: Based on detected mood (e.g., sad, anxious, happy, angry), the user receives a comforting emotional letter.

🌐 Responsive UI: Built using ReactJS for a smooth and interactive experience.

🔗 Backend Integration: Java Spring Boot connects frontend with the ML model.

🛠️ Tech Stack

Frontend: React.js
Backend: Java Spring Boot
ML Model: Python (Flask)
Communication: REST APIs

🚀 How to Run the Project

Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/healershub.git
cd healershub
Run the ML Model (Python)

bash
Copy
Edit
cd ml-model
pip install -r requirements.txt
python app.py
Starts server at http://localhost:5000

Run the Spring Boot Backend

bash
Copy
Edit
cd backend
./mvnw spring-boot:run
Starts backend at http://localhost:8080

Run the React Frontend

bash
Copy
Edit
cd frontend
npm install
npm start
Starts frontend at http://localhost:3000

📁 Folder Structure

bash
Copy
Edit
healershub/
├── frontend/        # React App
├── backend/         # Java Spring Boot APIs
├── ml-model/        # Python-based Emotion Detection
└── README.md
📸 Preview (Add screenshots here if available)

Homepage

Input Mood Screen

Generated Support Letter Screen

📦 How It Works

sql
Copy
Edit
ReactJS Frontend → Spring Boot Backend → Python ML Model
→ Returns emotion → Spring Boot → React → Displays support letter
🧑‍🤝‍🧑 Team Members

Sanika Desai – React Frontend & Coordination

Vaishnavi Shelar – Content and Letters

Prathamesh Patil – Spring Boot API & Integration

Uday Yadav – Python ML Model & Prediction API

📄 License
This project is open-source under the MIT License.

💬 Notes

Each emotion is mapped to a thoughtful letter:

😞 Sad → “You’re not alone...”

😠 Angry → “Take a deep breath...”

😌 Calm → “Peace is power...”

😊 Happy → “Keep spreading joy...”

Easy to extend with:

User login

Database support

More NLP-based emotion models
