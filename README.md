# Email Spam Detection using Machine Learning

This project is a machine learning–based Email Spam Detection system with a simple Flask web interface.  
It classifies emails as **Spam** or **Not Spam** using NLP techniques and a trained supervised learning model.


## Features

- Classifies email text as **Spam / Not Spam**
- Uses **NLP + Machine Learning**
- Flask-based web application
- Pre-trained model loaded using Pickle
- Simple and intuitive UI
- Fast real-time predictions


## Machine Learning Approach

- **Text Preprocessing**
  - Tokenization
  - Stopword removal
- **Feature Extraction**
  - TF-IDF Vectorization
- **Model**
  - Supervised classification model trained using scikit-learn
- **Evaluation Metrics**
  - Precision
  - Recall
  - F1-score (important for imbalanced spam data)



## Tech Stack

- **Programming Language:** Python  
- **Machine Learning:** Scikit-learn  
- **NLP:** TF-IDF Vectorizer  
- **Backend:** Flask  
- **Frontend:** HTML, CSS  
- **Model Serialization:** Pickle  



## Project Structure

EmailSpamDetection/
│
├── app.py
├── spam_classifier.pkl
├── templates/
│ └── index.html
├── requirements.txt
└── README.md


## Installation & Setup

### 1. Clone the repository
git clone https://github.com/Abhinavdhara/EmailSpamDetection.git
cd EmailSpamDetection

### 2.Create and activate virtual environment
python -m venv venv
venv\Scripts\activate


### 3.Install dependencies
pip install flask scikit-learn

### 4.Run the Application
python app.py
Open your browser and go to:
http://127.0.0.1:5000

### How It Works
User enters email content in the web form
Flask sends input to the ML pipeline
Text is vectorized using TF-IDF
Model predicts spam or non-spam
Result is displayed on the UI

### Use Cases

Email filtering systems
NLP-based text classification
Cybersecurity and fraud prevention
Foundational NLP project for ML roles

### Future Improvements

Add prediction probability scores
Convert to REST API
Improve accuracy with advanced NLP models
Bulk email classification
Deploy to cloud platforms

Author

Abhinav Dhara
GitHub: https://github.com/Abhinavdhara
