
# 🎬 Movie Recommender System

A content-based movie recommendation system built with Python and machine learning. Given a movie title, the system suggests similar movies based on content features such as genre, cast, crew, keywords, and more.

---

## 🚀 Features

- Recommend similar movies based on a selected title
- Uses TF-IDF and cosine similarity
- Clean, intuitive UI with Streamlit
- Stored data using pickle files for faster load
- Large file support via Git LFS (for model files)

---

## 📁 Project Structure

```
movie-recommender-system/
│
├── app.py                     # Streamlit web app
├── similarity.pkl             # Precomputed similarity matrix (tracked by Git LFS)
├── movie_dict.pkl             # Movie metadata dictionary
├── .gitattributes             # Git LFS tracking config
├── requirements.txt           # Python dependencies
└── README.md                  # You're here!
```

---

## 🧪 Installation & Running Locally

1. **Clone the repo**

```
git clone https://github.com/subham-pradhan/movie-recommender.git
cd movie-recommender
```

2. **Install dependencies**

```
pip install -r requirements.txt
```

3. **Run the app**

```
streamlit run app.py
```

## 🛠 Built With

- Python
- Pandas
- Scikit-learn
- Streamlit
- Git LFS

---

## 🧠 How It Works

- Movie metadata is preprocessed from TMDB dataset
- NLP features like genres, keywords, cast, and crew are combined
- TF-IDF vectorization + cosine similarity is used to compute similarity scores
- Results are cached using pickle for performance

---

## 🧊 Notes

- `similarity.pkl` is over 100MB, so it's stored with [Git Large File Storage (LFS)](https://git-lfs.github.com/)
- If cloning the repo, make sure Git LFS is installed:

```
git lfs install
git lfs pull
```

---

## 📸 Demo

![Movie Recommender Demo](https://github.com/subham-pradhan/movie-recommender/assets/demo.gif) <!-- Replace with your actual image/gif -->

---

## 👤 Author

**Subham Pradhan**  
[GitHub](https://github.com/subham-pradhan)

