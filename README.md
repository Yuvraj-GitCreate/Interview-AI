# 🤖 Interview AI

> AI-powered interview preparation platform for smarter and personalized interview practice.

## 📌 Overview

Interview AI is a full-stack platform designed to help candidates prepare for technical interviews through AI-powered mock interviews, coding assessments, resume analysis, and performance insights.

## ✨ Planned Features

- 🤖 AI-powered mock interviews
- 📄 AI resume analysis
- 💻 Coding assessments
- 📊 Performance dashboard
- 🔐 Secure authentication & JWT
- 👤 User profiles
- 🛠️ Admin panel
- 🎯 Personalized AI feedback

## 🏗️ Architecture

                    ┌─────────────────┐
                    │      User       │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │ React Frontend  │
                    └────────┬────────┘
                             ↓ REST API
                    ┌─────────────────┐
                    │ Spring Boot API │
                    └──────┬──────┬───┘
                           ↓      ↓
                  ┌──────────┐  ┌──────────────┐
                  │PostgreSQL│  │ FastAPI AI   │
                  │ Database │  │   Service    │
                  └──────────┘  └──────┬───────┘
                                       ↓
                                  ┌──────────┐
                                  │  OpenAI  │
                                  └──────────┘