🎬 AI Movie Recommendation Engine

A content-based Movie Recommender System built using Machine Learning and deployed with Streamlit.

🚀 Live Demo
👉 https://movie-recommender-jjcgdasvemjwrrdgkrzoec.streamlit.app/

📌 Features
🎯 Recommends similar movies instantly
🧠 Uses cosine similarity for recommendations
🎬 Fetches real-time movie posters using TMDB API
⚡ Fast and interactive UI with Streamlit
🌐 Deployed on cloud
🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
Streamlit
TMDB API
📂 Project Structure

movie-recommender/
│
├── app.py # Streamlit app
├── main.py # Model building
├── movies.pkl # Processed movie data
├── similarity.pkl # Similarity matrix
├── requirements.txt # Dependencies
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv

⚙️ How it works
Preprocessed movie dataset (TMDB 5000)
Combined features like genres, cast, keywords
Applied CountVectorizer
Calculated cosine similarity
Recommended top 5 similar movies
🔑 API Setup

This project uses TMDB API.

Add your API key in Streamlit Secrets:

TMDB_API_KEY = "your_api_key_here"

▶️ Run Locally
git clone https://github.com/anantasatish-1417/movie-recommender.git
cd movie-recommender
pip install -r requirements.txt
streamlit run app.py


📌 Future Improvements
Add movie ratings ⭐
Add search bar 🔍
Add genres filter 🎭
👨‍💻 Author

Ananta Satish
