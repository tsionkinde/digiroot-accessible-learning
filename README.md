# 🌱 DIGIROOT – Accessible Digital Learning for Every Child

**Bridging the digital divide and accessibility gap for every child.**

DIGIROOT is an inclusive, beginner-friendly digital learning platform designed to help children in both rural and urban communities develop essential computer literacy skills, regardless of their abilities, technology access, or learning environment.

Our goal is to make digital education accessible to every child through simple lessons, accessible interactions, and offline-friendly learning.

## 🎯 The Problem

Many children face barriers to accessing digital education. Children in rural communities may have limited access to computers, reliable internet, and digital learning resources. Children with disabilities may also encounter digital platforms that are not designed with their accessibility needs in mind.

Traditional digital learning platforms often assume that every learner has the same technology, abilities, and learning environment.

DIGIROOT aims to change this by making digital literacy education more inclusive and accessible.

## 💡 Our Solution

DIGIROOT provides an accessible digital learning environment where children can learn basic computer skills at their own pace.

The platform is designed to:

- Support children with and without disabilities.
- Work in different learning environments, including rural and urban communities.
- Provide beginner-friendly computer literacy lessons.
- Support accessible interactions and assistive technologies.
- Make essential learning content available offline.
- Encourage independent and collaborative learning.

## ✨ Key Features

### 📚 Beginner-Friendly Lessons

- Introduction to computers and their components.
- Learning how to use a keyboard and mouse.
- Understanding instructions, sequences, and basic computational thinking.

### ♿ Accessibility Features

- Keyboard-friendly navigation.
- Screen-reader-friendly interface.
- High-contrast display option.
- Adjustable text size.
- Optional text-to-speech support.
- Clear instructions and accessible learning activities.

### 🌍 Inclusive Learning

- Designed for children in rural and urban communities.
- Supports children with different abilities and learning needs.
- Suitable for shared computers and classroom environments.

### 📶 Offline-Friendly Learning

- Core learning content designed to be accessible without a continuous internet connection.
- Local progress storage.
- Future support for synchronization when internet access becomes available.

### 🤖 AI Learning Buddy

An optional AI-powered learning assistant designed to explain basic computer concepts in simple language, provide hints, and encourage children as they learn.

_AI assistance requires an internet connection and is not necessary to access the core lessons._

## 🛠️ Technology Stack

| Area            | Technologies                     |
| --------------- | -------------------------------- |
| Frontend        | React, Vite, CSS                 |
| Icons           | Lucide React                     |
| Backend         | Node.js, Express.js              |
| Database        | Supabase / PostgreSQL            |
| AI Integration  | OpenAI API                       |
| Accessibility   | Semantic HTML, Web Speech API    |
| Offline Support | Progressive Web App technologies |

## 📁 Project Structure

```text
digiroot/
├── src/
│   ├── components/
│   ├── pages/
│   ├── data/
│   ├── hooks/
│   ├── utils/
│   ├── App.jsx
│   ├── App.css
│   └── index.css
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── app.js
│   │   └── server.js
│   ├── .env.example
│   └── package.json
│
├── public/
├── .gitignore
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/tsionkinde/digiroot-accessible-learning.git
```

### 2. Start the Frontend

```bash
cd digiroot-accessible-learning
npm install
npm install lucide-react
npm run dev
```

The frontend will normally be available at:

```text
http://localhost:5173
```

### 3. Start the Backend

Open another terminal:

```bash
cd digiroot-accessible-learning/backend
npm install
npm run dev
```

The backend will run at:

```text
http://localhost:5000
```

### 4. Test the Backend

Open this endpoint in your browser:

```text
http://localhost:5000/api/health
```

You should receive a response similar to:

```json
{
  "success": true,
  "message": "DIGIROOT backend is running!",
  "status": "healthy"
}
```

## 🔐 Environment Variables

Create a `.env` file inside the `backend/` directory.

```env
PORT=5000
FRONTEND_URL=http://localhost:5173

SUPABASE_URL=
SUPABASE_SERVICE_ROLE_KEY=

OPENAI_API_KEY=
OPENAI_MODEL=
```

Keep your API keys private. Never commit your `.env` file or expose secret keys in frontend code.

## 🌱 Project Vision

We believe every child deserves the opportunity to participate in the digital world.

DIGIROOT is built around the idea that access to technology and accessible learning should not depend on where a child lives or how they interact with technology.

By combining inclusive design, beginner-friendly education, and offline-first thinking, we aim to help create a future where every child can grow their digital skills.

## 👩‍💻 Development

DIGIROOT is currently under development as an accessibility-focused hackathon project.

Features and integrations are being implemented incrementally.

## 📄 License

This project is currently developed for educational and hackathon purposes. A formal open-source license can be added later.

---

**DIGIROOT – Accessible digital learning for every child, everywhere. 🌱**
