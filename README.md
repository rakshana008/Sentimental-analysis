🧠 Sentiment Analysis Web App
This project is a Flask-based web application that performs sentiment analysis on user-inputted text using a pre-trained machine learning model hosted via an external API (such as Azure ML or HuggingFace). The app classifies input as Positive or Negative.


🚀 Features
Simple web UI to enter and analyze text

Uses external API for accurate sentiment prediction

Secure API key configuration via .env file

Real-time classification result display

Modular code structure for easy maintenance

🛠️ Tech Stack
Backend: Python, Flask

Frontend: HTML (Jinja templates)

Sentiment Model: External ML API (HuggingFace or Azure)

Security: dotenv for API key management

📁 Project Structure
graphql
Copy
Edit
├── app.py                  # Flask application entry point
├── sentiment_analysis.py  # Handles API requests for sentiment
├── config.py              # Loads API key and URL from .env
├── templates/
│   └── index.html         # Web UI template
├── .env                   # Environment variables (not committed)
├── .gitignore             # Ignore rules
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

⚙️ Setup Instructions
1. 🔧 Prerequisites
Python 3.x installed
pip installed

2. 📦 Install Dependencies
Run the following in your terminal:
pip install -r requirements.txt

▶️ Running the App
Launch the Flask app using:
python app.py

💬 How to Use
Enter any sentence in the input box.
Click Analyze Sentiment.
View whether the text is Positive or Negative.




