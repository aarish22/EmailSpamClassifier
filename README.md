# Email/SMS Spam Classifier

This project is a simple web application for classifying emails or SMS messages as spam or not spam using Natural Language Processing (NLP) techniques. The app is built with Streamlit for the frontend and a pre-trained machine learning model for the backend.

## Features

- User-friendly interface for entering email/SMS messages.
- Real-time prediction of whether the input message is spam or not.
- Clean and modern design with vibrant colors and interactive elements.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/spam-classifier.git
   cd spam-classifier
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
import nltk
nltk.download('stopwords')
nltk.download('punkt')
streamlit run app.py
