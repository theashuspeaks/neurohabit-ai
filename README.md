# 🧠 NeuroHabit AI

An AI-powered habit tracking platform that combines behavioral analytics, streak tracking, and personalized coaching to help users build lasting habits and maintain consistency.

Built using the MERN stack and powered by Google Gemini AI, NeuroHabit AI transforms daily habit data into actionable insights, recovery strategies, and personalized recommendations.

---

## 🌟 Key Highlights

* 🤖 Google Gemini AI Integration
* 📈 Advanced Habit Analytics
* 🔥 Streak & Consistency Tracking
* 🧠 AI-Powered Coaching System
* 📊 GitHub-Style 90-Day Activity Heatmap
* 💡 Personalized Habit Recommendations
* 📄 AI Weekly Performance Reports
* 🌙 Light & Dark Theme Support
* 📱 Fully Responsive Design
* 🔐 Secure JWT Authentication

---

## 🧠 AI Features

### AI Weekly Performance Reports

Generates detailed weekly reports based on habit completion rates, streak performance, consistency trends, and behavioral patterns.

### AI Habit Recommendations

Suggests personalized habits based on:

* User goals
* Existing routines
* Productivity patterns
* Historical performance
* Behavioral insights

### AI Recovery Coach

Automatically detects broken streaks and generates personalized recovery plans to help users regain momentum and maintain consistency.

### AI Habit Analysis Chat

Provides a natural language interface where users can ask questions about their progress and receive AI-generated insights based on real habit data.

### AI Daily Motivation

Generates personalized motivational messages using user activity, habit performance, and streak history.

---

## 📊 Analytics & Insights

### Habit Performance Dashboard

* Weekly Progress Tracking
* Monthly Performance Analysis
* Category-Based Statistics
* Habit Completion Trends
* Top Performing Habits

### Streak Intelligence

* Current Streak Monitoring
* Longest Streak Records
* Consistency Scoring
* Habit Retention Analysis

### GitHub-Style Heatmap

Visualizes user activity across the last 90 days through an interactive contribution-style heatmap for better consistency tracking.

---

## ✨ Core Functionality

### Authentication & Security

* User Registration & Login
* JWT-Based Authentication
* Password Hashing using bcrypt
* Protected API Routes
* Secure Session Management

### Habit Management

* Create New Habits
* Edit Existing Habits
* Delete Habits
* Archive Habits
* Category Management
* Custom Colors & Icons
* Flexible Target-Day Configuration

### Daily Tracking

* One-Click Habit Completion
* Real-Time Progress Updates
* Progress Indicators
* Achievement Celebrations
* Daily Activity Logging

### Statistics & Reporting

* Weekly Reports
* Monthly Analysis
* Completion Rate Tracking
* Habit Rankings
* Performance Comparisons
* Behavioral Trend Analysis

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS v4
* React Router DOM
* Axios

### Backend

* Node.js
* Express.js
* JWT Authentication
* bcrypt

### Database

* MongoDB Atlas
* Mongoose ODM

### Artificial Intelligence

* Google Gemini API

---

## 📂 Project Structure

```text
NEUROHABIT-AI
│
├── frontend
│   │
│   ├── public
│   │
│   └── src
│       │
│       ├── components
│       │   ├── charts
│       │   ├── dashboard
│       │   ├── habits
│       │   ├── insights
│       │   ├── statistics
│       │   └── ui
│       │
│       ├── pages
│       │   ├── Login
│       │   ├── Register
│       │   ├── Dashboard
│       │   ├── Weekly
│       │   ├── Statistics
│       │   └── Insights
│       │
│       ├── services
│       │   ├── api
│       │   ├── auth
│       │   ├── habits
│       │   └── ai
│       │
│       ├── hooks
│       ├── context
│       ├── utils
│       └── assets
│
├── backend
│   │
│   ├── controllers
│   │   ├── authController
│   │   ├── habitController
│   │   ├── analyticsController
│   │   └── aiController
│   │
│   ├── routes
│   │   ├── authRoutes
│   │   ├── habitRoutes
│   │   ├── analyticsRoutes
│   │   └── aiRoutes
│   │
│   ├── middleware
│   │   ├── authMiddleware
│   │   ├── errorMiddleware
│   │   └── validationMiddleware
│   │
│   ├── services
│   │   ├── geminiService
│   │   ├── streakService
│   │   ├── reportService
│   │   ├── recoveryService
│   │   └── analyticsService
│   │
│   ├── models
│   │   ├── User
│   │   ├── Habit
│   │   ├── Completion
│   │   └── Report
│   │
│   ├── config
│   ├── database
│   └── server.js
│
├── screenshots
├── docs
├── README.md
└── package.json
```

---

## 🏗️ System Architecture

```text
Frontend (React + Vite)
        │
        ▼
REST API Layer (Express.js)
        │
        ├── Authentication Service
        ├── Habit Management Service
        ├── Analytics Engine
        └── AI Intelligence Layer
                    │
                    ▼
           Google Gemini API
                    │
                    ▼
          MongoDB Atlas Database
```

---

## 🔒 Security Features

* JWT-Based Authentication
* Password Hashing with bcrypt
* Protected API Routes
* Environment Variable Security
* Request Validation Middleware
* Secure User Data Storage

---

## 🎯 Problem Solved

Most habit-tracking applications only record user activity and provide basic statistics.

NeuroHabit AI goes beyond simple tracking by analyzing behavioral patterns, identifying consistency gaps, detecting broken streaks, and generating AI-powered coaching strategies that help users build sustainable habits and achieve long-term goals.

---

## 🚀 Future Enhancements

* Habit Sharing & Community Challenges
* AI-Powered Goal Planning
* Smart Notifications & Reminders
* Calendar Integrations
* Productivity Score System
* Team Accountability Features
* Mobile Application (React Native)

---

## 📂 Repository

GitHub Repository:

https://github.com/theashuspeaks/neurohabit-ai

---

## 👨‍💻 Developer

**Ashutosh Mishra**

GitHub: https://github.com/theashuspeaks

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub and sharing your feedback.
