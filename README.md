# Civic Tracker – MyVoice 🏙️

Civic Tracker is a web application that makes it easier for people to report and keep track of local civic issues.

Users can report problems like potholes, garbage, water supply issues, streetlights, etc. They can also support complaints raised by others and track their status.

The project also includes a small **machine learning system** that gives each complaint a priority score based on its description and category.

### Features

* 👤 User signup and login
* 📝 Report civic issues with images and location
* 👍 Support other complaints
* 🔎 Search and filter complaints
* 📊 Admin dashboard to manage complaints
* 🔄 Track complaint status
* 🤖 ML-based complaint priority prediction

### Tech Stack

**Frontend:** React.js, JavaScript, CSS
**Backend:** Node.js, Express.js
**Database:** MongoDB
**ML:** Python, Flask, Scikit-learn, TF-IDF, Random Forest

### How it works

```text
Report Issue
     ↓
Complaint is stored
     ↓
ML assigns priority
     ↓
Admin reviews it
     ↓
Status is updated
     ↓
Issue gets resolved
```

### Running the Project

```bash
# Backend
cd backend
npm install
node server.js

# Frontend
cd frontend
npm install
npm start

# ML
cd model_training
pip install -r requirements.txt
python app.py
```

## Project Goal

The idea behind Civic Tracker is simple: **make it easier for citizens to report problems and easier for authorities to keep track of them.**
