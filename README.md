
🏡 LivoraStays – Travel Stay Booking Platform

LivoraStays is a full-stack web application inspired by Airbnb.
Users can explore stays, create and manage listings, upload images, view locations on map, and leave reviews.
The project focuses on backend development, authentication, file uploads, and real-world features used in modern web apps.

🚀 Live Demo
🔗 Live URL: https://livorastays.onrender.com/

🛠 Tech Stack
Frontend
EJS (templating)
Bootstrap (responsive UI)
Vanilla CSS
Backend
Node.js
Express.js
MongoDB (MongoDB Atlas)
Mongoose
Authentication & Sessions
Passport.js (Local Strategy)
Express-session
Connect-mongo (session store)
File Upload & Media
Multer (file handling)
Cloudinary (cloud image storage)
Maps & Location
Mapbox (Geocoding & Map view)

Other Tools:-
Joi (server-side validation)
Method-override
EJS-Mate (layouts)
dotenv

✨ Features
User authentication (signup, login, logout)
Create, edit, delete listings (CRUD)
Upload listing images (Cloudinary)
Location mapping using Mapbox
Review system (add/delete reviews)
Authorization (only owner can edit/delete listing)
Session & cookie management
Search & category filtering
Fully responsive UI

MVC architecture - Models,Views,Controllers
LivoraStays/
│
├── app.js
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── middleware.js
├── multer.middleware.js
├── utils/
│   └── cloudinary.js
├── .env
└── package.json

🧑‍💻 RUN LOCALLY :-
1️⃣ Clone the repo
git clone https://github.com/your-username/LivoraStays.git
cd LivoraStays
2️⃣ Install dependencies
npm install
3️⃣ Add environment variables
Create .env file (as shown above)
4️⃣ Start the server
npm start
5️⃣ Open in browser
http://localhost:8080
