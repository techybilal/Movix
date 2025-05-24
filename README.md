# 🎬 Movix - Your Ultimate Movie Database 🎥

![image](https://github.com/user-attachments/assets/22c3b983-92c1-4550-b361-adff164c664f)

*Because every movie lover deserves a perfect watchlist.*

---

## 🚀 About Movix

Movix is a sleek, modern React-based **Movie Database Website** powered by [The Movie Database API (TMDb)](https://www.themoviedb.org/).  
Discover trending movies, search your favorites, and dive deep into movie details — all in one place!

---

## 🌟 Features

- 🔥 Browse Trending Movies & TV Shows  
- 🔍 Search movies by title instantly  
- 🎞️ View detailed movie info: synopsis, ratings, cast, and trailers  
- ⚡ Fast & Responsive UI  
- 🔐 Secure API Key management with environment variables  
- 🎨 Clean and modern design with smooth animations  

---

## 🛠️ Tech Stack

| Technology | Purpose                    |
|------------|----------------------------|
| React.js   | Frontend framework          |
| Vercel     | Hosting & deployment        |
| TMDb API   | Movie data provider         |
| CSS        | Styling & animations        |

---

## 📋 Prerequisites

- Node.js and npm installed locally: [https://nodejs.org/](https://nodejs.org/)  
- A TMDb API key (see below)  
- Git installed (optional, for cloning repo)  

---

## 🎯 How to Get TMDb API Key

1. Go to [TMDb API Documentation](https://developer.themoviedb.org/reference/intro/authentication).  
2. Create a free account or log in.  
3. Navigate to your **API Keys** section.  
4. Apply for an API key (usually the "Developer" key is sufficient).  
5. Copy the **API key** — you will need it to run Movix.

---

## 📝 `.env` File Format

In the root directory of the project, create a `.env` file with this content:

```env
VITE_APP_TMDB_TOKEN=your_api_key_here
```
Replace your_api_key_here with the actual API key you got from TMDb.

## 💻 Getting Started (Run Locally)

1. **Clone the repo:**

   ```bash
   git clone https://github.com/techybilal/Movix.git
   cd Movix
   ```
   
2. **Create your .env file as shown above.**

3. **Install dependencies:**

   ```bash
   npm install
   ```
   
4. Start the development server:

   ```bash
   npm run dev
   ```
