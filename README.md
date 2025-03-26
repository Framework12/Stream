🎬 Video Streaming Demo
A Netflix-inspired video streaming platform that features a custom video player and supports HLS streaming.

🚫 Note: Image optimization is disabled due to Fair Use Policy.

🚀 Features
✅ Custom Media Player – Built-in player for an immersive viewing experience.
✅ HLS Streaming – Streams video content following the HLS (HTTP Live Streaming) protocol.
✅ Middleware & Edge Functions – Handles profile selection efficiently using Edge Functions for lightning-fast redirection.
✅ TMDb API Integration – Fetches movie details using the TMDb API.


🎥 Custom Media Player
This platform features a fully customized media player built from scratch.

📸 Preview:
https://streaming-platform-tmdb.vercel.app/

📌 Getting Started
Follow these steps to set up the project on your local machine.

1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/repository-name.git
cd repository-name
2️⃣ Set Up Environment Variables
Copy the contents of .env.public into your local .env file and fill in the missing fields.

3️⃣ Install Dependencies
bash
Copy
Edit
npm install
# or
yarn install
4️⃣ Start the Development Server
bash
Copy
Edit
npm run dev
# or
yarn dev
5️⃣ Open the App
Once the server is running, open your browser and go to:
🔗 http://localhost:3000

📡 API Integration
The project uses the TMDb API to fetch movie data.

Base URL:

arduino
Copy
Edit
https://api.themoviedb.org/3/
Example Endpoints:

🎬 Get Popular Movies → /movie/popular

🔍 Search for a Movie → /search/movie?query=Inception

📌 Get Movie Details → /movie/{movie_id}

📂 Project Structure
bash
Copy
Edit
📦 project-root
 ┣ 📂 public            # Static assets (images, icons, etc.)
 ┣ 📂 src
 ┃ ┣ 📂 components      # Reusable components
 ┃ ┣ 📂 pages           # Application pages
 ┃ ┣ 📂 utils           # Helper functions
 ┃ ┣ 📜 styles.css      # Global styles
 ┣ 📜 .env              # Environment variables
 ┣ 📜 package.json      # Dependencies & scripts
 ┣ 📜 README.md         # Project documentation
📢 Contributing
We welcome contributions! Feel free to submit a PR with improvements. 🎉

📜 License
This project is licensed under the MIT License.