# ⚖️ H-A-QMarg – AI-Powered Legal Assistance Platform

H-A-QMarg is an AI-powered legal assistance platform designed to make legal support accessible for women, especially in Tier-2 and Tier-3 cities in India. It provides AI-guided legal advice, petition generation, downloadable legal documents, and access to NGOs, helplines, and legal resources through a simple and user-friendly interface.

---

## 🚀 Features

### 🤖 AI Legal Assistant
- AI-powered chatbot using Google Gemini API
- Answers legal queries in simple language
- Guest access without mandatory login

### 📄 AI Petition Generator
- Generates professional legal petitions
- Supports different legal case types
- Creates downloadable PDF petitions

### 🏛️ Legal Resources
- NGO directory
- Emergency helpline numbers
- Frequently Asked Questions (FAQs)

### 🎤 Voice Support
- Voice-to-text input
- Text-to-speech responses
- Accessible for users with limited typing skills

### 🌍 Multi-language Support
- Designed for users from Tier-2 and Tier-3 cities
- Supports multiple languages (extendable)

### 📱 Responsive Design
- Works on desktop, tablet, and mobile devices

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS

### Backend
- Node.js
- Express.js
- REST APIs

### Database
- MongoDB Atlas
- Mongoose

### AI & APIs
- Google Gemini API
- Browser Speech Recognition API
- Browser Speech Synthesis API
- PDFKit

---

## 📂 Project Structure

```
H-A-QMarg/
│
├── Backend/
│   ├── config/
│   ├── controllers/
│   ├── routes/
│   ├── services/
│   ├── models/
│   ├── middleware/
│   ├── utils/
│   ├── data/
│   ├── .env
│   └── server.js
│
├── src/
├── public/
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/H-A-QMarg-Hackathon-Project.git
```

### 2. Navigate to the Project

```bash
cd H-A-QMarg-Hackathon-Project
```

### 3. Install Frontend Dependencies

```bash
npm install
```

### 4. Install Backend Dependencies

```bash
cd Backend
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `Backend` folder.

```env
PORT=5000

MONGO_URI=YOUR_MONGODB_CONNECTION_STRING

GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd Backend
npm run dev
```

### Start Frontend

```bash
npm run dev
```

---

## 🌐 API Endpoints

### Chat API

```
POST /api/chat
```

### Petition Generator

```
POST /api/petition
```

### Download Petition PDF

```
GET /api/petition/download
```

### NGOs

```
GET /api/resources/ngos
```

### Helplines

```
GET /api/resources/helplines
```

### FAQs

```
GET /api/resources/faqs
```

---

## 🎯 Problem Statement

Many women in rural and semi-urban India struggle to access legal guidance due to limited awareness, language barriers, and lack of nearby legal resources. H-A-QMarg bridges this gap by providing AI-assisted legal support, petition generation, and verified legal resources through an easy-to-use platform.

---

## 🔮 Future Scope

- User authentication
- Petition history
- Nearby police stations and legal aid centers
- Live lawyer consultation
- Regional language expansion
- AI-powered legal document summarization

---

## 👩‍💻 Team

Developed for the **H-A-QMarg Hackathon Project**.

---

## 📜 License

This project is developed for educational and hackathon purposes.
