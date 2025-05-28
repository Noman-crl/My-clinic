# Clinic Management App

## Features
- User authentication (admin, doctor, receptionist)
- Patient, doctor, appointment, billing management
- Subscription check (trial/active/expired)
- Cloud-ready PostgreSQL database

## Setup

1. Clone the repo and enter the directory:
   ```
   git clone <your_repo_url>
   cd clinic_mgmt
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Copy `.env.example` to `.env` and fill in your secrets and database URL.

4. Initialize the database:
   *(You may use Flask-Migrate or create tables manually)*

5. Run the app:
   ```
   python app.py
   ```

## Deployment
- Ready for local or cloud deployment (Heroku, Render, etc.) 