SurveilAI – Real-Time Crime Detection System

SurveilAI is a real-time video surveillance web application that uses machine learning and computer vision to detect suspicious or criminal activities from live video feeds. The system is designed to assist organizations in proactive monitoring by generating alerts and maintaining incident logs for further analysis.

This project was developed as a college group project, with collaborative design and implementation across backend, machine learning, and system integration components.

Key Features

Real-time video feed processing for activity detection

Machine learning–based analysis of video frames

Alert notification system for detected incidents

Incident logging for monitoring and reporting

Web-based dashboard for system interaction

Tech Stack

Backend: Python, Flask

Machine Learning & CV: OpenCV, ML models

Database: MongoDB

Frontend: HTML, CSS, JavaScript

Other Tools: Git, REST APIs

My Contribution

As part of the development team, I primarily worked on:

Designing and implementing the machine learning pipeline for video frame analysis

Integrating real-time detection logic with the backend

Implementing incident logging and alert-trigger mechanisms

Assisting in system integration and testing

Project Status

This project is currently under active development.

Core detection and logging features are functional

Email notification integration and model accuracy improvements are ongoing

Current model accuracy is approximately 72%, with plans for further optimization

Steps to Run the Project
1. Clone the Repository
git clone https://github.com/prathmesh-27/SurveilAI
cd SurveilAI

2. Configure MongoDB

Open config.py and update the MongoDB URI:

MONGO_URI = os.getenv('MONGO_URI', '#your_mongo_URI')


Ensure the database contains the following collections:

Camera

Organization

Payment

3. Set Email Credentials

In config.py, configure email credentials for notifications:

MAIL_USERNAME = os.getenv('EMAIL_USER', '# your email address')
MAIL_PASSWORD = os.getenv('EMAIL_PASS', '# your Google app password')

4. Install Dependencies
pip install -r requirements.txt

5. Activate Virtual Environment (Optional)

On Windows:

venv\Scripts\activate

6. Run the Application
python run.py

7. Access the Application

Open your browser and go to:

http://127.0.0.1:5000/

8. Create an Account

Register using the application’s registration page before accessing features.
