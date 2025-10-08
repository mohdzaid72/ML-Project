# 🎬 Movie Recommendation System

A **personalized movie recommendation system** built with **Python, Streamlit, and machine learning**, capable of suggesting movies similar to a user’s choice, along with dynamic movie posters. This project demonstrates **content-based recommendation, data preprocessing, similarity computation, and interactive web app development**.

---

## 🚀 Project Overview

This system recommends the top 5 movies similar to a selected movie using **cosine similarity** on preprocessed movie metadata such as **genres, cast, director, and keywords**.  
It provides a **rich, interactive frontend** built with **Streamlit** and fetches **real-time movie posters** via the **TMDb API**.

**Key Highlights:**
- Intelligent movie recommendations based on content similarity.
- Interactive web app for easy exploration.
- Real-time poster display for enhanced user experience.

---

## 🧠 Features

- 🎯 **Content-Based Recommendations** — Suggests movies based on metadata similarity.  
- 🖼️ **Dynamic Poster Fetching** — Integrates with TMDb API to show movie posters.  
- 🌐 **Interactive Frontend** — Built with Streamlit; user-friendly dropdown and button interface.  
- 💾 **Preprocessed & Optimized Data** — Uses pickle files for fast, real-time performance.  
- ⚡ **Scalable Architecture** — Easy to extend with more movies or advanced recommendation algorithms.

---

## 🏗️ Project Structure

```
Movie-Recommender/
│
├── model/
│   ├── movie_list.pkl       # Preprocessed movie dataset
│   └── similarity.pkl       # Cosine similarity matrix
│
├── app.py                   # Streamlit frontend
├── movies.csv               # Raw movie dataset
├── requirements.txt         # Dependencies
└── README.md                # Project documentation
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | Streamlit |
| **Backend** | Python, Pandas, NumPy |
| **Recommendation** | CountVectorizer, Cosine Similarity |
| **API Integration** | TMDb API for movie posters |
| **Data Storage** | Pickle files (`.pkl`) |
| **Version Control** | Git & GitHub |

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/movie-recommender.git
cd movie-recommender
```

2. **Create and activate a virtual environment**
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the Streamlit app**
```bash
streamlit run app.py
```

5. **Select a movie** from the dropdown and click **Show Recommendation** to see top 5 similar movies with posters.

---

## 🎨 Demo

![Movie Recommender Screenshot](https://i.imgur.com/YourDemoImage.png)  
*Interactive UI displaying recommended movies with posters.*

**Example:**  
- Selected Movie: `Avatar`  
- Recommended Movies: `Titanic`, `Guardians of the Galaxy`, `Interstellar`, `The Avengers`, `Inception`

---

## 🔮 Future Enhancements

- Integrate **user-based collaborative filtering** for personalized recommendations.  
- Add **multi-modal features** like plot summaries or reviews.  
- Deploy as a **cloud-hosted app** (Heroku, Streamlit Cloud, or AWS).  
- Add **real-time user feedback** to refine recommendations dynamically.

---

## 🧑‍💻 Author

**Ayaan Turk**  
📧 mohdzaidonly@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | 🔗 [GitHub](https://github.com/your-username)  

---

## 📜 License

This project is licensed under the **MIT License** — free to use and modify.  

---

⭐ **If you find this project interesting, consider giving it a star!**
