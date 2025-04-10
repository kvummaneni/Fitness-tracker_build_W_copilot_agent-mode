# Backend Setup

The backend of the Octofit Tracker is built using Django and MongoDB. Below are the steps to set up and run the backend:

## Prerequisites
- Python (v3.8 or later)
- pip (v20 or later)
- MongoDB (running locally or remotely)

## Installation
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure the database connection in `settings.py`.
5. Apply migrations:
   ```bash
   python manage.py migrate
   ```
6. Start the development server:
   ```bash
   python manage.py runserver
   ```

The backend will be available at `http://localhost:8000` by default.