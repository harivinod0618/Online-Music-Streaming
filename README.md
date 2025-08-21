Online Music Streaming Platform

A full-stack music streaming web application built using React, Node.js, Express, MongoDB, and Firebase Authentication.
This platform provides a role-based experience where admins can upload/manage songs, while users can stream, like, and comment on music tracks.

Features

Secure Authentication with Firebase (Signup/Login with role-based access)

Music Management: Admins can upload, edit, or delete songs

User Engagement: Users can like songs and leave comments

Responsive UI built with React for smooth user/admin experience

RESTful API with Express & MongoDB for efficient data handling

Scalable architecture suitable for real-world deployment

Tech Stack

Frontend: React.js

Backend: Node.js + Express.js

Authentication: Firebase Authentication

Database: MongoDB (via Mongoose)

Styling: CSS / Bootstrap / Tailwind (if used)

Other: REST APIs, role-based access control

Project Structure
Online-Music-Streaming/
├── app.js               # Main server file
├── models/              # Database models (User, Song, Comment, Like)
├── routes/              # API routes (e.g., songs, auth, comments)
├── views/               # Templates (if Pug/HTML used)
├── public/              # Static assets (CSS, JS, Images)
├── data/                # Sample data or seed files
├── package.json         # Dependencies
└── README.md            # Project Documentation
Installation & Setup

Clone the repository

git clone https://github.com/harivinod0618/Online-Music-Streaming.git
cd Online-Music-Streaming

Install dependencies

npm install

Set up Firebase Authentication

Go to Firebase Console

Create a project and enable Email/Password Authentication

Add your Firebase config keys in config/firebase.js

Set up MongoDB

Use MongoDB Atlas or local MongoDB

Create a .env file in the root with:

MONGO_URI=your_mongodb_connection_string
PORT=5000

Run the server

npm start

Open your browser at:
http://localhost:5000

Usage

Admin: Upload and manage music tracks (CRUD operations).

Users: Browse songs, play them, like, and comment.

Authentication: Only logged-in users can engage with songs.

Contributing

Contributions are welcome!

Fork this repo

Create a new branch: git checkout -b feature-name

Commit changes: git commit -m "Add feature"

Push the branch: git push origin feature-name

Open a Pull Request

License

This project is licensed under the MIT License.
Feel free to use, modify, and distribute it as per the license.

Future Enhancements

Add real-time audio streaming support

Build a mobile app version with React Native

Add search and playlist features

Add analytics for admin to track user engagement

Author

Developed by Hari Vinod
GitHub Profile
