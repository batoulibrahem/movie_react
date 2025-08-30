🎬 Movie Explorer
A sleek and responsive web app built with React that lets users discover trending movies and search for their favorites using the TMDB API. It features real-time search with debounce, loading indicators, and error handling for a smooth user experience
🚀 Features
🔍 Instant movie search with debounce

📈 Displays trending movies from Appwrite backend

🎞️ Movie cards with posters and titles

⏳ Loading spinner while fetching data

⚠️ Clear error messages for failed requests

🌐 Integration with TMDB API and Appwrite
🛠️ Tech Stack
React

React Hooks (useState, useEffect)

react-use for debounce

TMDB API

Appwrite (for trending movies and search analytics)

📁 Folder Structure
src/
│
├── component/
│   ├── search.jsx
│   ├── spinner.jsx
│   └── moviecard.jsx
│
├── appwrite.js         // Appwrite functions: getTrendingMovies, updateSearchCount
├── App.jsx             // Main component
└── main.jsx            // Entry point
⚙️ Setup Instructions
1-Clone the repository:
git clone https://github.com/your-username/movie-explorer.git
cd movie-explorer
2-Install dependencies:
npm install
3-Configure environment variables:
Create a .env file in the root directory and add your TMDB API key
VITE_TMDB_API_KEY=your_tmdb_api_key_here
4-Run the app:
npm run dev
🧠 Developer Notes
Debounced search reduces API calls for better performance.

Search count is updated via Appwrite when results are found.

Trending movies are fetched from Appwrite on initial load.

📸Screenshots:
<img width="1174" height="668" alt="image" src="https://github.com/user-attachments/assets/54255378-b78a-4496-b214-82ad64a4881c" />
<img width="1329" height="648" alt="image" src="https://github.com/user-attachments/assets/5447b292-96fe-4265-a14e-e4b35db571cc" />
<img width="1297" height="629" alt="image" src="https://github.com/user-attachments/assets/db38d8c2-90c8-49ee-a465-d5f3b793711d" />
📄 License
This project is open-source and free to use for educational or personal purposes.
Would you like help writing a GitHub description or setting up a deployment for this project?




