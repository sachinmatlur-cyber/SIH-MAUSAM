# Mausam Backend Setup

## Requirements
- Python 3.10 or newer
- pip

## Install dependencies
pip install -r requirements.txt

## Start the backend
python app.py

## Test the API
python test_api.py
python check_database.py

## Health check
GET http://127.0.0.1:5000/health

## Personalized homepage
POST http://127.0.0.1:5000/api/homepage
