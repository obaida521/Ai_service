# 🎓 EduPilot AI

## 🌟 Overview

EduPilot AI is an enterprise-grade autonomous school operations platform designed to automate administrative workflows, maintain academic continuity, and provide intelligent insights to educational institutions.

Unlike traditional school management systems, EduPilot AI functions as an intelligent AI agent capable of understanding context, retrieving academic information, generating lessons, monitoring attendance, tracking fee payments, managing notifications, and delivering real-time analytics for school leadership.

The platform combines FastAPI, MongoDB Atlas, and Google Gemini AI to create a complete ecosystem for students, teachers, parents, and administrators.

---

## 🎯 Problems Solved

✅ Teacher absence disrupting classroom learning

✅ Manual attendance monitoring

✅ Delayed fee reminder processes

✅ Lack of real-time school insights

✅ Administrative overload on school management

✅ Limited academic support outside classroom hours

✅ Difficulty maintaining syllabus continuity

---

## 🤖 Core AI Capabilities

### 🧑‍🏫 AI Continuity Teacher

Automatically conducts lessons when a teacher is absent by using syllabus context, chapter progress, and learning objectives.

### 📚 Intelligent Syllabus Engine

Processes uploaded syllabus PDFs and converts them into structured academic knowledge for AI retrieval.

### 🧠 AI Doubt Resolution Engine

Answers only curriculum-related student questions to ensure academic relevance and accuracy.

### 📝 Automated Homework Generator

Creates Easy, Medium, and Hard difficulty assignments aligned with chapter content.

### 📊 Principal Intelligence Dashboard

Provides AI-generated attendance trends, fee analytics, operational insights, and school performance indicators.

### 🔔 Smart Notification System

Automatically triggers alerts and notifications for parents, teachers, and administrators.

### 💰 Fee Management Intelligence

Tracks pending fees and generates professional, personalized reminder messages.

### 📈 Attendance Intelligence

Detects attendance patterns, repeated absences, and potential academic risks.

---

## 🏗️ System Architecture

```text
Students / Teachers / Parents
              │
              ▼
      EduPilot AI Platform
              │
 ┌─────────────────────────┐
 │     FastAPI Backend     │
 └─────────────────────────┘
              │
 ┌─────────────────────────┐
 │     MongoDB Atlas       │
 └─────────────────────────┘
              │
 ┌─────────────────────────┐
 │    Google Gemini AI     │
 └─────────────────────────┘
              │
 ┌─────────────────────────┐
 │     AI Workflows        │
 └─────────────────────────┘
              │
              ▼
 Automated School Operations
```

---

## 🧠 AI Workflow Lifecycle

```text
Teacher Marked Absent
          │
          ▼
Attendance Intelligence
          │
          ▼
Need Continuity Class?
          │
          ▼
Syllabus Context Retrieval
          │
          ▼
AI Continuity Teacher
          │
          ▼
Student Doubt Resolution
          │
          ▼
Homework Generation
          │
          ▼
Parent Notifications
          │
          ▼
Principal Insights Dashboard
```

---

## ⚙️ Technology Stack

### Backend

* Python 3.13
* FastAPI
* Uvicorn

### Database

* MongoDB Atlas
* Motor Async Driver

### Artificial Intelligence

* Google Gemini 2.0 Flash
* Prompt Engineering Framework
* Context-Aware Retrieval

### Supporting Libraries

* Pydantic
* PyPDF2
* python-dotenv

---

## 📊 Key Features

| Module                  | Capability                 |
| ----------------------- | -------------------------- |
| AI Substitute Teacher   | Automated lesson delivery  |
| Attendance Intelligence | Pattern detection & alerts |
| Fee Intelligence        | Automated fee reminders    |
| Homework Generator      | AI-generated assignments   |
| Doubt Engine            | Curriculum-based responses |
| Principal Dashboard     | Real-time analytics        |
| Notification Engine     | Automated alerts           |
| Syllabus Engine         | Academic context retrieval |

---

## 🚀 Future Roadmap

* Multi-school deployment support
* Voice-enabled AI teacher
* Student performance prediction
* Parent mobile application
* Real-time classroom monitoring
* AI-powered examination generation
* Learning analytics dashboard
* Multi-language support

---

## 👨‍💻 Team

| Member     | Role                           |
| ---------- | ------------------------------ |
| Obaida Gul | Backend, AI & Integration Lead |
| Owais Khan | Frontend & UI Development      |


