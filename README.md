🎬 Video Streaming Demo Platform
A video streaming demo platform, inspired by Netflix, using a custom video player and following the HLS protocol for streaming.

Note: Image optimization is disabled due to Fair Use Policy.

🚀 Features
✅ Custom-built media player
✅ Streaming via the HLS protocol
✅ Edge function-based profile validation
✅ API integration with The Movie Database (TMDB)

🔧 Known Issues & Solutions
1️⃣ Player Reset Issue
Problem: The player does not reset properly when switching videos.

Solution: Move the player store to the watch route for better state management.

📡 API Usage
This project utilizes the TMDB API for fetching movie data.
📌 TMDB API Documentation

🛠️ Middleware & Edge Functions
Profile selection is validated at the edge to ensure fast redirection handling.

This enables static-like performance while checking user authentication.

🎥 Custom Media Player
This project features a custom-built video player tailored for an optimal streaming experience.

⚠️ Due to missing resources, audio and subtitle selection are currently not supported.



📌 Getting Started
1️⃣ Setup Environment Variables
Copy the contents of .env.public to your local .env file and fill in the missing fields.

2️⃣ Run the Development Server
Use one of the following commands:

bash
Copy
Edit
npm run dev
# OR
yarn dev
The project will be available at: http://localhost:3000

3️⃣ API Routes
All files inside pages/api/ are mapped to /api/* and act as API routes instead of React pages.

📜 License
This project is for educational and demonstration purposes.
