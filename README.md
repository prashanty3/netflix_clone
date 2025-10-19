🧑‍💻 Developer

👤 Prashant Rao
💼 Full Stack Developer | DevOps Enthusiast


# 🎬 Netflix Clone – Watch Your Favorites Anytime!

> A high-performance Netflix clone built using **React.js**, **Tailwind CSS**, and **Vite**, designed to replicate the look and feel of the world’s most popular streaming platform.

---

## 🚀 Features

✅ **Modern UI/UX** inspired by Netflix  
✅ **Responsive design** – works on all devices  
✅ **Dynamic movie listings** with smooth hover animations  
✅ **Fully functional authentication** (Login / Signup)  
✅ **Firebase backend integration**  
✅ **Trailer playback using YouTube API**  
✅ **Optimized with lazy loading and reusable components**  

---

## 🧠 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend | React.js + Vite |
| Styling | Tailwind CSS |
| Backend | Firebase (Auth + Firestore) |
| API | TMDB (The Movie Database API) |
| Deployment | Docker / Vercel / Netlify |

---

## 🧰 Installation & Setup

Follow these steps to run locally 👇

```bash
# Clone the repository
git clone https://github.com/prashanty3/netflix_clone.git

# Navigate into the project folder
cd netflix_clone

# Install dependencies
npm install

# Run the project
npm run dev


Follow these steps to run on Docker 👇

```bash
# Clone the repository
git clone https://github.com/prashanty3/netflix_clone.git

# Navigate into the project folder
cd netflix_clone

# Build Docker image
docker build -t netflix-clone .

# Run the container
docker run -d -p 3000:80 netflix-clone
