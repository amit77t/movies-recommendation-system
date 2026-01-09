# 🎬 End-to-End Movie Recommendation System  
### Using NLP, TF-IDF & FastAPI

An intelligent **content-based movie recommendation system** that suggests similar movies based on their descriptions using **Natural Language Processing (NLP)** and **TF-IDF vectorization**.  
The system is built end-to-end with a **FastAPI backend** and an **interactive Streamlit frontend**, deployed live for real-world usage.

---

## 🚀 Live Demo
🔗 **Try it here:**  
👉 https://movies-recommendation-system-rruthtyjaf5sbw67qsarlg.streamlit.app/

---

## 🖼️ Project Preview
<img width="1366" height="768" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/7c9c75a7-5e9f-4bf7-a6ba-c2f0d4ea0578" />

### 🎥 Recommendation I
<img width="1366" height="768" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/3c65c873-e449-4b53-b936-b50bf776cc29" />
nterface


---

## 📌 Key Features
- 🔍 **Content-Based Recommendations** using movie metadata
- 🧠 **NLP-powered similarity matching**
- 📊 **TF-IDF Vectorization** for text analysis
- ⚡ **FastAPI backend** for high performance
- 🎨 **Streamlit frontend** for interactive UI
- 🌐 **Fully deployed & accessible online**
- 🧩 Clean, modular, and scalable architecture

---

## 🛠️ Tech Stack

### 🔹 Backend
- **Python**
- **FastAPI**
- **Scikit-learn**
- **TF-IDF Vectorizer**
- **Cosine Similarity**

### 🔹 Frontend
- **Streamlit**
- **TMDB API (for posters & metadata)**

### 🔹 Machine Learning / NLP
- Natural Language Processing (NLP)
- Text preprocessing (stopwords, stemming)
- Feature extraction using TF-IDF

---

## 🧠 How It Works

1. Movie descriptions are cleaned and preprocessed using NLP techniques.
2. Text data is converted into numerical vectors using **TF-IDF**.
3. **Cosine Similarity** is applied to find similar movies.
4. FastAPI serves recommendation results via REST APIs.
5. Streamlit consumes the API and displays recommendations with posters.

---

## 📂 Project Structure
```bash
movie-recommendation-system/
│
├── backend/
│   ├── main.py          # FastAPI entry point
│   ├── model.py         # Recommendation logic
│   ├── utils.py         # Preprocessing utilities
│
├── frontend/
│   ├── app.py           # Streamlit application
│
├── data/
│   └── movies.csv       # Dataset
│
├── requirements.txt
└── README.md
````

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system

### 2️⃣ Create Virtual Environment & Install Dependencies

pip install -r requirements.txt

### 3️⃣ Run Backend

uvicorn backend.main:app --reload

### 4️⃣ Run Frontend

streamlit run frontend/app.py

### 👨‍💻 Author

Amit Chaurasia
🎓 B.Tech (AIML) | 💻 Full Stack & ML Enthusiast

GitHub: https://github.com/amit77t

LinkedIn: https://www.linkedin.com/in/amit-chaurasia-0b9976290

Portfolio: https://amit778.netlify.app/
