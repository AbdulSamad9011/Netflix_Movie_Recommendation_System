# 🎬 Netflix Movie Recommendation System

A Machine Learning based **Content-Based Movie Recommendation System** that recommends the **Top 5 similar movies** based on movie metadata such as genres, keywords, cast, crew, and overview.

---

## 📌 Project Overview

This project uses **Content-Based Filtering** to recommend movies similar to the movie selected by the user. The recommendation is generated using **Cosine Similarity** on processed movie features.

The project is built using Python and popular data science libraries like Pandas, NumPy, NLTK, and Scikit-learn.

---

## 🚀 Features

- Recommend Top 5 similar movies
- Content-Based Recommendation System
- Uses Cosine Similarity
- Data preprocessing and feature engineering
- Fast recommendation generation
- Simple and easy-to-understand implementation

---

## 📂 Dataset

The project uses the TMDB 5000 Movie Dataset.

Files used:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## ⚙️ Project Workflow

1. Load movie and credits datasets.
2. Merge both datasets.
3. Select useful features.
4. Clean and preprocess the data.
5. Create tags by combining important features.
6. Convert text into vectors using CountVectorizer.
7. Calculate Cosine Similarity.
8. Recommend the Top 5 similar movies.

---

## 📷 Example

### Input

```python
recommend("Avatar")
```

### Output

```
Titan A.E.
Aliens
Guardians of the Galaxy
John Carter
Star Trek Into Darkness
```

---

## 📁 Project Structure

```
Netflix_Movie_Recommendation_System/
│
├── Netflix Movie Recommendation System.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/AbdulSamad9011/Netflix_Movie_Recommendation_System.git
```

### Navigate to the Project Folder

```bash
cd Netflix_Movie_Recommendation_System
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn nltk
```

### Open the Notebook

```bash
jupyter notebook
```

Run all the cells and test recommendations.

---

## 🔮 Future Improvements

- Build a Streamlit Web Application
- Add Movie Posters using TMDB API
- Deploy on Streamlit Cloud
- Improve recommendation accuracy
- Add search functionality
- Recommend movies based on user preferences

---

## 👨‍💻 Author

**Abdul Samad**

B.Tech in Artificial Intelligence

GitHub: https://github.com/AbdulSamad9011

---

## ⭐ If you like this project

If you found this project useful, consider giving it a ⭐ on GitHub.
