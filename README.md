# SurveilAI – Real-Time Crime Detection System

SurveilAI is a real-time video surveillance web application that leverages machine learning and computer vision to detect suspicious or criminal activities from live video feeds. The system is designed to assist organizations in proactive monitoring by generating alerts and maintaining detailed incident logs for further analysis.

This project was developed as a college group project, with collaborative efforts across system design, backend development, and machine learning components.

## Key Features
- Real-time video feed processing  
- Machine learning–based activity detection  
- Alert generation for detected incidents  
- Incident logging for monitoring and reporting  
- Web-based interface for system interaction  

## Tech Stack
- Backend: Python, Flask  
- Machine Learning & Computer Vision: OpenCV, ML models  
- Database: MongoDB  
- Frontend: HTML, CSS, JavaScript  
- Version Control: Git, GitHub  

## My Contribution
As part of the project team, my primary responsibilities included:
- Designing and implementing the machine learning pipeline for video frame analysis  
- Integrating real-time detection logic with the backend  
- Implementing incident logging and alert-trigger mechanisms  
- Assisting in system integration and testing  


## **Steps to Run the Project**

### 1. **Clone the Repository**  
```bash
   git clone https://github.com/prathmesh-27/SurveilAI
   cd SurveilAI
```

### 2. **Update the MongoDB URI**  
Open config.py
 
Replace the placeholder MongoDB URI with your MongoDB Atlas URI:

```bash    
    MONGO_URI = os.getenv('MONGO_URI', '#your_mongo_URI')
  ```
   Ensure your MongoDB database has the following collections:
   
 * Camera
   
 * Organization
   
 * Payment

### 3. ***Set Email Credentials***
* In the config.py file, configure your email and Google-generated app password for sending notifications:
```
    MAIL_USERNAME = os.getenv('EMAIL_USER', '# Your email address')  
    MAIL_PASSWORD = os.getenv('EMAIL_PASS', '# Your app password generated from Google')   
```
### 4. Install Dependencies
Install the required Python packages listed in the requirements.txt file:

```bash
pip install -r requirements.txt
```
### 5. Activate the Virtual Environment
If you're using a virtual environment, activate it:

On Windows:
```bash
venv\Scripts\activate
```
### 6. Run the Application
Start the Flask application:

```
python run.py
```

### 7. Access the Application
Open your browser and navigate to:
```
http://127.0.0.1:5000/
```
### 8. Create an Account
* Before using the application, register an account through the registration page.
* Follow the on-screen instructions to complete the process.
  
## Disclaimer
This project was developed for academic and learning purposes as part of a college group project.
