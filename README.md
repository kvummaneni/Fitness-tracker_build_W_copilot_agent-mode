🚀 Exploring AI-Powered Development with GitHub Copilot 🚀

Hi everyone! 👋

I recently embarked on an exciting journey to build a fitness tracker app called Octofit Tracker for Merington High School. Inspired by the Monafit Tracker, this project was my first attempt at creating a full-stack application using Django, React, MongoDB, and Bootstrap—all with no prior experience in JavaScript, CSS, or coding!

https://learn.microsoft.com/en-us/training/modules/github-copilot-agent-mode/


# Octofit Tracker

Octofit Tracker is a fitness tracking application designed for Merington High School, inspired by the Monafit Tracker app. It allows users to log activities, manage teams, view leaderboards, and track workouts.

## Features
- User authentication and profiles
- Activity logging and tracking
- Team management and leaderboards
- Personalized workout suggestions

## Tech Stack
- **Frontend**: React, Bootstrap
- **Backend**: Django, MongoDB

## Live Demo
[Live Demo Link](#) *(Replace with actual link once deployed)*

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd octofit-tracker
   ```
3. Set up the backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```
4. Set up the frontend:
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

## License
This project is licensed under the MIT License. See the LICENSE file for details.
