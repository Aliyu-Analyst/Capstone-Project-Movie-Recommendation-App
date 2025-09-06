# Capstone-Project-Movie-Recommendation-App
Build a full-featured movie recommendation platform where users can discover, search, and save their favorite movies.

📅 Week-by-Week Roadmap (3 Weeks)

📌 Week 14 – Setup & Basic Features
Backend (Express + MongoDB)
Initialize project:

 mkdir movie-app && cd movie-app
npm init -y
npm install express mongoose cors dotenv


Setup Express server (server.js)


Connect to MongoDB (use MongoDB Atlas)


Create models:


User (username, email, password hash)


Movie (title, genre, year, rating, description)


Setup routes:


GET /movies → fetch all movies


GET /movies/:id → fetch single movie


Frontend (React)
Initialize React app:

 npx create-react-app client
cd client
npm install axios react-router-dom


Create basic pages:


Home (list of movies)


Movie Details


Fetch movies from backend with Axios.


Setup React Router for navigation.


✅ By end of Week 14: You have a React frontend connected to Express backend displaying movie data.

📌 Week 15 – Advanced Features & Authentication
Backend
Install JWT authentication:

 npm install bcrypt jsonwebtoken


Create authentication routes:


POST /auth/register → register user (hash password with bcrypt)


POST /auth/login → login, return JWT token


Secure movie endpoints (require JWT).


Frontend
Add User Authentication UI:


Register & Login forms


Store JWT token in localStorage


Use token for protected requests (Axios interceptor).


Add Search & Filters:


Search by title/genre/year


Filter by rating, release date


Add Favorites & Watchlist (connect with backend).


✅ By end of Week 15: You have authentication working, users can login/register, search movies, and save favorites.

📌 Week 16 – Polish & Deployment
Backend
Finalize endpoints:


Save favorites/watchlist


Rate/review movies


User profile management


Integrate with TMDB API for real movie data.


Frontend
Responsive design (mobile + desktop)


Profile page (favorites, reviews, watchlist)


Add personalized recommendations (based on favorites/ratings).


Deployment
Deploy frontend to Netlify or Vercel.


Deploy backend to Render or Heroku.


Setup CI/CD pipeline (GitHub → Netlify/Render auto-deploy).


✅ By end of Week 16: Fully working deployed app with authentication, movie discovery, and personalized features.

