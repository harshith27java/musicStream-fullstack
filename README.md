# Music Streaming Application

A full-stack music streaming application with a user interface for playback and an administrative panel for managing songs and albums. The system is built using a modular architecture with separate frontend, backend, and admin services.

## Features

- Audio playback with play, pause, and track switching
- Song and album browsing interface
- Centralized state management for playback control
- Admin panel for uploading and managing songs and albums
- Cloud-based media storage and delivery
- RESTful API architecture

## Tech Stack

Frontend:
- React
- Tailwind CSS
- Context API

Admin Panel:
- React
- Tailwind CSS

Backend:
- Node.js
- Express.js

Database:
- MongoDB

Media Storage:
- Cloudinary

## Architecture

- Frontend and admin panel communicate with the backend via REST APIs
- Backend handles business logic, database operations, and media uploads
- Media files are stored in cloud storage and served via URLs

## Project Structure
project-root/
│
├── spotify-clone
├── spotify-admin
├── spotify-backend

## Setup Instructions

1. Clone the repository
git clone https://github.com/harshith27java/musicStream-fullstack.git

2. Install dependencies
cd spotify-backend
npm install
cd ../spotify-clone
npm install
cd ../spotify-admin
npm install

3. Configure environment variables

Create a `.env` file in the backend directory and add:
MONGODB_URI=your_mongodb_connection
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_SECRET_KEY=your_secret_key

4. Run the application

Start backend:
cd spotify-backend
npm run server

Start frontend:
cd spotify-clone
npm run dev

Start admin panel:
cd spotify-admin
npm run dev

## Future Improvements

- User authentication and authorization
- Playlist management
- Streaming optimization
- Search and recommendation system
- Performance improvements with caching

## License

This project is for educational purposes.
