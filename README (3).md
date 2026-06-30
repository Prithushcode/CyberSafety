# CyberSafe

A gamified cybersecurity awareness platform built using Flask and Supabase, designed to educate non-technical users through interactive learning modules, assessments, progress tracking, and achievement-based rewards.

## Overview

CyberSafe is a full-stack web application that delivers cybersecurity education through a structured learning pathway. Users progress through ten cybersecurity awareness modules, complete interactive assessments, earn achievement badges, and track their learning progress through a gamified experience.

## Core Features

### User Authentication
- Secure user registration and login
- Password hashing using Werkzeug
- Session management using Flask-Login
- Protected routes and authenticated access control

### Learning Modules
1. Spotting Phishing Emails
2. Creating Strong Passwords
3. Recognizing Scam Websites
4. Verifying Strange Payment Requests
5. Safe Use of Public Computers
6. Avoiding Password Reuse
7. Managing App Permissions
8. Handling Unknown Email Attachments
9. Verifying Secure Websites (HTTPS)
10. Two-Factor Authentication (2FA)

### Assessment Engine
- Pre-assessment and post-assessment quizzes
- Automated score calculation
- Improvement percentage tracking
- Badge eligibility evaluation

### Gamification System

| Badge | Requirement |
|---------|---------|
| Bronze | Complete 3 modules |
| Silver | Complete 6 modules |
| Gold | Complete all 10 modules |
| Diamond | Achieve 30%+ assessment improvement |

### Administrative Dashboard
- User monitoring
- Assessment review
- Feedback management
- CSV export functionality
- Completion statistics

## Technology Stack

### Backend
- Python
- Flask
- Flask-Login
- SQLAlchemy
- Werkzeug

### Frontend
- HTML5
- CSS3
- JavaScript
- CSS Grid
- Flexbox

### Database
- Supabase
- PostgreSQL
- SQLAlchemy ORM

### Deployment
- Render Cloud Platform

### Monitoring
- Uptime Robot

## Security Implementation

- Password hashing
- Session management
- Route-level access control
- SQLAlchemy ORM protection
- Authentication validation
- Secure session handling

## Performance Highlights

- 90.3% completion rate
- 87.5% learning improvement rate
- 100% positive usability feedback
- 94.6% increase in user confidence
