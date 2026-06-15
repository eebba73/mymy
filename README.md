# Secure Online Examination System (SOES)

A comprehensive secure online examination platform with anti-cheat features, student management, exam monitoring, and real-time reporting.

## Features

### Admin Features
- Secure login
- Student registration and management
- Password reset
- Exam creation, editing, deletion, and monitoring
- Question and answer management
- Real-time student monitoring
- Results and reports export
- Cheating detection and reporting

### Student Features
- Secure login with admin-assigned credentials
- Profile management
- Take assigned exams
- View results (if allowed)

### Exam Features
- One question per screen
- Question navigation bar
- Countdown timer
- Auto-submit on time expiry
- Exam summary before submission
- Auto-save answers

### Anti-Cheat Features
- Tab switching detection
- Window switching detection
- Alt+Tab detection
- Browser minimize detection
- Copy/paste prevention
- Right-click prevention
- Screen activity recording
- Automatic cheating reports

### Secure Exam Browser (Electron)
- Full-screen kiosk mode
- Website locking
- Navigation blocking
- Browser controls disabled
- Security violation recording

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Secure Browser: Electron.js

## Project Structure
```
soes/
├── backend/
├── frontend/
├── secure-browser/
├── database/
└── docs/
```

## Installation & Setup
See individual README files in each directory.
