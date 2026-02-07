# 🎬 MovieIndex

MovieIndex is an open-source movie and web series discovery platform that aggregates publicly available metadata from the **TMDB API**.  

It allows users to explore movies and TV shows, view detailed information, and share reviews and comments.

> ⚠️ MovieIndex does **not host or stream any media content**. It only indexes and displays metadata fetched from third-party APIs.

---

## ✨ Features

- 🔍 Browse and search movies & web series
- 🎞️ Detailed movie/show pages (cast, genres, ratings, trailers, etc.)
- ⭐ User reviews and comments
- 📈 Trending, popular, and top-rated content
- 🧭 IMDb-style indexing and discovery experience

### 🛣️ Planned Features
- 🎥 Streaming platform redirection (Netflix, Prime, etc.)
- 📩 Request a movie/web series using IMDb link
- 👤 User authentication & profiles
- ❤️ Watchlist and favorites
- 🧠 Recommendation system

---

## 🧱 Tech Stack

### Backend
- **FastAPI**
- Python
- TMDB API
- RESTful API architecture

### Frontend
- **React**
- JavaScript
- Fetch/Axios for API calls

### Hosting
- **Backend:** Render (custom domain planned)
- **Frontend:** GitHub Pages

---

## 📁 Project Structure

```

MovieIndex/
│
├── backend/        # FastAPI backend
├── frontend/       # React frontend
├── README.md
├── LICENSE         # MIT License
└── .gitignore

````

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.9+
- Node.js & npm
- TMDB API Key

---

### 🔑 Environment Variables

Create a `.env` file in the `backend` directory:

```env
TMDB_API_KEY=your_tmdb_api_key_here
````

---

### 🚀 Backend Setup (FastAPI)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend will run at:

```
http://localhost:8000
```

---

### 🎨 Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

Frontend will run at:

```
http://localhost:3000
```

---

## 🌐 Deployment

### Backend (Render)

* Connect the `backend` folder to Render
* Set environment variables in Render dashboard
* Use `uvicorn main:app` as start command

### Frontend (GitHub Pages)

* Build React app
* Deploy `build/` directory to GitHub Pages
* Update API base URL to point to Render backend

---

## 🧾 API Attribution

This project uses the **TMDB API** but is **not endorsed or certified by TMDB**.

> “This product uses the TMDB API but is not endorsed or certified by TMDB.”

---

## ⚖️ Legal Disclaimer

MovieIndex does not host, upload, or stream any movies or TV shows.
All content information is sourced from third-party APIs and publicly available metadata.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to open issues, submit pull requests, or suggest new features.

---

## 📬 Contact

If you have ideas, feedback, or feature requests — open an issue or start a discussion 🚀
