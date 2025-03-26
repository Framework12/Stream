# 🎬 Video Streaming Platform  

A video streaming platform, inspired by **Netflix**, using a **custom video player** and following the **HLS protocol** for streaming.  

> **Note:** Image optimization is disabled due to Fair Use Policy.  

## 🚀 Features  
- ✅ **Custom-built media player**  
- ✅ **Streaming via the HLS protocol**  
- ✅ **Edge function-based profile validation**  
- ✅ **API integration with TMDB**    

## 📡 API Usage  
This project integrates with **The Movie Database (TMDB) API** to fetch movie data.  
📌 [TMDB API Documentation](https://developers.themoviedb.org/3/getting-started/introduction)  

## 🛠️ Middleware & Edge Functions  
- Profile selection is **validated at the edge** to ensure **fast redirection handling**.  
- This enables **static-like performance** while checking user authentication.  

## 🎥 Custom Media Player  
This project features a **custom-built video player** tailored for an optimal streaming experience.  

![Media Player Preview](public/preview-player.png)  

## 📌 Getting Started  

### 1️⃣ Setup Environment Variables  
Copy the contents of `.env.public` to your local `.env` file and **fill in the missing fields**.  

### 2️⃣ Run the Development Server  
Use one of the following commands:  
```bash
npm run dev
# OR
yarn dev

Then, open http://localhost:3000 in your browser.

## 3️⃣ API Routes
All files inside pages/api/ are mapped to /api/* and act as API routes instead of React pages.

## 📜 License
This project is for educational and demonstration purposes only.
