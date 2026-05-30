# 🤖 HMN - Personal AI Assistant

HMN is a full-stack AI chatbot built using FastAPI, Groq LLMs, HTML, CSS, and JavaScript. The application provides an interactive chat experience where users can ask questions related to programming, learning, productivity, career guidance, and general knowledge.

## 🌐 Live Demo

**Frontend:** https://chatbot-project-two-delta.vercel.app/

## 🚀 Features

* AI-powered conversational assistant
* FastAPI backend API
* Groq LLM integration
* Responsive user interface
* Persistent chat history
* Cross-Origin Resource Sharing (CORS) support
* Cloud deployment using Render and Vercel
* Real-time chat interaction
* Error handling for API failures

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Backend

* Python
* FastAPI
* Pydantic
* Groq API
* Python Dotenv

### Deployment

* Vercel (Frontend)
* Render (Backend)

## 📂 Project Structure

```text
chatbot-project/
│
├── backend/
│   ├── backend.py
│   ├── requirements.txt
│   ├── history.json
│   └── .env
│
└── frontend/
    ├── index.html
    ├── styles.css
    └── script.js
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/chatbot-project.git
cd chatbot-project
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Environment Variables

Create a `.env` file inside the backend folder:

```env
GROQ_API_KEY=your_api_key_here
```

### 6. Run Backend

```bash
uvicorn backend:app --reload
```

Backend will run at:

```text
http://localhost:8000
```

### 7. Open Frontend

Open:

```text
frontend/index.html
```

in your browser.

## 🔌 API Endpoint

### Chat Endpoint

```http
POST /chat
```

Request:

```json
{
  "message": "What is FastAPI?"
}
```

Response:

```json
{
  "reply": "FastAPI is a modern Python web framework..."
}
```

## 🎯 What I Learned

This project helped me learn:

* FastAPI fundamentals
* REST API development
* Frontend-backend communication
* JavaScript Fetch API
* Environment variables
* API integration with LLMs
* Deployment using Render and Vercel
* Debugging CORS and deployment issues
* Building full-stack AI applications

## 🔮 Future Improvements

* SQLite/PostgreSQL database integration
* User authentication
* Individual chat sessions
* Markdown support
* Dark mode
* Chat history sidebar
* Streaming AI responses
* Message timestamps
* Mobile UI enhancements

## 📜 License

This project is developed for learning and portfolio purposes.

## 👨‍💻 Author

**Shaik Husamuddin**

B.Tech Computer Science Engineering Student

Passionate about AI Engineering, Full-Stack Development, and Building Real-World Applications.
