# 🧠Sentiment Analysis Web Application(Simple Version)

A beginner-friendly Sentiment Analysis web app built using Python and Streamlit.  
This application analyzes user input text and predicts whether the sentiment is **Positive**, **Negative**, or **Neutral** using TextBlob.


## 📌 Project Overview

This web application allows users to enter any text and instantly receive sentiment feedback along with a polarity score.  
It is lightweight, easy to deploy, and ideal for beginners learning NLP and web deployment.


## ✨ Features

- Real-time sentiment prediction  
- Classifies text as Positive / Negative / Neutral  
- Displays polarity score  
- Simple and clean user interface  
- Lightweight NLP implementation  


## 🛠 Technologies Used

- Python  
- Streamlit  
- TextBlob  


## 📁 Project Structure

sentiment-analysis-app/
│
├── app.py  
├── requirements.txt  
└── README.md  


## ⚙ Installation & Local Setup

Step 1: Install dependencies

py -m pip install streamlit textblob  
py -m textblob.download_corpora  

Step 2: Run the application

py -m streamlit run app.py  

The app will open in your browser at:

http://localhost:8501


## 📄 requirements.txt

streamlit  
textblob  


## 🧪 Sample Input

I love Him 

Output:

Sentiment: POSITIVE 😊  
Polarity Score: 0.5  


## 🌍 Deployment

1. Upload `app.py` and `requirements.txt` to a GitHub repository  
2. Login to Streamlit Community Cloud  
3. Click **New App**  
4. Select your repository  
5. Choose `app.py` as main file  
6. Click **Deploy**

Your app will be live with a public URL.


## 👩‍💻 Author

Dasari Renuka  
B.Tech Computer Science Engineering Student  


## 📜 License

This project is open-source and free for educational purposes.
