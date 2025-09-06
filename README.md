# Capstone-Project-Movie-Recommendation-App
Build a full-featured movie recommendation platform where users can discover, search, and save their favorite movies.
movie-recommendation-app/
│── backend/                  # Express + MongoDB API
│   ├── src/
│   │   ├── config/           # DB connection, environment configs
│   │   ├── controllers/      # Route controllers (auth, movies, users)
│   │   ├── middleware/       # Auth middleware (JWT)
│   │   ├── models/           # Mongoose models (User, Movie, Watchlist)
│   │   ├── routes/           # Express routes (authRoutes.js, movieRoutes.js)
│   │   ├── utils/            # Helpers (e.g., password hashing, validators)
│   │   └── server.js         # App entry point
│   ├── .env                  # Environment variables (DB_URI, JWT_SECRET)
│   ├── package.json
│   └── README.md
│
│── frontend/                 # React App
│   ├── public/
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Pages (Home, Login, Register, Dashboard)
│   │   ├── services/         # API calls (Axios/fetch)
│   │   ├── context/          # Auth & state management
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│   └── README.md
│
│── README.md                 # Main project documentation
│── LICENSE


