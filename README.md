<<<<<<< HEAD
# Sentiment-Driven Feedback System

## Setup Instructions

### Frontend:
=======
# 🎓 College Event & Club Feedback System

A full-stack application that collects user feedback, analyzes it with sentiment analysis (TextBlob & VADER), and shows results in an admin dashboard. Gmail email alerts and admin authentication included.

## 🛠 Tech Stack
- **Frontend:** React, Tailwind CSS
- **Backend:** FastAPI, SQLite
- **NLP:** TextBlob, VADER
- **Auth:** JWT
- **Email Alerts:** Gmail SMTP

## 🚀 Getting Started

### Frontend
>>>>>>> f2136a4 (Initial commit: Full-stack feedback system)
```bash
cd frontend
npm install
npm start
```

<<<<<<< HEAD
### Backend:
=======
### Backend
>>>>>>> f2136a4 (Initial commit: Full-stack feedback system)
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

<<<<<<< HEAD
### .env File (Place in backend directory):
Refer to `.env.example` for required variables.
=======
## 🔐 Admin
- JWT-based login for admins
- Super admin can manage other admins

## 📬 Email
- Set up `.env` with Gmail credentials for notifications

## 📊 Sentiment
- Uses both TextBlob and VADER to classify feedback
>>>>>>> f2136a4 (Initial commit: Full-stack feedback system)
