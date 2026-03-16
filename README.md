# cloud-support-ticket-analyzer-
angular, python,, nlp, google cloud
# Cloud Support Ticket Analyzer

A cloud-based web platform that analyzes customer support tickets and predicts category, sentiment, and priority using machine learning.

## Features

- Upload support ticket dataset
- Predict sentiment and category
- Automatic ticket prioritization
- Dashboard for analytics
- Cloud deployment

## Tech Stack

Frontend
- Angular

Backend
- Python (FastAPI / Flask)

Machine Learning
- Scikit-learn
- NLP preprocessing

Cloud
- Google Cloud Run

Storage
- Google Cloud Storage

## System Flow

User uploads support ticket data  
Backend processes text and extracts features  
ML model predicts sentiment and priority  
Results displayed on dashboard

## Running Locally

Backend

pip install -r requirements.txt  
python app/main.py

Frontend

npm install  
ng serve

## Future Improvements

- Real-time ticket streaming
- AI-based response suggestions
- Integration with helpdesk platforms
