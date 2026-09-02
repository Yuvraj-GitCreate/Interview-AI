# Phase 0 — Project Setup

## Project
- **Name:** Interview AI
- **Type:** Full-stack AI-powered interview preparation platform

## Tech Stack
- **Frontend:** React *(planned)*
- **Backend:** Spring Boot 4.1.1
- **Language:** Java 21
- **Build Tool:** Maven
- **Database:** PostgreSQL 18
- **AI Service:** Python FastAPI *(planned)*
- **AI:** OpenAI *(planned)*

## Backend Setup
- Spring Boot project created using Spring Initializr
- Package: `com.interviewai.backend`
- Dependencies:
  - Spring Web MVC
  - Spring Boot DevTools
  - Spring Data JPA
  - PostgreSQL JDBC Driver
- Maven build verified successfully

## Server
- Default port `8080` was occupied by Oracle TNS Listener
- Changed Spring Boot port to `8081`
- Server successfully tested at `http://localhost:8081`

## Database Setup
- PostgreSQL 18 installed
- pgAdmin 4 installed
- Database: `InterviewAI`
- Application user: `interviewai_user`
- Dedicated database user used for better security

## Completed
- [x] Java & Maven setup
- [x] Spring Boot project
- [x] Backend dependencies
- [x] Server verification
- [x] PostgreSQL installation
- [x] Database creation
- [x] Application database user

## Next
- [ ] Connect Spring Boot to PostgreSQL
- [ ] Verify database connection
- [ ] Start Phase 1 — Authentication & Security

> **Security:** Never commit database passwords, API keys, or other secrets to GitHub.