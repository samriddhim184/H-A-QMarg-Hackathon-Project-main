# ⚖️ H-A-QMarg — AI-Powered Legal Assistance Platform

H-A-QMarg is an **AI-powered legal assistance platform** designed to make legal information and support more accessible to women, particularly those in Tier-2 and Tier-3 cities in India.

The platform combines **AI-guided assistance, petition generation, voice support, and legal resources** in a simple, user-friendly interface.

> **Disclaimer:** H-A-QMarg provides AI-assisted legal information and is not a substitute for professional legal advice.

---

## 🚀 Features

### 🤖 AI Legal Assistant

* AI-powered chatbot using the **Google Gemini API**
* Provides legal information in simple, accessible language
* Guest access without mandatory registration
* Situation-based guidance for common legal concerns

### 📄 AI Petition Generator

* Generates structured legal petition drafts
* Supports multiple case types
* Generates downloadable PDF documents
* Helps users understand the information required for a petition

### 🏛️ Legal Resources

* NGO directory
* Emergency helpline information
* FAQs and legal awareness resources
* Designed to help users find relevant support

### 🎤 Voice Support

* Voice-to-text input
* Text-to-speech responses
* Makes the platform easier to use for people with limited typing skills

### 🌍 Multi-Language Support

* Designed with users from diverse linguistic backgrounds in mind
* Architecture can be extended to support additional regional languages

### 📱 Responsive Design

* Mobile-friendly interface
* Responsive across desktop, tablet, and mobile devices

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB Atlas
* Mongoose

### AI & APIs

* Google Gemini API
* Browser Speech Recognition API
* Browser Speech Synthesis API
* PDFKit

---

## 📂 Project Structure

```text
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
│   ├── .env.example
│   └── server.js
│
├── src/
├── public/
├── package.json
├── .gitignore
└── README.md
```

> **Note:** The actual `.env` file should never be committed to GitHub. Use `.env.example` to document the required variables.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/H-A-QMarg-Hackathon-Project.git
cd H-A-QMarg-Hackathon-Project
```

### 2. Install Frontend Dependencies

```bash
npm install
```

### 3. Install Backend Dependencies

```bash
cd Backend
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `Backend` folder:

```env
PORT=5000
MONGO_URI=YOUR_MONGODB_CONNECTION_STRING
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

**Never commit your `.env` file or API keys to GitHub.**

---

## ▶️ Run the Project

### Start the Backend

From the `Backend` directory:

```bash
npm run dev
```

### Start the Frontend

Open another terminal and navigate to the project root:

```bash
npm run dev
```

The frontend will normally be available at:

```text
http://localhost:5173
```

---

## 🌐 API Endpoints

| Feature               | Method | Endpoint                   |
| --------------------- | ------ | -------------------------- |
| AI Chat               | POST   | `/api/chat`                |
| Petition Generator    | POST   | `/api/petition`            |
| Download Petition PDF | GET    | `/api/petition/download`   |
| NGOs                  | GET    | `/api/resources/ngos`      |
| Helplines             | GET    | `/api/resources/helplines` |
| FAQs                  | GET    | `/api/resources/faqs`      |

---

## 🎯 Problem Statement

Many women in rural and semi-urban areas face difficulties accessing legal information because of:

* Limited awareness of legal rights
* Language and communication barriers
* Lack of accessible legal resources
* Difficulty understanding legal procedures
* Limited awareness of nearby support organizations

**H-A-QMarg aims to bridge this accessibility gap** by bringing AI-assisted legal information, document assistance, voice interaction, and relevant resources together in one platform.

---

## 💡 Impact

H-A-QMarg focuses on making legal information:

**Accessible • Understandable • Voice-Friendly • Resource-Oriented**

The goal is not to replace lawyers or legal professionals, but to help users better understand their options and take informed next steps.

---

## 🔮 Future Scope

* 🔐 User authentication and secure profiles
* 📁 Petition and document history
* 📍 Nearby police stations and legal-aid centers
* 👩‍⚖️ Live lawyer consultation
* 🌐 Expanded regional-language support
* 📑 AI-powered legal document summarization
* 🔊 Improved voice-based accessibility
* 🏛️ Integration with verified government and legal-aid resources

---

## 👩‍💻 Team

Developed as part of the **H-A-QMarg Hackathon Project**.

### Built with

**React • Node.js • Express • MongoDB • Gemini AI • Tailwind CSS**

---

## ⚠️ Disclaimer

H-A-QMarg is an educational and informational technology project. AI-generated responses and documents may contain errors and should be reviewed by a qualified legal professional before being used for legal proceedings.

**H-A-QMarg — Making Legal Support More Accessible.**
