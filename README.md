# 🎬 Movie Recommender System

A simple and interactive **Streamlit-based content-based movie recommender system**. Select a movie, and it recommends similar movies using cosine similarity on vectorized features.

🔗 **Live App**: [Click to Open](https://vaxkkaezk37byoy3gznqeb.streamlit.app/)

---

## 💡 Features

- Select any movie from the dropdown
- Get top 5 similar movie recommendations
- Powered by content-based filtering using cosine similarity
- Built with lightweight Python libraries and Streamlit UI

---

## 🚀 How It Works

- Uses a precomputed **similarity matrix** (`similarity.pkl`)
- The `movie_dict.pkl` contains details of movies (like title, ID, etc.)
- When a movie is selected, its similarity scores with all other movies are computed
- The top 5 most similar (excluding itself) are shown as recommendations

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**: Pandas, Pickle (for model loading)

---

## 📦 requirements.txt

pandas
numpy
scikit-learn
streamlit


---

## 💻 Run Locally

```bash
# 1. Clone the repository
```
[git clone https://github.com/yourusername/movie-recommender.git
](https://github.com/gourab-9/movie_recommender_system)
```
cd movie-recommender

# 2. (Optional) Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run app.py
```

# 📦 Files in the Repository
- app.py – Main Streamlit app script
- movie_dict.pkl – Dictionary of movie titles and IDs
- similarity.pkl – Cosine similarity matrix for recommendations
- requirements.txt – Dependencies list

![image](https://github.com/user-attachments/assets/e06c4f10-98c6-419e-b0f5-413f8074c882)
