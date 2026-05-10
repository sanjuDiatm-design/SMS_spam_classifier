SMS Spam Classifier

A machine learning-based SMS/Email Spam Detection web application built using Python, Scikit-learn, and Streamlit. This project classifies messages as Spam or Not Spam using Natural Language Processing (NLP) techniques.

🚀 Features
Detects spam SMS/Emails instantly
Text preprocessing using NLP
TF-IDF Vectorization
Machine Learning classification model
Interactive web app using Streamlit
🛠️ Technologies Used
Python
Streamlit
Scikit-learn
NLTK
Pandas
NumPy
📂 Project Structure
├── SMS_spam_classifier.py   # Streamlit web app
├── model.pkl                # Trained ML model
├── vectorizer.pkl           # TF-IDF vectorizer
├── SMS_spam_detection.ipynb # Model training notebook
├── requirements.txt         # Required libraries
└── README.md
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-sanjuDiatm/sms-spam-classifier.git
cd sms-spam-classifier
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Download NLTK Data

Run Python and execute:

import nltk
nltk.download('punkt')
nltk.download('stopwords')
▶️ Run the Application
streamlit run SMS_spam_classifier.py
🧠 Machine Learning Workflow
Data Cleaning
Text Preprocessing
Tokenization
Stopword Removal
Stemming
TF-IDF Vectorization
Model Training
Prediction
📸 Demo
Spam Example
Congratulations! You have won a free lottery ticket.
Ham Example
Hey, are we meeting today?
📊 Model Used
Multinomial Naive Bayes
📌 Future Improvements
Add deep learning models
Improve UI design
Deploy on cloud platforms
Add multilingual support
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch
Commit your changes
Push to your branch
Open a Pull Request
📜 License

This project is licensed under the MIT License.
