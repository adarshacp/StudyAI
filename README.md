# StudyAI 🤖

An AI-powered study assistant built as a full-stack application using **React, FastAPI, MySQL, and Hugging Face**.

## 📌 Project Overview

StudyAI is a web application designed to help students learn more effectively using AI-powered features.

The application will provide tools for studying, understanding learning materials, generating questions, and tracking study progress.

The project is being developed from scratch to understand how a complete AI-powered full-stack application works.

---

## 🎯 Objectives

* Build a complete full-stack web application.
* Learn how frontend and backend communicate through REST APIs.
* Implement secure user authentication.
* Store and manage user data using MySQL.
* Integrate pretrained AI models from Hugging Face.
* Run AI models locally during development.
* Build practical AI features for students.
* Learn how to test and deploy an AI application.

---

## ✨ Planned Features

### 🔐 Authentication

* User registration
* User login
* Password hashing
* JWT-based authentication
* Protected routes
* Logout

### 📚 Study Features

* Create and manage study notes
* Organize learning materials
* View study history
* Track learning progress

### 🤖 AI Features

* AI question answering
* Text summarization
* Question generation
* Quiz generation
* Quiz evaluation
* Feedback analysis

### 📊 Dashboard

* User profile
* Study activity
* Quiz scores
* AI usage history
* Learning progress

---

## 🛠️ Technology Stack

### Frontend

* React
* HTML
* CSS
* JavaScript

### Backend

* Python
* FastAPI

### Database

* MySQL

### AI / Machine Learning

* Hugging Face Transformers
* PyTorch

### Development Tools

* Git
* GitHub
* Visual Studio Code

---

## 🏗️ System Architecture

```text
                    StudyAI
                       │
                       ▼
                ┌─────────────┐
                │   React     │
                │  Frontend   │
                └──────┬──────┘
                       │
                  REST API
                       │
                       ▼
                ┌─────────────┐
                │   FastAPI   │
                │   Backend   │
                └──────┬──────┘
                       │
              ┌────────┴────────┐
              ▼                 ▼
        ┌──────────┐      ┌──────────────┐
        │  MySQL   │      │ Hugging Face │
        │ Database │      │    Models    │
        └──────────┘      └──────────────┘
```

---

## 📂 Project Structure

The project structure will evolve as development progresses.

```text
StudyAI/
│
├── backend/
│
├── frontend/
│
├── docs/
│
├── .gitignore
│
└── README.md
```

---

## 🤖 AI Models

The project will use pretrained models available through the Hugging Face ecosystem.

Models will be selected based on the requirements of individual AI features.

Possible tasks include:

* Sentiment analysis
* Text summarization
* Question answering
* Text generation
* Question generation

---

## 🔐 Security

The application will implement:

* Password hashing
* JWT authentication
* Protected API endpoints
* Environment variables for sensitive configuration
* Secure database access

Sensitive information such as passwords, API keys, and database credentials will **not** be committed to GitHub.

---

## 🚀 Development Roadmap

* [x] Create GitHub repository
* [x] Clone repository locally
* [x] Initial project documentation
* [ ] Set up FastAPI backend
* [ ] Create backend project structure
* [ ] Connect MySQL
* [ ] Design database
* [ ] Implement user registration
* [ ] Implement authentication
* [ ] Set up React frontend
* [ ] Connect frontend with FastAPI
* [ ] Integrate Hugging Face models
* [ ] Implement AI features
* [ ] Build student dashboard
* [ ] Add testing
* [ ] Improve security
* [ ] Deploy application

---

## 📖 Learning Goals

Through this project, the goal is to understand:

```text
Frontend
   ↓
REST API
   ↓
Backend
   ↓
Database
   ↓
AI Model
   ↓
Response
   ↓
Frontend
```

The project will be developed incrementally so that each component is understood before moving to the next stage.

---

## 👨‍💻 Developer

**Adarsh**

B.E. Computer Science and Engineering

---

## 📜 License

License information will be added later.
