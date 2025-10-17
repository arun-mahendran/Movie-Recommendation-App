# 🎬 Movie Recommendation App

A front-end demo web application that lets users browse movies, get recommendations, and maintain a watchlist. The app uses sample movie data and stores user preferences locally in the browser.

Features

Browse movies with posters, genres, and ratings.

Search movies by title.

Filter movies by genre.

Add movies to a personal watchlist.

Get personalized recommendations based on saved watchlist.

Rate movies (1–5 stars) to influence recommendations.

Responsive and visually appealing dark-themed UI.

Technologies Used

Frontend: HTML5, CSS3, JavaScript

Styling: CSS Grid, Flexbox

Storage: Browser localStorage (for ratings and watchlist)

Data: Sample movie dataset with poster URLs (TMDb images)

Deployment: Can be hosted on GitHub Pages or any static web host

Installation & Usage

Clone or download this repository.

Open index.html in your preferred browser.

Use the search bar and genre filter to explore movies.

Click "+ Watchlist" to save a movie to your personal watchlist.

Click Get Recommendations to view suggested movies based on your saved list.

File Structure
/Movie-Recommendation-App
│
├── index.html         # Main HTML file with embedded CSS & JS
├── README.md          # Project overview and instructions
└── assets/            # Optional folder for images or additional resources

How It Works

The app loads a sample dataset of movies with poster URLs and metadata.

Users can search, filter, and sort movies dynamically.

Ratings and watchlist data are saved in the browser using localStorage.

Recommendations are generated based on the user’s watchlist and ratings.

The UI is fully responsive and works across desktop and mobile devices.

Future Enhancements

Integrate with a real movie API (e.g., TMDb) to fetch live data.

Add user authentication for personal watchlists across devices.

Include reviews, trailers, and more movie details.

Implement advanced recommendation algorithms (collaborative or content-based filtering).
