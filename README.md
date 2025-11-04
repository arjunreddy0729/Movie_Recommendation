# 🎬 Movie Recommendation System

This project is a **content-based movie recommendation system** built using Python, Flask, and Natural Language Processing techniques. It suggests similar movies based on their descriptions and metadata such as genres and keywords.

---

## 🚀 Features

- **Content-Based Filtering** using TF-IDF and Cosine Similarity  
- **Flask Web App** for an interactive user experience  
- **Preprocessed Movie Dataset** (TMDB)  
- **Search Bar Functionality** to find similar movies instantly  
- **Deployed-Ready Structure** for GitHub Pages or local hosting  

---

## 🧠 Tech Stack

- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** Python (Flask)  
- **Libraries:** pandas, numpy, scikit-learn, nltk, pickle  
- **Dataset Source:** TMDB (The Movie Database)

---

## 🧩 Project Structure

project/
│
├── app.py # Main Flask application
├── app.ipynb # Development notebook
├── model/ # Model scripts (preprocessing, recommender)
│ ├── preprocess.py
│ ├── recommender.py
│ └── model_utils.py
├── templates/ # HTML templates
│ └── index.html
├── .gitignore
└── requirements.txt # Required Python libraries

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/arjunreddy0729/Movie_Recommendation.git
   cd Movie_Recommendation
2. Install dependencies
pip install -r requirements.txt

3.Run the Flask app
python app.py
Then open your browser and visit:
👉 http://127.0.0.1:5000/

📊 Model Overview

Vectorizes movie overviews using TF-IDF Vectorizer
Measures movie similarity using Cosine Similarity
Recommends top 5 movies with the highest similarity score
