# Ujjwal.AI [Quick] – AI SaaS Platform

Ujjwal.AI [Quick] is a full-stack AI SaaS application that provides AI-powered tools for content creation, image generation, and resume analysis.

## 🌐 Live Demo

https://saas-ai-mauve.vercel.app


## 📸 Project Screenshots

### Dashboard

![Dashboard](https://github.com/Ujjwal15-coder/Quick-AI-Ujjwal.AI-/blob/main/Dashboard.png?raw=true)

### AI Tools

![AI Tools](https://github.com/Ujjwal15-coder/Quick-AI-Ujjwal.AI-/blob/main/AI%20Tools.png?raw=true)

### Pricing

![Pricing](https://github.com/Ujjwal15-coder/Quick-AI-Ujjwal.AI-/blob/main/Pricing.png?raw=true)

## ✨ Features

- AI Article Generator
- AI Blog Title Generator
- AI Image Generator
- AI Resume Review
- Background Removal
- Object Removal from Images
- Community content sharing
- Secure authentication with Clerk

## 🛠 Tech Stack

Frontend
- React
- Vite
- Tailwind CSS
- Clerk Authentication

Backend
- Node.js
- Express.js
- PostgreSQL

AI & Cloud Services
- Gemini API
- Cloudinary
- ClipDrop API

## 📂 Project Structure

SAAS-AI  
│  
├── client (React frontend)  
├── server (Node.js backend)  

⚙️ Installation & Setup
Prerequisites

Make sure you have the following installed:

Node.js
npm
PostgreSQL````markdown
## ⚙️ Installation & Setup

### Prerequisites

Make sure the following tools are installed on your system:

- Node.js
- npm
- PostgreSQL
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Ujjwal15-coder/Quick-AI-Ujjwal.AI-.git
cd Quick-AI-Ujjwal.AI-
````

### 2. Install Frontend Dependencies

```bash
cd client
npm install
```

### 3. Install Backend Dependencies

Open a new terminal and run:

```bash
cd server
npm install
```

### 4. Environment Variables

Create a `.env` file inside the `server` directory and add the required environment variables for the database and external services.

> Keep all API keys and credentials private. Never commit `.env` files to GitHub.

### 5. Start the Backend

From the `server` directory:

```bash
npm run server
```

### 6. Start the Frontend

Open another terminal and run:

```bash
cd client
npm run dev
```

The frontend will be available at the local development URL provided by Vite, usually:

```text
http://localhost:5173
```

---

## 🧪 Testing

The backend APIs can be tested using:

* **Postman** – Test API endpoints and responses
* **Browser Developer Tools** – Inspect requests and errors
* **Network Tab** – Monitor API calls, status codes, and response data

These tools help during development and debugging to verify API requests, authentication, responses, and errors.

---

## 🔐 Security

* Store API keys and credentials in environment variables.
* Never commit `.env` files to the repository.
* Never expose backend secrets in frontend code.
* Keep sensitive configuration on the server side.
* Add environment files and dependencies to `.gitignore`.

### Recommended `.gitignore`

```gitignore
.env
.env.*
node_modules/
```

---

## 👨‍💻 Author

**Ujjwal Srivastava**

* GitHub: [https://github.com/Ujjwal15-coder](https://github.com/Ujjwal15-coder)
* LinkedIn: [https://www.linkedin.com/in/ujjwal-srivastava-844034328](https://www.linkedin.com/in/ujjwal-srivastava-844034328)

```
